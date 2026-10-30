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

## Browser and platform reliability review checklist

This is a checklist for a future review, not a record of completed testing or verified results.

- Review the page in current desktop browsers relevant to your audience and on mobile browsers such as Safari on iOS and Chrome on Android where applicable. Choose target browsers and versions based on intended visitors; no compatibility results are recorded here.
- Open developer tools and inspect the console and network panel while loading the page and trying its links or other interactions. Look for runtime errors, failed requests, and resources that do not load.
- Inspect `index.html` for local asset and external font or script references. The listed root files have no separate asset files, but check the HTML itself; if you add assets, confirm every path resolves locally and on the host. Check capitalization and directory names in hosted paths.
- Compare a narrow mobile-sized viewport with a wide desktop-sized viewport. Check that the four sections and their content remain readable and usable, and review on actual mobile hardware where practical.

## Manual review checklist

These are review steps, not verified results.

- Open the root `index.html` or use the local preview steps above. Review the About Me, First Project, What I Learned, and Contact sections.
- Try links or other interactions present on the page and check their destinations or responses.
- After changing colors, content, or layout, repeat the browser, network, and viewport review.

## Accessibility review checklist

These are future review checks, not verified accessibility results.

- Use Tab and Shift+Tab to check keyboard access, logical focus order, and visible focus indicators for links and other interactive elements.
- Review links and controls for meaningful names that make destinations or actions clear. If you add images, provide useful alternative text for informative images and treat decorative images accordingly.
- Check text and link contrast against the page background and readability at narrow viewports.
- If you add animated or moving effects, check behavior with the operating system's reduced-motion preference enabled.