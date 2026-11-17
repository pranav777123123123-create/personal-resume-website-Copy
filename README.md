# Personal Resume Website — CSS Midterm Update

This is the CSS-enhanced version of the existing HTML resume website. It is intended to replace the `index.html` file in the **same GitHub repository** as the original HTML baseline, with `styles.css` added alongside it.

## Files

- `index.html` — updated semantic HTML page linked to a separate stylesheet
- `styles.css` — all styling for font, layout, color, selectors, responsive design and interactions
- `assets/pranav-portrait.jpg` — existing photograph, unchanged from the original site

## What changed from the original HTML-only version

1. Linked an external stylesheet using `<link rel="stylesheet" href="styles.css">`.
2. Applied an intentional consistent color palette (ink, teal, mint, off-white) using CSS custom properties in `:root`.
3. Added type hierarchy with Outfit for headings and DM Sans for body text, with system-font fallbacks.
4. Organized navigation using Flexbox and kept the header visible with `position: sticky`.
5. Used CSS Grid for the hero, education, projects, skills, and contact layouts.
6. Styled semantic `<article>` items as cards and formatted the existing actual `<table>` as a readable skills table.
7. Improved alignment, margins, padding, borders, radii, line-height and responsive whitespace.
8. Demonstrated element (`body`, `h2`, `a`), class (`.card`, `.main-nav`) and ID (`#skills`, `#contact` via attribute selectors and anchors) selectors, hover and focus states, pseudo-elements and media queries.
9. Added mobile layouts with `@media` breakpoints and accessible keyboard focus and reduced-motion support.
10. Preserved the existing resume facts, personal portrait, email, LinkedIn and major content sections.

## Deploy to the SAME GitHub Pages site

Repository: https://github.com/pranav777123123123-create/personal-resume-website-Copy
Site: https://pranav777123123123-create.github.io/personal-resume-website-Copy/

1. In your existing GitHub repository, choose **Add file → Upload files**.
2. Upload the updated `index.html` and new `styles.css` to the **repository root**.
3. If GitHub's web uploader refuses a duplicate filename, replace the content of `index.html` using its pencil **Edit this file** control and commit the change, then upload `styles.css` separately.
4. Do not delete `assets/pranav-portrait.jpg`, or add an extra enclosing folder.
5. Commit with a message such as **Style resume website with CSS for midterm**.
6. Keep the same Pages settings (Deploy from branch → main → /(root)). Visit the same site link and refresh after deployment.
7. Confirm the picture loads, desktop and mobile layouts work, and navigation/LinkedIn/email links are clickable.

## Academic transparency

The initial HTML-only version was reconstructed after the earlier HTML module and published as a baseline. The second GitHub commit is the CSS-enhanced midterm update. The PDF report describes the actual changes in these files; review the implementation so you can explain the techniques in your own words.
