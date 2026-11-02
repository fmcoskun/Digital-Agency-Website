# Digital Agency Website

A responsive, single-page landing site for a digital marketing agency, built with Bootstrap 5 and plain HTML, CSS and JavaScript. No build step, no framework, no dependencies to install.

**🔗 Live demo:** https://fmcoskun.github.io/Digital-Agency-Website/

![Digital Agency Website demo](images/demo.gif)

## Features

- Responsive navbar with a collapsible mobile menu
- Hero banner with call-to-action button
- Services section (Growth Marketing, Online Branding, Animated Ads)
- "Why choose us" section with a network illustration
- Client testimonials
- Social media links and footer
- Smooth scrolling between sections

## Tech Stack

- [Bootstrap 5.2](https://getbootstrap.com/) (grid, navbar, utilities) via CDN
- [Bootstrap Icons](https://icons.getbootstrap.com/) and [Font Awesome 6](https://fontawesome.com/) via CDN
- Custom CSS (`style.css`)
- [SmoothScroll](https://github.com/cferdinandi/smooth-scroll) v16.1.4 (`smooth-scroll.js`, MIT)

## Getting Started

The site is static, so you can run it by opening the file directly:

```bash
git clone https://github.com/fmcoskun/Digital-Agency-Website.git
cd Digital-Agency-Website
```

Then open `index.html` in your browser.

To serve it locally with a simple web server instead:

```bash
npx serve .
# or
python -m http.server 8000
```

## Project Structure

```
.
├── index.html          # Main page and all sections
├── style.css           # Custom styles
├── smooth-scroll.js    # Smooth scrolling for in-page links
├── images/             # Logos, icons, illustrations, and demo GIF
└── .github/workflows/  # GitHub Pages deployment workflow
```

## Deployment

The site is deployed to GitHub Pages with a GitHub Actions workflow (`.github/workflows/pages.yml`). Every push to `main` publishes the latest version.

## Customization

- **Text and content:** edit the sections in `index.html`.
- **Colors and layout:** adjust the styles in `style.css`.
- **Images:** replace the files in `images/`, keeping the same file names or updating the `src` attributes.

## Author

[@fmcoskun](https://github.com/fmcoskun)
