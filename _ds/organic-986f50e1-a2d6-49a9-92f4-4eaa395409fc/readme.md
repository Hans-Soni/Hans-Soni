# Design System (DS)

This folder contains the shared design-system assets for the portfolio website. It defines the visual language used across the site: colors, type, spacing, elevation, buttons, cards, form controls, and other reusable styled patterns.

## Files

- `styles.css` — the main design token file and component stylesheet. It includes the base theme, CSS variables, typography, spacing system, and reusable UI classes.
- `_ds_bundle.js` — the generated bundle that wires the design-system components used by the page.
- `_ds_manifest.json` — metadata describing the design-system sections, stories, and examples.
- `_adherence.oxlintrc.json` — linting and adherence configuration for the DS assets.

## Purpose

The DS folder acts as the visual foundation for the portfolio. Instead of scattering styles across the page, the site reuses a consistent set of tokens and component patterns so the interface feels cohesive and themeable.

## Main theme decisions

- Warm neutral background with earthy accent colors
- Serif heading style paired with a clean sans-serif body font
- Structured spacing scale and rounded corners
- Soft shadow system for depth and layering
- Consistent button, card, tag, and form styles

## How it is used

The portfolio loads the design system from the main page:

```html
<link rel="stylesheet" href="ds/styles.css">
<script src="ds/_ds_bundle.js"></script>
```

This keeps the styling centralized and makes it easier to update the entire visual identity in one place.

## Notes

The styles are intentionally lightweight and framework-free: plain CSS, semantic HTML, and reusable classes. This makes the design system easy to maintain and easy to extend for future sections or portfolio updates.
