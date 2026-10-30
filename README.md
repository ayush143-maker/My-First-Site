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

## Asset and loading review checklist

This is a checklist of actions to perform, not a record of verified results.

- Inspect `index.html` for local image, font, audio, stylesheet, or other media references. If you add files, check that every reference resolves from the page and remove assets only after confirming they are not used.
- Keep images and other media sized for their role; avoid retaining unnecessarily large originals or unused copies.
- Review any external font or script references in the HTML and keep them only when they are intentional. Check the page's appearance and readability if an external font is unavailable.
- After moving or renaming local files, update the page references and check that the assets still load.

## Manual review checklist

This is a checklist of actions to perform, not a record of verified results.

- Open the root `index.html` in a browser, or use the local preview steps above. Review the About Me, First Project, What I Learned, and Contact sections.
- Try any links or other interactions present on the page and check that they lead to the intended destination or respond as expected.
- Inspect the page at a narrow mobile-sized viewport and a wide desktop-sized viewport. Check that the sections and their content remain readable and usable.

## Accessibility review checklist

These are future review checks, not verified accessibility results.

- Use Tab and Shift+Tab to review keyboard access to any links or other interactive elements in the four page sections. Check that focus order is logical and that each action is possible without a pointer.
- Check that keyboard focus is clearly visible on each focused link or control.
- Review links and controls for meaningful names that make their destinations or actions clear. If you add images, check whether informative images have useful alternative text and decorative images are treated as decorative.
- Check text and link contrast against the page background, including after changing colours, and review readability at narrow viewports.
- If you add animated or moving effects while editing `index.html`, check their behavior with the operating system's reduced-motion preference enabled.