# Björk & Bord

**A responsive website concept for a fictional Swedish neighbourhood restaurant.**

Designed and built by **Arezo Hazara Jafari** — Software Engineer | Full-Stack Engineer.

> This portfolio project demonstrates frontend development with HTML and CSS. It does not include a backend, JavaScript, online booking system, or payment processing.

## Overview

Björk & Bord is a mobile-first website concept for a seasonal Swedish restaurant. Visitors can explore sample dishes, learn about the restaurant, and find its opening hours and contact details.

## Features

- Responsive layouts for screen widths from 360 px to 980 px and wider.
- Semantic HTML sections and a logical heading hierarchy.
- Accessible navigation, a skip-to-content link, visible keyboard focus, and descriptive image alt text.
- CSS Grid and Flexbox layouts, plus support for reduced-motion preferences.
- Email links for reservation requests; reservations are not processed by the website.
- A descriptive page title and meta description.

## Built with

- HTML5
- CSS3

No frameworks, JavaScript, or backend services are required.

## Run the project

### In IntelliJ IDEA

1. Open the project folder in IntelliJ IDEA.
2. In the Project panel, locate `index.html`.
3. Right-click the file and choose **Open In → Browser**.

The site is static, so `Main.java` is not needed to run it. If the browser option is unavailable, open `index.html` directly in a browser.

### From a terminal

```bash
git clone https://github.com/ArezoHJ/webbplats-restaurang.git
cd webbplats-restaurang
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Project structure

```text
webbplats-restaurang/
├── index.html   # Semantic page content
├── styles.css   # Responsive styles and visual design
└── README.md    # Project documentation
```

## Design notes

The design pairs forest-green colours and warm neutral backgrounds with editorial-style typography. CSS media queries adapt the mobile-first layout for wider screens. Restaurant photography is served by Unsplash, so an internet connection is needed to load the images.

## Future improvements

- Add a functional reservation flow.
- Connect restaurant content to a content management system.
- Develop a backend API if the project scope expands.

## Author

**Arezo Hazara Jafari** · Software Engineer | Full-Stack Engineer

[GitHub profile](https://github.com/ArezoHJ)
