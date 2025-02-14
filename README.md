# Vertical Guam Landing Page

A modern landing page for Vertical Guam's container farming business.

## Description

This is a simple, responsive landing page built with HTML and CSS for Vertical Guam, showcasing their innovative container farming solutions in Guam.

## Deployment Instructions

To deploy this site to GitHub Pages:

1. Create a new repository on GitHub
2. Push these files to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin [your-repository-url]
   git push -u origin main
   ```
3. Go to your repository settings on GitHub
4. Navigate to "Pages" under "Code and automation"
5. Under "Source", select "Deploy from a branch"
6. Select "main" branch and "/ (root)" folder
7. Click "Save"

## Domain Setup

To point your domain (verticalguam.com) to GitHub Pages:

1. Go to your domain registrar's DNS settings
2. Add these A records pointing to GitHub Pages' IP addresses:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
3. Add a CNAME record:
   - Host: www
   - Points to: [your-username].github.io

## Local Development

To run this site locally, simply open the `index.html` file in your web browser.

## Credits

Designed and developed by [Adam Pang](https://adampang.com)