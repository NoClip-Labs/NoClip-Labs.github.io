# NoClip Labs Documentation

A comprehensive documentation site for NoClip Labs FiveM scripts, built with HTML, CSS, and JavaScript. This site is designed to work with GitHub Pages and provides detailed documentation for our projects.

## Features

- **Dark Theme**: High contrast dark theme for excellent readability
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Comprehensive Documentation**: Detailed guides for installation, configuration, and troubleshooting
- **Interactive Elements**: Copy code buttons, smooth scrolling, and mobile navigation
- **Search Functionality**: Built-in search capabilities for finding specific information
- **GitHub Pages Ready**: Optimized for deployment on GitHub Pages

## Projects Covered

### noclip_crafting
- Comprehensive crafting script for FiveM servers
- Multiple locations, job-based access, blueprint system
- Skill progression and experience-based crafting
- Full ox_lib and ox_inventory integration

### noclip_drugs
- Advanced drug manufacturing and distribution system
- Addiction mechanics with withdrawal effects
- Dynamic pricing and market system
- Drug influence persistence across server restarts

## File Structure

```
NoClip-Labs.github.io/
├── index.html                 # Main landing page
├── styles.css                 # Main stylesheet
├── script.js                  # JavaScript functionality
├── troubleshooting.html       # General troubleshooting guide
├── noclip-crafting/          # noclip_crafting documentation
│   ├── index.html            # Overview page
│   ├── installation.html     # Installation guide
│   ├── configuration.html    # Configuration guide
│   ├── exports.html          # Exports and API documentation
│   └── troubleshooting.html  # Project-specific troubleshooting
├── noclip-drugs/             # noclip_drugs documentation
│   ├── index.html            # Overview page
│   ├── installation.html     # Installation guide
│   ├── configuration.html    # Configuration guide
│   ├── exports.html          # Exports and API documentation
│   └── troubleshooting.html  # Project-specific troubleshooting
└── README.md                 # This file
```

## Deployment

### GitHub Pages Setup

1. **Repository Setup**:
   - Create a new repository named `NoClip-Labs.github.io`
   - Upload all files to the repository

2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Navigate to Pages section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

3. **Custom Domain (Optional)**:
   - In Pages settings, add your custom domain
   - Update DNS records accordingly

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/NoClip-Labs/NoClip-Labs.github.io.git
   cd NoClip-Labs.github.io
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience

3. **Using a local server**:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

## Customization

### Adding New Projects

1. Create a new folder for your project in the root directory
2. Add the following files:
   - `index.html` - Project overview
   - `installation.html` - Installation guide
   - `configuration.html` - Configuration guide
   - `exports.html` - Exports and API documentation
   - `troubleshooting.html` - Project-specific troubleshooting

3. Update the navigation in all HTML files to include your new project

### Styling

The site uses a modular CSS approach:
- `styles.css` contains all styles
- Dark theme with blue accent colors
- Responsive design with mobile-first approach
- Custom components for alerts, cards, and interactive elements

### JavaScript Features

- Mobile menu toggle
- Smooth scrolling navigation
- Copy code functionality
- Table of contents generation
- Search functionality
- Scroll to top button

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This documentation site is part of the NoClip Labs project. Please refer to the individual project licenses for specific terms.

## Support

For issues with the documentation site:
- Create an issue on GitHub
- Contact the development team

For issues with the actual scripts:
- Check the troubleshooting guides
- Create an issue in the respective project repository 