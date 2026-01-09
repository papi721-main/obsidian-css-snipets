# Obsidian Snippets

Custom CSS snippets used in this vault. They target the AnuPpuccin theme (and Catppuccin palettes), typography for Amharic-friendly reading, and a textured background option. Drop this folder in `.obsidian/snippets/` and enable the ones you want in Settings → Appearance → CSS snippets.

## Contents

- `general.css` — Shared tweaks: centered/left/right images, smaller nav font, and Noto Sans Ethiopic as the primary note font.
- `headings.css` — Heading/title font swap to Faculty Glyphic in both edit and reading views; sets inline title font.
- `text_colors.css` — Color-coded headings and emphasis for light/dark modes (H1–H6, bold, italic) plus body text tone.
- `extended-colorschemes.css` — Massive Catppuccin/AnuPpuccin palette extensions with Style Settings toggles for many light/dark flavors and an AMOLED variant.
- `cracked_wall_background.css` — Adds a fixed, vignetted background image with a blue tint overlay across core panes.
- `pdf_export_settings.css` — Print-specific tweaks to avoid orphaned/widowed lines and prevent headings from breaking across pages.
- `prism_theme_settings.css` — Refined callout styling (borders, padding, tinted backgrounds) respecting callout color tokens.
- `archived_snippets/` — Older iterations kept for reference.
- `style-settings/AnuPpuccin.json` — Exported Style Settings config for the AnuPpuccin theme.

## Prerequisites

- Obsidian 1.5+ (earlier versions untested)
- AnuPpuccin theme enabled
- Style Settings plugin (needed to expose the extended palette toggles)
- Fonts: Noto Sans Ethiopic (for body), Faculty Glyphic (for headings/inline titles). Install at the OS level for best results.

## Quick start

1) Copy this folder into your vault at `.obsidian/snippets/`.
2) In Obsidian, go to Settings → Appearance → CSS snippets and toggle on the files you want.
3) If using `extended-colorschemes.css`, open Style Settings (command palette or ribbon icon) and pick your Catppuccin flavor:
   - Toggle `anp-theme-ext-light` / `anp-theme-ext-dark` for the extensions.
   - Choose a light flavor (`catppuccin-theme-extended`) and a dark flavor (`catppuccin-theme-dark-extended`).
   - Enable `anp-theme-ext-amoled` for deep blacks.
4) For the textured look, enable `cracked_wall_background.css`. Adjust `--global-bg-image` or tint variables at the top of the file if you want a different backdrop.

## Notes

- The snippets are independent; mix and match as needed.
- Printing: keep `pdf_export_settings.css` on if you export/print frequently.
- To edit accent colors or typography, open the corresponding file and tweak the CSS variables near the top.
