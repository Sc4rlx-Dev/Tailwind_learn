Tailwind CSS Learning Project

## Overview
This small project demonstrates how to build fast, responsive UIs with Tailwind CSS.

## Why Tailwind
- Utility-first: compose designs directly in markup
- Speed: fewer context switches between HTML and CSS
- Consistency: shared design tokens and scales
- Responsive out of the box: sm/md/lg/xl utilities
- Tiny builds: purges unused classes for production

Using this project
- Quick try: open index.html in a browser (if using the CDN script)
- Full setup (recommended for real projects):
    1) Install Node.js (LTS)
    2) Install dev deps: npm install -D tailwindcss postcss autoprefixer
    3) Init config: npx tailwindcss init -p
    4) Configure content paths in tailwind.config.js (e.g., ["./*.html", "./src/**/*.{js,ts,jsx,tsx}"])
    5) Add Tailwind directives to your CSS: @tailwind base; @tailwind components; @tailwind utilities;
    6) Build in watch mode: npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
- If package.json defines scripts (dev/build), use npm run dev or npm run build

## Customize
- Add utility classes directly in HTML for spacing, colors, typography, and layout
- Extend theme in tailwind.config.js (colors, spacing, fonts)
- Keep components consistent by extracting class combinations into small templates or components

## Resources
- Docs: https://tailwindcss.com/
- Video overview: https://www.youtube.com/watch?v=6biMWgD6_JY
- Tailwind CSS site: https://tailwindcss.com
- Background image docs: https://tailwindcss.com/docs/background-image
- Installation — Framework guides: https://tailwindcss.com/docs/installation/framework-guides
- Installation — CLI: https://tailwindcss.com/docs/installation/cli
- Installation — PostCSS: https://tailwindcss.com/docs/installation/postcss
- Installation — Play CDN (v4): https://tailwindcss.com/docs/installation/play-cdn
- Installation — Play CDN (v3): https://v3.tailwindcss.com/docs/installation/play-cdn
- Core concepts — Utility-first: https://tailwindcss.com/docs/core-concepts/utility-first
- Showcase: https://tailwindcss.com/showcase
- CDN script (v3.4.17): https://cdn.tailwindcss.com/3.4.17
- Blog — Tailwind CDN UX tips: https://blogs.purecode.ai/tailwind-cdn-how-to-enhance-user-experience-twofold
- Installation — Vite: https://tailwindcss.com/docs/installation/vite
- Cours complet Tailwind CSS v4 2025 – YouTube: https://www.youtube.com/watch?v=XXXX (replace XXXX with the actual video ID)
