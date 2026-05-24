# Exponent

Landing page for Exponent — embedded marketing pod by Emma Joelle + LDF.

## Stack

A single `index.html` file. HTML, CSS, and one tiny inline script (~30 lines) that makes the hero aura follow the cursor. Zero dependencies, zero build step. All copy, layout, and styling live in that one file — edit it and refresh.

## Edit

Open `index.html` in any editor. Sections are labeled with comment dividers (`────── HERO ──────`, `────── SERVICES ──────`, etc.). The design system lives in the `:root` CSS variables at the top of the `<style>` block:

| Variable      | Purpose                |
| ------------- | ---------------------- |
| `--indigo`    | Page background        |
| `--cream`     | Text / foreground      |
| `--glow`      | Hero radial glow color |
| `--serif`     | Display type           |
| `--mono`      | UI / labels            |
| `--sans`      | Body copy              |

## Run locally

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

Hosted on GitHub Pages: <https://ilovethedev.github.io/exponent-site/>.
Any push to `main` redeploys automatically.
