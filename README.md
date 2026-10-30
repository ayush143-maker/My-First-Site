# My-First-Site

My-First-Site is a beginner-friendly website created while learning HTML and CSS. It is a single HTML page with embedded styling and markup.

## Page contents

The page has About Me, My First Project, What I Learned, and Contact sections. Its navigation links jump to those sections using in-page anchors. The project section includes an inline SVG smiley-face drawing. The Contact section has a button that displays an alert explaining that it does not actually do anything yet. The supplied page uses no framework imports.

## Preview locally

No package installation is needed. Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Personalize the page

Edit the section text, colors, spacing, and section order in `index.html`. The page title is “My First Website”; update it there if you want the browser title to match your changes. Markup and styling are embedded in the HTML, and the listed root files include no separate image or stylesheet files. Inspect the existing presentation before adding assets or moving styles.

If you add local files, use paths relative to `index.html` and keep references aligned with the files. Review the About Me and Contact content before publishing: this page has no server-side environment for secrets, and personal details in browser-delivered files may be visible to visitors.

## Review

Check all four sections, in-page links, and the Contact button after changes. Review the page at narrow and wide viewport sizes. No package scripts or deployment configuration are documented.