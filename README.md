# Vite Vanilla JS Project

A simple Vanilla JavaScript project setup using [Vite](https://vitejs.dev/), a fast build tool that provides instant server start and lightning-fast HMR (Hot Module Replacement).

## Features

- ⚡ Blazing fast development with Vite
- 📂 Organized project structure
- 🎯 ES Modules support
- 🎨 CSS and assets handling
- 🧪 Ready for unit testing
- 🚀 Easy deployment

## Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v16 or later recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/lelongrvp/wedding-site.git
   cd wedding-site
   ```

2. Install dependencies:
   ```sh
   npm install
   ```
   or
   ```sh
   yarn install
   ```

## Development

Start the development server:

```sh
npm run dev
```

or

```sh
yarn dev
```

Vite will start a local development server at `http://localhost:5173/` (default).

## Build for Production

To build the project for production:

```sh
npm run build
```

or

```sh
yarn build
```

The production-ready files will be available in the `dist` folder.

## Preview Production Build

After building, preview the production build locally:

```sh
npm run preview
```

or

```sh
yarn preview
```

## Project Structure

```
├── public          # Static assets (index.html, images, etc.)
├── src             # Source files
│   ├── assets      # Static files (CSS, images, etc.)
│   ├── js          # JavaScript files
│   ├── main.js     # Entry point
│   └── styles.css  # Main stylesheet
├── .gitignore      # Files to ignore in Git
├── index.html      # Main HTML file
├── package.json    # Project metadata and dependencies
├── vite.config.js  # Vite configuration file
└── README.md       # Project documentation
```

## Configuration

Vite can be configured via the `vite.config.js` file. Modify this file according to your project needs.

## Useful Commands

- `npm run dev` – Start the development server
- `npm run build` – Build the project for production
- `npm run preview` – Preview the production build

## Deployment

Once built, the `dist` folder can be deployed to any static hosting service such as:

- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [GitHub Pages](https://pages.github.com/)
- [Firebase Hosting](https://firebase.google.com/docs/hosting)
