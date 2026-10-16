# Portfolio test report

Test date: 16 October 2026. Browser: automated headless Chromium in the development environment.

## Browser checks completed

| Viewport | No horizontal page overflow | Images load | All 5 navigation links clicked successfully |
|---|---|---|---|
| 1440 × 1000 | Pass | Pass | Pass |
| 1024 × 768 | Pass | Pass | Pass |
| 768 × 1024 | Pass | Pass | Pass |
| 390 × 844 | Pass | Pass | Pass |
| 320 × 740 | Pass | Pass | Pass |

- Each navigation click updated the hash and brought its target section into the viewport.
- All local browser responses observed during these tests were below HTTP 400; no page JavaScript errors were recorded.
- The document contains zero script elements. There are no `.js` files in the submission.
- Keyboard Tab exposed the skip-to-content link; Enter navigated to the main content.
- With reduced motion enabled, computed scroll behaviour was `auto`.
- Four technical skill cards cover Python, HTML, CSS, AI/ML, and C programming. Additional labels include problem-solving and communication, exceeding the minimum of five named skills.
- Three project cards are present: the built portfolio and two explicitly planned learning projects.
- Full-page screenshots captured at 1440px (desktop) and 390px (mobile). Desktop full-page overview and mobile top sections visually reviewed.

## Static source checks completed

- HTML5 doctype, language, UTF-8 character encoding, viewport metadata, title, and separate stylesheet are present.
- Header, nav, main, section, article, and footer elements are present.
- One H1; sections use H2 and cards use H3.
- No duplicate IDs; every internal anchor has a matching element.
- Both photo paths exist and have nonempty alt text. Decorative inline art is hidden from assistive technology.
- External new-tab links use `rel="noopener noreferrer"`.
- CSS variables, Grid/Flexbox, media queries, focus/hover styles, and reduced-motion support are included.

## Limits and remaining user checks

- Not tested on physical devices, Safari, Firefox, screen readers, or by a formal accessibility/HTML validation service. These checks are not an accessibility certification.
- External profile pages and account ownership have not been independently verified. Links use the exact details provided by Satyam.
- Actual email delivery is not tested; `mailto:` requires a configured mail application.
- GitHub Pages deployment has not been performed. Follow the hosting guide and test the published URL after deployment.
- No internship form has been submitted and its current availability has not been checked.
- Planned projects are truthful but may not satisfy an evaluator who expects two implemented projects. The PDF requires two project cards without explicitly clarifying this distinction. Build a small additional project or confirm expectations with the organiser if possible.
