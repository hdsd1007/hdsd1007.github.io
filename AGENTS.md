# AGENTS.md - Portfolio Website

## Repository Type
Static personal portfolio website (GitHub Pages). No build system, no tests.

## Structure
- `index.html` - Single-file portfolio (~1200 lines) with embedded CSS/JS
- `*.pdf` - Resume files
- `*.png` - Project screenshots

## Key Files
- `index.html` - Main website (deployable to GitHub Pages)
- `.gitignore` - Contains personal files (LORs, profile photos)

## Developer Commands
None - this is a static HTML site. To view locally:
```bash
# Open index.html in browser, or use a simple server:
python -m http.server 8000
```

## Important Notes
- This is NOT a code project - it's a static portfolio site
- No npm, no build scripts, no CI/CD
- Font: DM Serif Display (titles), DM Mono (mono), Inter (body)
- Theme: Beige/cream background with dark ink text

## Writing Guidelines
If editing content:
- Keep hero tagline concise (< 10 words for main heading)
- Project cards: title, 1-2 sentence description, tech tags, repo link
- Skills use transparent border style (not solid backgrounds)
- Interest tags use transparent style to match skills

## Design Constants
```css
--beige: #f5f0e8       /* Background */
--beige-mid: #ede7d9   /* Tags default */
--ink: #1c1a17         /* Primary text */
--accent: #2d4a3e     /* Links/buttons */
--serif: 'DM Serif Display', serif
--mono: 'DM Mono', monospace
```