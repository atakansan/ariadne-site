# ariadne-site

Public home, privacy policy and terms of service for **Ariadne**, a personal Google Drive organizer that runs on its owner's own computer.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Home: what Ariadne is and is not |
| `privacy.html` | Privacy policy (Google OAuth consent requirement) |
| `terms.html` | Terms of service |
| `style.css` | Shared styles, light and dark color schemes |

## Notes

- Static HTML and CSS only: no JavaScript, no trackers, no build step.
- The current page is marked with `aria-current="page"` in the navigation.
- Respects `prefers-color-scheme` and shows a visible `:focus-visible` outline.
