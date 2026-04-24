# Web App

## Overview
A simple Node.js/Express web application serving a static frontend on port 5000.

## Tech Stack
- **Runtime**: Node.js 20
- **Framework**: Express.js
- **Frontend**: Static HTML/CSS (in `public/` directory)

## Project Structure
- `server.js` - Express server entry point (serves on 0.0.0.0:5000)
- `public/index.html` - Main frontend page
- `package.json` - Node.js dependencies

## Running the App
The app runs via the "Start application" workflow:
```
node server.js
```

## Deployment
Configured for autoscale deployment running `node server.js`.
