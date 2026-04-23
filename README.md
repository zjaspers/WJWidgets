# WorkJam GitHub Widget Refactor

This folder contains:
- `styles.css` — shared WorkJam design system stylesheet
- refactored HTML widgets — each links to `styles.css`

## GitHub usage
Upload these files into the same directory in your repo.
Each widget already references:

```html
<link rel="stylesheet" href="styles.css">
```

If your HTML files live in a subfolder, keep `styles.css` in that same folder or update the relative path.
