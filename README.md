# ToolsRhino

Static website for **ToolsRhino** — a collection of free online tools (landing pages like `index.html`, `about.html`, `contact.html`, `privacy.html`, plus tool pages under `tools/`).

## Run locally (preview)

Because this is a static site, you can open `index.html` directly in a browser. For best results (so relative paths behave consistently), run a small local server.

### Option A: VS Code / Cursor Live Server

1. Install the **Live Server** extension.
2. Right-click `index.html` → **Open with Live Server**.

### Option B: Python

From the project folder:

```bash
python -m http.server 5173
```

Then open:

- `http://localhost:5173/index.html`

### Option C: Node (http-server)

```bash
npx http-server -p 5173
```

## Structure

- `index.html`: Home / tools listing
- `about.html`: About page
- `contact.html`: Contact page
- `privacy.html`: Privacy policy
- `tools/`: Individual tool pages

## Notes

- The site is designed to be **responsive** on mobile, tablet, and desktop.
- Analytics: Google Analytics tag is included on pages.

