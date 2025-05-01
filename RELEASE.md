# Release Notes

## v1.0.0-beta (May 1, 2025)

We're excited to announce the first beta release of GPX Scraper, a command-line tool designed to simplify downloading GPX files from websites.

### Features

- **Single File Download**: Download individual GPX files from any webpage with a simple command
- **Batch Processing**: Download multiple GPX files from a list of links
- **Organized Storage**: Automatically organize downloads into hierarchical folder structures based on page titles
- **Command-line Interface**: Easy integration into scripts and automation workflows
- **Interactive Mode**: User-friendly interactive mode for manual operation

### Installation

```bash
# Using pip
pip install gpx-scraper

# Using Poetry
poetry add gpx-scraper

# From GitHub
pip install git+https://github.com/ironscripter/gpx-scraper.git
```

### Usage Examples

Download a single GPX file:
```bash
gpx-scraper download https://example.com/hike-page
```

Download multiple GPX files from a list page:
```bash
gpx-scraper batch https://example.com/hikes-list --organize
```

Run in interactive mode:
```bash
gpx-scraper interactive
```

### Dependencies

- Python ≥ 3.7
- requests ≥ 2.25.0
- beautifulsoup4 ≥ 4.9.0

### Known Limitations

- Some websites with complex JavaScript rendering may not be fully supported
- Rate limiting is not yet implemented for batch downloads

### What's Next

We're working on the following features for upcoming releases:
- Support for more complex website structures
- Rate limiting for respectful scraping
- Additional output formats beyond GPX
- Improved error handling and recovery

### Feedback and Contributions

We welcome your feedback and contributions! Please open issues or submit pull requests on our [GitHub repository](https://github.com/ironscripter/gpx-scraper).

### License

This project is licensed under the MIT License - see the LICENSE file for details.
