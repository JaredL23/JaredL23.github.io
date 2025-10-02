# Portfolio Site - Replit Setup

## Project Overview
Static HTML portfolio website showcasing Jared Lafferty's software engineering projects. Originally designed for GitHub Pages, now configured to run on Replit.

## Structure
- **Main site**: `JaredL23.github.io/index.html` - Portfolio homepage
- **Documentation**: `JaredL23.github.io/docs/` - Sample developer documentation

## Technology Stack
- Pure HTML, CSS, and vanilla JavaScript
- No build process or dependencies
- Python HTTP server for local/Replit serving

## Development
- **Server**: Python's built-in HTTP server
- **Port**: 5000 (bound to 0.0.0.0)
- **Workflow**: Automatically serves files from `JaredL23.github.io` directory

## Deployment
- **Type**: Autoscale (static site, no persistent state needed)
- **Command**: Python HTTP server serving the static files
- **No build step required**: Site is already compiled/ready to serve

## Recent Changes (Oct 2, 2025)
- Imported from GitHub repository
- Configured Python 3.12 environment
- Set up workflow to serve static files on port 5000
- Configured autoscale deployment for production
