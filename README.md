# Exponent

Landing page for Exponent — embedded marketing pod by Emma Joelle + LDF.

## Stack

A single `index.html` plus a sibling `tweaks-panel.jsx` it loads via `<script type="text/babel">`. React and Babel are pulled from unpkg at runtime — there is no build step, no bundler, and no local dependencies to install.

## Run locally

Serve the folder with any static file server, for example:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

Hosted on GitHub Pages: <https://ilovethedev.github.io/exponent-site/>
