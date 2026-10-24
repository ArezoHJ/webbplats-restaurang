# Björk & Bord

**A responsive restaurant website for a fictional Swedish neighbourhood restaurant.**

Designed and built by **Arezo Jafari** — Software Engineer | Full-Stack Engineer.

> This project focuses on frontend development with HTML and CSS. It does not include a backend, JavaScript, online reservations, or payment processing.

## Overview

Björk & Bord is a polished, mobile-first website concept for a seasonal Swedish restaurant. Visitors can explore the menu, learn about the restaurant, and find its opening hours and contact details.

## Features

- Responsive layouts for mobile, tablet, and desktop.
- Semantic HTML sections and a logical heading hierarchy.
- Accessible navigation, a skip-to-content link, visible keyboard focus, and descriptive image alternatives.
- CSS Grid and Flexbox layouts, with reduced-motion preferences respected.
- Contact links that start an email reservation request.
- Search-friendly page title and meta description.

## Built with

- HTML5
- CSS3

No frameworks, JavaScript, or backend services are required.

## Run locally

Clone the repository and start a local web server:

```bash
git clone https://github.com/YOUR-USERNAME/webbplats-restaurang.git
cd webbplats-restaurang
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. You can also open `index.html` directly, but a local server is recommended for development.

## Project structure

```text
webbplats-restaurang/
├── index.html   # Page content and semantic markup
├── styles.css   # Responsive layout, colours, and typography
└── README.md    # Project documentation
```

## Design and implementation

The visual direction combines a forest-green palette, warm neutral backgrounds, and editorial-style typography. The page is designed mobile-first, then uses CSS media queries to make better use of wider screens.

Restaurant photography is loaded from Unsplash. An internet connection is needed to display those images.

## Scope and future improvements

This is a frontend portfolio project, not a production restaurant booking system. Possible next steps include adding a working booking flow, connecting the menu to a content management system, and introducing a backend API.

## Author

**Arezo Jafari**

Software Engineer | Full-Stack Engineer

- GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)

Replace `YOUR-USERNAME` in the clone command and profile link with your GitHub username.
