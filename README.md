# Solange Galiano - Counselling Website

This repository contains a static version of Solange Galiano's counselling website, designed to be hosted on GitHub Pages with the domain solangegaliano.ca.

## Overview

The website is a static HTML/CSS/JS implementation based on the design of https://solangegaliano.wixsite.com/website. It includes the following pages:

- Home (index.html)
- Counselling (counselling.html)
- Approaches (approaches.html)
- Mental Disorders (mental-disorders.html)

## Setup Instructions

### 1. Images

Before deploying the site, you need to:

1. Download images from the original site to replace the placeholders
2. Place them in the `/images` directory
3. The main background image should be named `hero-bg.jpg`

### 2. GitHub Pages Setup

To deploy this site on GitHub Pages with a custom domain:

1. Push this repository to GitHub
2. Go to the repository settings on GitHub
3. Navigate to the "Pages" section
4. Select the branch to deploy (usually `main`)
5. Enter your custom domain: `solangegaliano.ca`
6. Wait for the DNS to propagate and SSL certificate to be generated

### 3. DNS Configuration

For the domain `solangegaliano.ca`, you'll need to configure the following DNS records with your domain provider:

- Type: A
  - Name: @
  - Value: 185.199.108.153
  - Value: 185.199.109.153
  - Value: 185.199.110.153
  - Value: 185.199.111.153
  
- Type: CNAME
  - Name: www
  - Value: username.github.io (replace username with your GitHub username)

### 4. HTTPS Setup

GitHub Pages automatically provides HTTPS for custom domains. Once your DNS is properly configured, GitHub will automatically issue and renew an SSL certificate for your site.

## Development

If you need to modify the site:

1. Edit the HTML, CSS, or JavaScript files
2. Test locally by opening the HTML files in a browser
3. Commit and push your changes to GitHub
4. GitHub Pages will automatically rebuild and deploy your site

## Credits

- Original website design: https://solangegaliano.wixsite.com/website
- Development: [Your Name]
- Fonts: Google Fonts (Montserrat & Playfair Display)
