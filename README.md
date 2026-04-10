# Netflix Clone

## Overview

A pixel-faithful, static front-end recreation of the Netflix landing page, built with pure HTML and CSS. The project replicates the look and feel of the real Netflix sign-up page — including the hero section, feature highlights, FAQ accordion, and footer — targeting the Pakistani market. It demonstrates core web development skills such as responsive layout, CSS Grid, Flexbox, and media queries, with no frameworks or JavaScript required.

## Key Features

- **Hero Section** — Full-bleed background with an email capture prompt and "Get Started" call-to-action
- **Feature Sections** — Four highlight panels (Watch on TV, Download for offline, Watch everywhere, Kids profiles) with embedded autoplay videos and images sourced from Netflix's CDN
- **FAQ Section** — Interactive-style accordion items with hover state transitions
- **Responsive Design** — Fluid layouts via Flexbox and CSS Grid that reflow cleanly on screens below 1300 px
- **Custom Typography** — Google Fonts integration (Poppins & Martel Sans) for typographic fidelity
- **Footer** — Multi-column link grid matching the Netflix footer structure

## Tech Stack

| Category    | Technology                        |
|-------------|-----------------------------------|
| Language    | HTML5, CSS3                       |
| Fonts       | Google Fonts (Poppins, Martel Sans) |
| Assets      | SVG logo, JPEG/PNG images, M4V video |
| Tools       | Browser DevTools, VS Code         |

## Installation

No build tools or package managers are required.

```bash
# 1. Clone the repository
git clone https://github.com/MAbdullahWaqar/Netflix-clone.git

# 2. Navigate into the project directory
cd Netflix-clone
```

## Usage

Open `index.html` directly in any modern web browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows (PowerShell)
start index.html
```

Alternatively, serve the project locally with any static file server for a more realistic environment:

```bash
# Using Python's built-in server
python -m http.server 8000
# Then visit http://localhost:8000
```

## Project Structure

```
Netflix-clone/
├── index.html          # Main landing page markup
├── style.css           # Primary stylesheet (layout, components, responsive)
├── styles.css          # Additional stylesheet (reserved)
├── favicon.ico         # Browser tab icon
└── assets/
    ├── images/
    │   ├── bg.jpg      # Hero section background image
    │   └── logo.svg    # Netflix wordmark (SVG)
    └── videos/         # Local video assets directory
```

## UI Features

| Section              | Description                                                                                  |
|----------------------|----------------------------------------------------------------------------------------------|
| Navigation Bar       | Netflix logo on the left; language selector and "Sign In" button on the right                |
| Hero                 | Headline with pricing (Rs 299), subtitle, email input, and "Get Started" CTA button          |
| TV Highlight         | Two-column layout with a TV frame image and an embedded looping background video             |
| Download Highlight   | Reversed layout showcasing the mobile offline-download feature                               |
| Watch Everywhere     | Device grid image with an embedded multi-screen looping video                                |
| Kids Profiles        | Highlight panel for child-friendly profile creation                                          |
| FAQ Accordion        | Four expandable question items with plus-icon toggle and hover animation                     |
| Footer               | Four-column link grid with support phone number and standard Netflix footer links            |

## Configuration

No environment variables or configuration files are required. The project is entirely self-contained. Media assets for feature sections (TV frame, mobile image, and autoplay videos) are loaded from Netflix's public CDN:

```
https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/
```

To host all assets locally, download the referenced images and videos and update the `src`/`href` attributes in `index.html` accordingly.

## Contributing

1. Fork the repository and create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Commit your changes with a clear message following conventional commits.
3. Open a pull request describing the motivation and changes made.
4. Ensure the page renders correctly on both desktop (≥ 1300 px) and mobile (< 1300 px) viewports before submitting.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

> **Disclaimer:** This project is a non-commercial, educational clone created for learning purposes only. Netflix, the Netflix logo, and all associated trademarks are the property of Netflix, Inc.

## Author

**MAbdullahWaqar**  
GitHub: [@MAbdullahWaqar](https://github.com/MAbdullahWaqar)
