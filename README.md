# WCAG-Compliant Website

A hand-coded, multi-page website built from scratch to practice web accessibility, aiming for WCAG 2.2 Level AA. The content is a fictional community library (Harbor Community Library).

🔗 **Live site:** https://zeynepkeles.github.io/wcag-accessible-website/

**Status:** 🚧 In progress. The site is deployed; the accessibility audit is ongoing.

## Pages
- **Home** (`index.html`): introduction and services
- **Programs** (`programs.html`): weekly schedule in an accessible data table
- **Contact** (`contact.html`): accessible form with inline validation

## Accessibility Features
- Semantic HTML5 landmarks (`header`, `nav`, `main`, `footer`) and a logical heading structure
- "Skip to main content" link
- Keyboard navigation with a visible focus indicator on all interactive elements
- Color palette chosen for WCAG AA contrast (verification results in the audit)
- Accessible form: visible labels, required fields, inline error messages, focus moves to the first error
- Data table with caption and `scope` attributes
- Responsive layout with a keyboard-accessible mobile menu (Esc closes it)
- `prefers-reduced-motion` support
- Page language, descriptive page titles, and `aria-current` for the active page

## Accessibility Audit
Findings, fixes, and test results are documented in [ACCESSIBILITY.md](./ACCESSIBILITY.md).

| Check | Result |
|---|---|
| Lighthouse accessibility score | In progress |
| axe DevTools | In progress |
| WAVE | In progress |
| Keyboard-only test | In progress |
| Screen reader test (VoiceOver) | In progress |

## Built With
HTML5, CSS3, JavaScript (no frameworks or libraries)

## Run Locally
Download or clone the repository and open `index.html` in a browser.

## Roadmap
- [x] Build three-page site with semantic HTML
- [x] Deploy with GitHub Pages
- [ ] Complete the accessibility audit (automated and manual)
- [ ] Fix any issues found and document them
- [ ] Test with additional screen readers

## Author
Zeynep: [GitHub](https://github.com/Zeynepkeles)