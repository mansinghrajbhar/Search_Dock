# Search Dock

Search multiple websites from one dashboard.

## Features
- Multi-source search from one query
- Live results from Wikipedia, Apple Movies, Open Library, TVMaze, Stack Overflow and Hacker News
- Native search links for Google, YouTube, IMDb, Facebook, Instagram and Reddit
- Enable/disable sources
- Add custom search sources with a `{query}` placeholder
- Search history stored locally
- PWA/offline shell
- Responsive dark/light interface

## How it works
Search Dock runs in the browser. Public APIs are queried directly where supported. Sites that do not expose a browser-friendly public API are opened using their native search URL.

No backend or database is required for the current version.

## Custom source
Use a search URL containing `{query}`, for example:

`https://example.com/search?q={query}`

## Development
Open `index.html` in a browser or serve the repository with a static web server.

GitHub Pages deployment is configured in `.github/workflows/pages.yml`.
