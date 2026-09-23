# ConvertHtmlTemplateToAngular8

A responsive Angular landing page project created by converting a static HTML template into Angular components and modules.

This repository contains a modern marketing-style website with sections such as a hero intro, gallery, feature/content blocks, testimonials, client logos, pricing tables, social media links, and footer content.

## Overview

The project is built with Angular and follows a component-based structure so each section of the page is organized into reusable UI modules.

Key sections included in the app:

- Header navigation
- Intro/hero section
- Gallery section
- Content/feature section
- Testimonials
- Client logos
- Pricing tables
- Social links
- Footer

## Tech Stack

- Angular 16
- TypeScript
- HTML5 / CSS3
- Font Awesome
- Angular CLI

## Project Structure

```text
.
├── src/
│   ├── app/
│   │   ├── clients/
│   │   ├── content-section/
│   │   ├── footer/
│   │   ├── gallery/
│   │   ├── header/
│   │   ├── intro/
│   │   ├── navigation/
│   │   ├── pricing-tables/
│   │   ├── social/
│   │   ├── testimonials/
│   │   ├── app.component.ts
│   │   ├── app.component.html
│   │   ├── app.component.css
│   │   ├── app.module.ts
│   │   └── app-routing.module.ts
│   ├── assets/
│   ├── environments/
│   ├── index.html
│   ├── main.ts
│   ├── styles.css
│   └── ...
├── docs/
├── angular.json
├── package.json
├── tsconfig.json
├── note.txt
├── README.md
└── ...
```

## Getting Started

Install dependencies:

```bash
npm install
```

Run the application locally:

```bash
npm start
```

Then open the app in your browser:

```text
http://localhost:4200
```

## Build

To create a production build:

```bash
ng build
```

For GitHub Pages deployment, this repository includes a custom build command in `note.txt`:

```bash
ng build --output-path docs --base-href /ConvertHtmlTemplateToAngular8/
```

This generates a static site in the `docs` folder for deployment.

## Notes

- This project was originally based on a static HTML template and converted into Angular components.
- The compiled output is placed in the `docs` directory, which is useful for hosting on GitHub Pages.
- `font-awesome` and related assets are used for icons and styling.

## License

This project does not currently include a dedicated license file. Please check the repository settings or add a license if needed.
