# My-First-Site

A beginner-friendly website created while learning HTML and CSS. The root `index.html` brings together About Me, First Project, What I Learned, and Contact sections.

## Open the website

No package installation is needed. Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Personalize the page

Edit the section text, colours, spacing, and section order in `index.html`. The page title is “My First Website”; update it there if you want the browser title to match your changes. The listed root files include no separate image or stylesheet files, so review the HTML for the existing presentation before adding assets or moving styles. If you add local files, use paths relative to `index.html` and keep those references aligned with the files.

This static page can also be served by a static host.

## Troubleshooting

Use these as diagnostic checks; they do not indicate known problems.

1. Confirm you opened the root `index.html`, the website’s entry page.
2. If an added image, stylesheet, or other local file does not load, check its reference in `index.html`, confirm the file is present, and preserve the relative path and filename capitalization.
3. Inspect the browser console for errors and the network panel for failed page or resource requests. Check the HTML for external requests separately from local file references; external resources depend on network access, while local resources must be present at their referenced paths.
4. Review the four sections at narrow and wide viewport sizes if content appears difficult to read or use.

## Configuration and personal data

The listed root files contain no `.env.example` or separate configuration file. This static page has no server-side environment in which to keep secrets: anything placed in its HTML or delivered browser files can be viewed by visitors. Do not put passwords, tokens, or other secrets in the page or tracked files.

The page includes About Me and Contact sections. Review their content before publishing, and do not include personal details or contact information you do not intend to make public. Any local assets added to the page are also project content and may be publicly accessible when hosted.

## Review checklist

These are review steps, not verified test results.

- Review the About Me, First Project, What I Learned, and Contact sections at narrow and wide viewport sizes.
- Try links or other interactions present on the page and check their destinations or responses.
- After changing content or layout, repeat the path and browser-console checks above.

## Accessibility review checklist

These are future review checks, not verified accessibility results.

- Use Tab and Shift+Tab to check keyboard access, logical focus order, and visible focus indicators for links and other interactive elements.
- Review links and controls for meaningful names that make destinations or actions clear. If you add images, provide useful alternative text for informative images and treat decorative images accordingly.
- Check text and link contrast against the page background and readability at narrow viewports.
- If you add animated or moving effects, check behavior with the operating system’s reduced-motion preference enabled.