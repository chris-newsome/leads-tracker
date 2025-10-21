# Leads Tracker

Simple Chrome extension that lets you save interesting links while browsing and revisit them later. Built as part of the Scrimba Frontend Developer Career Path to practice DOM manipulation, local storage, and browser extension fundamentals.

## Features
- Add the current browser tab or enter any URL manually to store it for later.
- Persist saved leads using `localStorage`, so they remain after refreshing.
- Render the saved list dynamically and remove entries when you clear the tracker.

## Tech Stack
- Vanilla JavaScript for UI and state management.
- HTML/CSS for layout and styling.
- Vite for bundling and local development.

## Getting Started
Install dependencies and start the dev server:
```
npm install
npm start
```

## Useful Commands
- `npm run build` to produce a production bundle.
- `npm run preview` to serve the production build locally.

## Project Structure
- `index.html` – extension popup markup.
- `index.js` – main logic for capturing, storing, and rendering leads.
- `index.css` – popup styling.
