# MERN CRUD

A CRUD interface for user records, built as the front end of a MERN-style stack: a React and Vite app that talks to an Express/Mongo API over HTTP.

## Features

- **Add** a record (`src/components/Add.jsx`)
- **Fetch and list** records (`src/components/Fetch.jsx`)
- **Update** an existing record (`src/components/Update.jsx`)
- Routing between views with **react-router-dom**
- Feedback via **SweetAlert2** dialogs

## Stack

React 18 · Vite · Tailwind CSS · axios · react-router-dom · SweetAlert2

## Getting started

```bash
npm install
npm run dev
```

Vite serves the app on `http://localhost:5173`. `npm run build` produces a production bundle.

## Talking to the API

All requests go through `src/api.js`, which holds the base URL and the axios calls. Point it at your API before running the UI — the Express/Mongo service is a separate repo, so this one won't work on its own.

## Notes

The repo name reflects the stack it was built as part of; only the client is committed here. Default Vite scaffolding has been replaced with the CRUD UI, and the Tailwind config lives in `tailwind.config.js`.
