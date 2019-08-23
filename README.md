# pages-starter
Unopinionated starter kit for GitHub pages with Showdown and Workbox

Intro
-----

This is a starter kit for generating GitHub Pages websites for project repositories. Markdown from the README.md file can be parsed and placed into an html page inside the `docs` folder. Workbox-build is preconfigured so the site is already setup with a full service worker and will work offline.

Getting Started
---------------

1. Download or clone this repo
2. Run
```
npm install
```
3. Use the template engine of your choice to render the html output within `server.js` to `docs/index.html`
4. Setup GitHub Pages to be served from the `/docs` folder.
