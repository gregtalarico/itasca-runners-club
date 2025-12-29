# Itasca Runners Club

A website for the Itasca Runners Club, a social group with a running problem!

## Overview

This project is a static site built using [Eleventy (11ty)](https://www.11ty.dev/). It provides information about the club, running schedules (Saturday and Weekday runs), and the annual Itasca Oktoberfast 5K.

## Tech Stack

*   **Static Site Generator**: [Eleventy](https://www.11ty.dev/)
*   **Templating**: Nunjucks (`.njk`) and Markdown (`.md`)
*   **Deployment**: Netlify (configured with `data-netlify="true"` for forms)

## Getting Started

### Prerequisites

*   [Node.js](https://nodejs.org/) (installed on your machine)
*   npm (comes with Node.js)

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    cd itasca-runners-club
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

### Running Locally

To start the development server with live reload:

```bash
npm start
```

This will run `eleventy --serve`. You can view the site at `http://localhost:8080`.

### Building for Production

To build the static files for production (outputs to `_site/`):

```bash
npm run build
```

## Project Structure

*   `_includes/`: HTML layouts and partials (e.g., `base.njk`).
*   `assets/`: Images, CSS, and other static assets.
*   `_site/`: The generated static site (created after build).
*   `eleventy.config.js`: Configuration file for Eleventy.
*   `index.md`: The main homepage content.

