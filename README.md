# Satyam Kumar Mishra — Personal Portfolio

A responsive HTML5 and CSS3 portfolio prepared for the HTML & CSS internship brief. No JavaScript, frameworks, backend, database, build tools, or external fonts are used. Open `index.html` in a browser to use the site offline; email and external profiles require an appropriate mail application or internet connection.

## Files

- `index.html` — semantic page structure and personalised content.
- `style.css` — colour variables, Grid/Flexbox, responsive breakpoints, interaction states, and CSS-only motion.
- `images/` — two supplied photographs, resized/compressed without AI editing, plus an original SVG favicon.
- `screenshots/desktop.png` and `screenshots/mobile.png` — full-page browser screenshots.
- `PROJECT_DESCRIPTION.txt` — five-sentence description for the submission form.
- `TEST_REPORT.md` — recorded browser checks and limits.
- `GITHUB_PAGES_GUIDE.md` — free hosting and submission instructions.

## Content and project status

Personal and contact details were supplied by Satyam. The portfolio is the implemented project. The Python and AI/ML projects are **planned**, as confirmed by Satyam; no results or specific repositories are claimed. The GitHub link goes to the supplied profile/repository listing, not an invented project repository. Update planned cards only after doing the work. The guide requires at least two cards but does not explicitly say whether planned projects qualify; the safest way to strengthen the submission is to build a small Python project and replace its planned status with accurate details. Do not describe planned work as completed in the submission.

## Understand and customise the code

1. The header contains navigation anchors, such as `href="#skills"`, matched by section IDs.
2. `<main>` contains the five content sections; `<article>` groups each project and skill card.
3. The stylesheet starts with reusable custom properties in `:root`. Change `--blue`, `--accent`, and `--bg` to adjust the theme.
4. `.hero`, `.about-grid`, `.skills-grid`, `.projects-grid`, and `.contact-grid` use CSS Grid. Buttons and navigation use Flexbox.
5. Media queries at 1050, 800, and 600 pixels adapt the layout. The mobile navigation is always visible, so no JavaScript menu is needed.
6. Hover/focus states are defined for links, buttons, and project cards. The `prefers-reduced-motion` query disables decorative motion when requested.
7. The email uses a `mailto:` link rather than a non-functional form. Sending depends on the visitor's mail client.
8. All links are normal HTML anchors. No JavaScript is needed for smooth scrolling; CSS handles it.

### Before you submit

- Review every personal detail and photo. These contact details and images become public if hosted.
- Open the site on your own phone and computer and try the navigation, email, and profile links.
- Read the code and be ready to explain it. Do not claim unaided authorship: an accurate disclosure is, “I supplied the personal content, photographs, and design preferences, and used an AI assistant for code generation, documentation, and testing.” Add your own review/customisations to that statement only once actually performed. Follow any additional internship rules on AI assistance.
- Keep the source files and screenshots together. Do not upload only screenshots.
- Hosting is optional. You can submit the ZIP without waiting for hosting.
- The brief lists 16 October 2026 as the deadline and does not give a closing time. Confirm the form is open; the project has not been submitted automatically.
