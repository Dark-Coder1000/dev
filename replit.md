# GitHub Dev Documentation Viewer

## Overview
This project displays documentation about GitHub's web-based editor (github.dev) as a simple static website. The original repository (github/dev) contains only a README file explaining GitHub's web-based VS Code editor feature.

## Project Type
Static documentation site with a simple Python HTTP server for development.

## Recent Changes
- **December 4, 2025**: Initial Replit setup
  - Created static HTML viewer for README content
  - Set up Python 3.11 HTTP server on port 5000
  - Configured deployment as static site
  - Added proper cache control headers to server

## Project Structure
- `index.html` - Static HTML page displaying the README content with GitHub-style dark theme
- `server.py` - Simple Python HTTP server for development (serves on 0.0.0.0:5000)
- `README.md` - Original documentation from github/dev repository

## Technology Stack
- Frontend: Static HTML/CSS
- Development Server: Python 3.11 SimpleHTTPServer
- Deployment: Static site hosting

## How It Works
- Development: Python server runs on port 5000, serving the static HTML
- Production: Deployed as a static site serving index.html and assets
- The HTML file replicates the README content with GitHub-style dark theme styling

## Notes
- This is a documentation-only repository with no application logic
- Server includes cache control headers to prevent browser caching issues
- Frontend configured to work with Replit's proxy environment
