# shortlinks

A simple, easily manageable, shortlinks solution using Jekyll and GitHub Pages

## Preview
Visit [go.rambots.org](https://go.rambots.org) to see a live preview of this repository.

## Setup
To use shortlinks for yourself, you can download this repository as a ZIP file, or clone it using Git.

```bash
git clone https://github.com/frc2204/shortlinks.git
```

### Configuration
Under the `_config.yml` file, you can change the following settings:

```yaml
name: Shortlinks # Name it whatever you want
description: A simple, easily manageable, shortlinks solution using Jekyll and GitHub Pages # Describe your site
```

### GitHub Pages
To host your shortlinks on GitHub Pages, you must enable it in the repository settings.

For more information regarding GitHub Pages, visit [pages.github.com](https://pages.github.com).

The GitHub action included with this repository will automatically build and deploy your shortlinks to GitHub Pages - no
need to worry about that.

### Managing Shortlinks

To add a shortlink, simply add a new file ending with `.html` or `.md` to the `_shortlinks` directory.

The file should contain the following information (front matter):

```yaml
---
target: https://example.com # The URL to redirect to
permalink: /example-shortlink/ # The shortened link (relative path)
---
```

> **Note:** The actual filename does not matter, but it is recommended to use the same name as the permalink.

Deletion is pretty straightforward, just delete the file from the `_shortlinks` directory.