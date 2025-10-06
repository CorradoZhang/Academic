# Yu Zhang — Academic Homepage

A minimal, responsive academic homepage built with plain HTML/CSS.

## Local preview
```bash
python3 -m http.server 5173 --bind 127.0.0.1
```
Then open `http://127.0.0.1:5173` in your browser. Or simply double‑click `index.html` to open it directly.

## Customize
- Edit `index.html` sections: `education`, `experience`, `projects`, `skills`.
- Adjust colors/spacing in `styles.css` under `:root` variables.
- Update email/phone/links in the header `nav.contact`.

## Deploy (GitHub Pages)
1. Create a new repository and put these files at the repository root.
2. Push to GitHub. In Settings → Pages, set Source to "Deploy from a branch", Branch to `main` and folder `/ (root)`.
3. Wait 1–2 minutes; your site will be live at `https://<username>.github.io/<repo>/`.

## License
MIT

