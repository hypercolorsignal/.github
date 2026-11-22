# HyperColorSignal public assets

This directory is the canonical, public-facing asset library for
HyperColorSignal. Use these files when referencing HCS branding or product
imagery from public repositories, websites, social cards, and documentation.

For a stable reference from another project, use the raw GitHub URL form
`https://raw.githubusercontent.com/hypercolorsignal/.github/main/assets/<path>`;
for example, `https://raw.githubusercontent.com/hypercolorsignal/.github/main/assets/brand/marks/wordmark.svg`.

## Brand

### Marks — [`brand/marks/`](brand/marks/)

- `wordmark.svg` — full-color orbit and flare with white HyperColorSignal
  lettering; transparent background, responsive vector master.
- `wordmark.min.svg` — optimized SVG export for production web use.
- `monogram.svg` / `monogram.min.svg` — compact HCS lettering mark on a
  transparent background.
- `circular-icon.svg` / `circular-icon.min.svg` — standalone color symbol on a
  white disc.

### Icons — [`brand/icons/`](brand/icons/)

- `hcs-monogram-dark.png` — square dark-theme organization avatar.
- `hcs-monogram-light.png` — square light-theme organization avatar.
- `favicon-32.png` — 32 × 32 favicon fallback.
- `app-icon-512.png` — 512 × 512 app/store icon.

### Social — [`brand/social/`](brand/social/)

- `open-graph-1200x630.png` — social sharing preview image.

## Product imagery

- [`products/nomi-project-page/`](products/nomi-project-page/) — real Nomi
  Projects screenshots in dark and light themes, with optimized WebP and
  lossless PNG variants. Its README describes dimensions, capture details, and
  suggested alt text.

## Use

- Prefer SVG for responsive web marks; use the minified variants when serving
  the same artwork in production.
- Provide useful alt text when the artwork communicates brand identity; use
  empty alt text when it is purely decorative beside equivalent text.
- Use WebP screenshots for web pages and PNG when lossless pixels are needed.
- Keep the editable master package and QA/history artifacts in the sibling
  `v2/` source directory. This folder is the public distribution surface.
- The Astro website remains a separate project in `website/`; its deployable
  files stay in `website/public/`.
