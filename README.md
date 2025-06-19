# AI-Terminiology

This demo uses Tailwind CSS classes directly in `index.html`. The compiled
stylesheet `tailwind.css` is included so you don't need an internet connection
to fetch the CDN version.

If you modify the markup and need to regenerate the CSS, install the Tailwind
CLI and build:

```bash
npm install -D tailwindcss-cli
npx tailwindcss-cli -i input.css -o tailwind.css --content index.html -m
```
