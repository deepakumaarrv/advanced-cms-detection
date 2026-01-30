# Advanced CMS Detection - Nuclei Template

This repository contains a Nuclei template to **detect major CMS platforms** (WordPress, Drupal, Joomla, Magento, Ghost, TYPO3, Strapi, Contentful) using headers, meta tags, JS files, APIs, and common paths.

## Author
Deepak

## Template ID
`advanced-cms-detection`

## Usage
1. Install Nuclei:
```bash
go install -v github.com/projectdiscovery/nuclei/v2/cmd/nuclei@latest
```

2. Clone this repository:
```bash
git clone https://github.com/<your-username>/advanced-cms-detection.git
cd advanced-cms-detection
```

3. Run the template:
```bash
nuclei -t templates/advanced-cms-detection.yaml -u https://example.com
```

## Supported CMS
- WordPress
- Drupal
- Joomla
- Magento
- Ghost
- TYPO3
- Strapi
- Contentful
