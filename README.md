# 221st Street Music - Searchable Catalog Prototype

This is a custom, lightweight music catalog prototype built for **221st Street Music**. It features a searchable database of tracks with a centralized "Master Player" to provide a clean, professional user experience.

## Key Features
- **Centralized Master Player**: A single audio interface at the top of the page to prevent UI clutter.
- **Dynamic Search**: Live-filtering of tracks by Title, Writer, or Multiple Collaborators.
- **Genre Filtering**: A dropdown menu to quickly categorize and find tracks by mood or style.
- **JSON-Powered**: The catalog is managed via a simple `songs.json` file, making it easy to update without touching the core HTML/JS code.

## Tech Stack
- **HTML5/CSS3**: Clean, responsive layout.
- **JavaScript (Vanilla)**: For live search logic and dynamic DOM manipulation.
- **JSON**: Used as a lightweight data store for the music catalog.
- **Suno AI**: Source for high-quality, commercially-licensed audio tracks used in this prototype.

## How to Run Locally
Because this project uses the `fetch()` API to load the JSON catalog, it must be run on a local server for the search to function:
1. Open your terminal in the project directory.
2. Run `python -m http.server 8000`.
3. Visit `http://localhost:8000` in your browser.

## Project Credits
- **Developer**: Victor Perez (V.I. Perez)
- **Audio Content**: Generated via Suno AI (The Atelier)

