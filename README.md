# SCSS Dashboard Practice

A responsive dashboard layout created as a learning project for practicing SCSS architecture, reusable components, responsive design, and working with SVG sprites.

## Overview

This project was built for educational purposes while learning SCSS/Sass.  
The main focus of the project is not JavaScript functionality, but styling, layout structure, reusable SCSS components, and responsive UI implementation.

The application includes a dashboard page and a separate companies page. The layout is built with HTML, SCSS, CSS Grid, Flexbox, and Vite.

## Pages

- `index.html` — main dashboard page
- `companies.html` — companies page

## Technologies Used

- HTML5
- SCSS / Sass
- CSS Grid
- Flexbox
- SVG sprites
- Responsive design
- Vite
- PostCSS
- Autoprefixer

## Features

- Responsive dashboard layout
- Separate companies page
- Sidebar navigation
- Header with search and notification buttons
- Reusable button system with different button types
- Company cards
- Task reports with progress bars
- Co-workers section
- Task list section
- SVG sprite icons
- Custom Montserrat fonts
- Mobile-first styling approach
- Organized SCSS file structure

## Project Structure

```text
/
├── public/
│   └── sass.svg
│
├── src/
│   ├── fonts/
│   │   ├── Montserrat-Regular.woff
│   │   ├── Montserrat-Regular.woff2
│   │   ├── Montserrat-Medium.woff
│   │   ├── Montserrat-Medium.woff2
│   │   ├── Montserrat-SemiBold.woff
│   │   ├── Montserrat-SemiBold.woff2
│   │   ├── Montserrat-Bold.woff
│   │   └── Montserrat-Bold.woff2
│   │
│   ├── img/
│   │   ├── avatars/
│   │   ├── webp/
│   │   ├── icons.svg
│   │   └── logo-sass.png
│   │
│   ├── js/
│   │   └── main.js
│   │
│   └── scss/
│       ├── base/
│       │   ├── _base.scss
│       │   ├── _fonts.scss
│       │   ├── _reset.scss
│       │   ├── _visually-hidden.scss
│       │   └── _index.scss
│       │
│       ├── components/
│       │   ├── btn/
│       │   │   ├── _btn.scss
│       │   │   ├── _btn.base.scss
│       │   │   └── types/
│       │   ├── companies/
│       │   │   ├── _company-card.scss
│       │   │   └── _index.scss
│       │   ├── coworkers/
│       │   ├── _badges.scss
│       │   ├── _logo.scss
│       │   ├── _menu.scss
│       │   ├── _menu-btn.scss
│       │   ├── _notification.scss
│       │   ├── _notification-btn.scss
│       │   ├── _reports.scss
│       │   ├── _search.scss
│       │   ├── _tasks.scss
│       │   ├── _welcome.scss
│       │   └── _index.scss
│       │
│       ├── layout/
│       │   ├── _companies.scss
│       │   ├── _header.scss
│       │   ├── _main.scss
│       │   ├── _page.scss
│       │   ├── _sidebar.scss
│       │   └── _index.scss
│       │
│       ├── utils/
│       │   ├── _functions.scss
│       │   ├── _mixins.scss
│       │   ├── _placeholders.scss
│       │   └── _variables.scss
│       │
│       └── main.scss
│
├── companies.html
├── index.html
├── package.json
├── postcss.config.cjs
├── vite.config.js
└── README.md

## SCSS Architecture

The SCSS code is organized into several layers:

- `base/` — global styles, font declarations, reset styles, and utility classes
- `utils/` — variables, functions, mixins, and placeholders
- `components/` — reusable UI components such as buttons, menu, search, reports, tasks, company cards, and coworker components
- `layout/` — page-level layout blocks such as header, sidebar, main content, and companies page layout

## What I Practiced

During this project, I practiced:

- SCSS file organization
- Using `@use`
- Creating and using variables
- Creating SCSS functions and mixins
- Using placeholders with `@extend`
- Building reusable button components
- Creating responsive layouts with CSS Grid and Flexbox
- Working with SVG sprites
- Styling SVG icons with `fill`, `stroke`, and `currentColor`
- Creating separate HTML pages without page-switching JavaScript
- Structuring a project with Vite

## Getting Started

Install dependencies:

```bash
npm install

Run the project locally: npm run dev
