# My-First-Site

My-First-Site is a beginner-friendly website created while learning HTML and CSS. The root `index.html` brings together About Me, First Project, What I Learned, and Contact sections.

## Open the website

No package installation is needed. Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Personalize the page

Edit the section text, colors, spacing, and section order in `index.html`. The page title is “My First Website”; update it there if you want the browser title to match your changes. The listed root files include no separate image or stylesheet files, so inspect the existing HTML presentation before adding assets or moving styles.

If you add local files, use paths relative to `index.html` and keep those references aligned with the files. Review the About Me and Contact content before publishing: the static page has no server-side environment for secrets, and personal details in browser-delivered files may be visible to visitors.

## Project files

- `index.html` — page entry point, content, and presentation.
- `README.md` — project documentation.

No package scripts or deployment configuration are documented. When reviewing changes, check all four sections and any links or interactions at narrow and wide viewport sizes.