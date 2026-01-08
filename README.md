# GitHub Node

Simple Express server that responds with a random superhero name on the root route. Uses the `superheroes` package to generate the name. Using git to save the project in GitHub and use of gitignore.

## Prerequisites
- Node.js 18+ recommended
- npm

## Setup
1. Install dependencies:
   ```bash
   npm install
   ```

## Run
Start the server:
```bash
node index1.js
```
The app listens on `http://localhost:3000/` by default.

## Endpoint
- `GET /` — returns HTML with a random superhero name, e.g. `<h1>Behold, I am Spider-Man!</h1>`.

## Project Notes
- Entry point: `index1.js`
- Dependencies: `express`, `superheroes`
