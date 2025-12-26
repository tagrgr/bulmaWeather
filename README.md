# weatherWeather

A responsive weather forecast web client built using **Eleventy (11ty)** and **Bulma CSS**.  
The project focuses on clean layout structure, reusable templates, and mobile-first design.

---

## Project Overview

This application displays weather-related information using a static-site approach powered by Eleventy.  
It is designed for clarity, responsiveness, and ease of maintenance, using Bulma for layout and styling.

Key features include:
- Reusable layouts and partials
- Responsive grid and card layouts
- City-based pages
- Clean navigation structure
- Static-site generation with Eleventy

---

## Getting Started

### Prerequisites

- **Node.js** (LTS recommended)
- **npm**

Verify installation:

```bash
node -v
npm -v
```

### Install Dependencies

```bash
npm install
```

### Install Eleventy

```bash
npm install -g @11ty/eleventy
```

### Run the project by Eleventy locally

```bash
eleventy --serve
```

Then open: [http://localhost:8080](http://localhost:8080) to see your site.

## Project Structure

```text
.
├── _includes/        # Layouts and reusable partials (nav, header, footer, components, layout, impress, etc.)
├── _site/            # Generated output (do not edit manually)
├── css/              # UX that we couldn't accomplish by Bulma.
├── images/           # Static assets
├── .eleventy.js      # eleventy config 
├── *.njk             # Pages and templates
├── package.json
└── README.md
```

## Technologies

* [Eleventy (11ty)](https://www.11ty.dev/)
* [Bulma](https://bulma.io/)
* [HTML / CSS]
* [Nunjucks templates](https://mozilla.github.io/nunjucks/)
* [Netlify with Git-based continuous deployment](https://www.netlify.com/)

# https://bulmaweather.netlify.app/
**Live Site (Netlify)**  