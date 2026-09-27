# website — progress log

## 2026-09-27

- replaced headshot with new photo (tower of london, square crop); old headshot archived to `assets/archived/headshot_2026_09_27.jpg`, uncropped original at `assets/archived/img_2144_original_2026_09_27.jpg`
- added photo grid to sidebar: 15 photos, 3 per row, 180px wide, under contact info with 260px top margin on desktop (20px on mobile); click opens lightbox with prev/next arrows, click-image-to-advance, swipe on mobile, arrow keys, esc/× to close
- stylesheet link is cache-busted (`style.css?v=4`); bump the version on every css change or browsers show stale styles
- photo files: `assets/photos/thumbs/` (320px) and `assets/photos/full/` (1600px); originals in `assets/photos/originals/` (gitignored)
- files changed: `index.html`, `style.css`, `.gitignore`
- status: all pushed to main and live

## 2026-04-07

- decided to create a personal academic website hosted via github pages
- reference site: https://noahdasanaike.github.io/ — minimal single-page layout, two-column (photo/bio on left, content on right), plain html/css, no framework
- plan: scaffold a similar site with plain html/css, deploy on github pages as `username.github.io`
- status: waiting on github username, headshot, bio content, and desired sections before building
