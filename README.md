# Personal Resume Website — CSS Midterm (Typography Update)

This is a revised CSS version of the **same personal resume website** used for the HTML module. It uses the existing resume facts and photograph but is deliberately styled like an understated personal resume rather than a marketing landing page.

## Files

- `index.html`: semantic resume content and working navigation
- `styles.css`: responsive styles, colours, typography and layouts
- `assets/pranav-portrait.jpg`: original photograph, retained unchanged

## Main CSS improvements

- Styled the page with a consistent off-white, navy-blue and charcoal colour palette.
- Used **Fraunces** for headings and **Manrope** for body text with consistent typography and spacing.
- Applied **Flexbox** to navigation and **CSS Grid** to the introduction, project layout and contact area.
- Applied class selectors, element selectors, ID anchors, hover and keyboard-focus states.
- Used a sticky navigation header, layout alignment, borders and responsive media queries.
- Used a neat portrait photo presentation and improved the formatting of the real skills table.

## Contact links

The previous "Email me" link used a `mailto:` address. That depends on having a mail application or browser mail handler configured; some computers do nothing when it is clicked. The revised site **shows the actual email address** and offers **Compose in Gmail**, which opens Gmail's web compose screen in a new tab (sign-in may be required). The email address is also a `mailto:` link for visitors who prefer an email app.

## Updating the original GitHub repository

1. Keep using your existing repository: `personal-resume-website-Copy`.
2. Upload the updated `index.html` and `styles.css` to the repository root on the `main` branch. You can upload `README.md` as well, if you want the repository documentation updated.
3. **Do not delete the existing `assets` folder.** The unchanged photo is already there.
4. Commit with a message such as `Refine CSS design and improve contact links`.
5. GitHub Pages will publish the updated version at the same website URL. After publishing, refresh with Ctrl+Shift+R.

Existing site: https://pranav777123123123-create.github.io/personal-resume-website-Copy/

The HTML-only version remains in earlier commits. The newer typography uses Google Fonts, and a locally installed fallback is specified if the fonts are unavailable. Use the latest, revised one-page PDF write-up for your midterm submission because it describes this particular CSS version.
