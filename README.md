# kwjekyll

A reusable Jekyll starter for Kitware-led landing pages with Tailwind CSS 4 and DaisyUI 5.

## Requirements
- Ruby with Bundler
- Node.js 20 or newer

## Setup
```bash
bundle install
npm install
npm run dev
```

For a production build: `npm run build`.

## Editing
- `_data/site.yml`: global branding, navigation, footer and CTA.
- `index.md`: hero and overview content. Only add navigation anchors for sections that exist.
- `_includes/hero.html` and `_includes/overview.html`: reusable homepage sections.
- `_layouts/default.html`: shared HTML shell; `_layouts/home.html`: homepage composition.
- `assets/css/tailwind.css`: Tailwind 4 tokens, DaisyUI 5 theme and reusable utilities.
- `assets/js/navigation.js`: sticky header behavior.
