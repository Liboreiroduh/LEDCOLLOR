# LEDCOLLOR

This project contains static HTML pages for LED training. A small Express server is provided for local development or deployment on platforms like [Render](https://render.com/).

## Local setup

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Open `http://localhost:3000` in your browser.

## Deploying on Render

On Render, create a new **Web Service** and configure the following settings:

- **Build Command:** `npm install`
- **Start Command:** `npm start`

The service will serve the static content defined in this repository.
