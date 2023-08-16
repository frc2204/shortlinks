# shortlinks

A simple, easily manageable, shortlinks solution using Jekyll and GitHub Pages

## Usage
To begin using shortlinks, simply add a new file to the `_shortlinks` directory.

The file should contain the following information (front matter):
```yaml
---
target: https://example.com # The URL to redirect to
permalink: /example-shortlink/ # The shortened link (relative path)
---
```

> **Note:** The actual filename does not matter, but it is recommended to use the same name as the permalink.