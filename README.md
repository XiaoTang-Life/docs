# Mossi Documentation

This directory contains the official documentation for Mossi app, published via GitHub Pages.

## Published Documentation

- **Privacy Policy**: Available in English, French, and Simplified Chinese

## Local Development

To preview the documentation locally:

```bash
# Install Jekyll (if not already installed)
gem install bundler jekyll

# Serve the site locally
cd docs
jekyll serve

# Visit http://localhost:4000 in your browser
```

## Deployment

This documentation is automatically deployed to GitHub Pages from the `/docs` directory on the main branch.

**Live Site**: `https://[username].github.io/XiaoTang-Life/`

## File Structure

```
docs/
├── index.md              # Homepage
├── _config.yml           # Jekyll configuration
├── README.md            # This file
└── Mossi/
    └── PrivacyPolicy.md # Privacy policy (multilingual)
```

## Contributing

When updating documentation:
1. Edit the relevant Markdown files
2. Commit and push to the main branch
3. GitHub Pages will automatically rebuild (takes 1-2 minutes)

---

*For questions or issues, please open an issue on GitHub.*

