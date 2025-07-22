# OptimalHRV Documentation

<p align="center">
    <img src="docs/assets/images/OptimalHRV_CMYK_Logo.png" style="width: 200px;" alt="OptimalHRV Logo"> 
</p>

<p align="center"> 
    <b>Comprehensive Documentation for OptimalHRV Platform</b>
</p>    

<p align="center">
    <a href="https://www.optimalhrv.com/" target="_blank">Official Website</a> | 
    <a href="https://optimalhrv.com/devices" target="_blank">HRV Reader</a> | 
    <a href="https://docs.optimalhrv.com/#/" target="_blank">Documentation</a>
</p>

# Quick Start with Docsify

This documentation is built with [Docsify](https://docsify.js.org/) for easy maintenance and deployment.

## Local Development

```bash
# Install docsify-cli globally
npm install -g docsify-cli

# Serve the documentation locally
docsify serve docs

# Open http://localhost:3000 in your browser
```

## Deployment

Since Docsify renders on the fly, no build process is required. Simply:

1. **GitHub Pages**: Push to GitHub and enable Pages from `/docs` folder
2. **Static Hosting**: Upload the `/docs` folder to any web server

## File Structure

```
docs/
├── index.html          # Entry point
├── _coverpage.md       # Landing page
├── _sidebar.md         # Navigation
├── _navbar.md          # Top navigation
└── *.md               # Content files
```

# Documentation Structure

```
📚 OptimalHRV Documentation
├── 🏠 [Cover Page](docs/_coverpage.md)
│   └── Landing page with branding & quick access
├── 📱 [Mobile App Guide](docs/mobile-app.md)
│   ├── Device connection and setup
│   ├── Taking HRV readings
│   ├── Biofeedback training sessions
│   └── Troubleshooting and support
├── 📊 [Web Dashboard Manual](docs/web-dashboard.md)
│   ├── Organizational setup and user management
│   ├── Group monitoring and analytics
│   └── Professional features for coaches and clinicians
├── 🔬 [HRV Reader Manual](docs/Others/user-manual.md)
│   ├── Device specifications and operation
│   ├── Charging and maintenance
│   └── Technical specifications
├── 📋 [Support & Resources](docs/Others/)
│   ├── [Technical Support](docs/Others/support.md)
│   └── [Subscription Management](docs/subscription.md)
└── 📝 [Changelog](docs/changelog.md)
    └── Version history and updates

# License & Copyright

© 2025 by Optimal, LLC. All rights reserved.

This documentation is built with [Docsify](https://docsify.js.org/) and the [docsify-darklight-theme](https://github.com/boopathikumar018/docsify-darklight-theme).

