# Harbor Light Community Center

A welcoming community website for Harbor Light Community Center, designed to highlight local programs, services, events, and contact information in a clear, accessible, and friendly way.

## Overview

This project creates a simple, semantic, and accessible webpage that includes:

- a clear site header and navigation
- structured sections for About Us, Services, and Events
- accessible image descriptions and ARIA support
- schema markup for the featured event
- a contact section with direct email communication
- responsive styling and updated HTML best practices

## Project Structure

- `index.html` — main webpage markup and styling
- `logo.jpg` — community center logo image
- `community-center.jpg` — community image for the About section
- `banner.jpg` — decorative banner image

## Features

- Semantic HTML using `header`, `nav`, `main`, `section`, `footer`, and `time`
- In-page anchor navigation linking to About, Services, Events, and Contact
- Accessibility improvements including proper `alt` text, skip links, and ARIA labels
- Schema.org Event markup for search engine understanding
- Clean, internal CSS with improved typography and spacing
- Local assets included so the site renders without external dependencies

## Accessibility and SEO Improvements

This website was built with accessibility and structure in mind:

- all non-decorative images include descriptive `alt` text
- the decorative banner is hidden from screen readers with `aria-hidden="true"`
- navigation is given the `role="navigation"` attribute
- the event section includes `itemprop` metadata for search-friendly structured data
- headings and sections follow a logical HTML structure for keyboard and assistive tech users

## Run Locally

Open `index.html` in a browser, or serve the folder with a simple local web server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## License

This project is for educational and community use.

## Contact

For inquiries about the Harbor Light Community Center site:

- Email: info@harborlight.com
