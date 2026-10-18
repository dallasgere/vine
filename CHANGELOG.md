# Changelog

## 2.0.0

A visual refresh focused on reducing the faded appearance of several palettes, improving syntax separation, and making cursors easier to find.

### Contrast and readability

- Deepened backgrounds and refined contrast in Sea Glass, Tokyo Night, Chrome DevTools, Sublime Text 4 Dark, Firefox DevTools, Rosé Pine Neutral, and b&w, including both bordered and unbordered variants.
- Enriched syntax colors in the affected color palettes while preserving each theme's character.
- Gave properties and parameters distinct colors in Sea Glass, Tokyo Night, Chrome DevTools, Firefox DevTools, and Rosé Pine Neutral, with matching TextMate and semantic token rules.
- Made comments, inactive tabs, line numbers, and other secondary details quieter so active content stands out more clearly.
- Refined selection and current-line backgrounds alongside the deeper editor surfaces.
- Kept editor, terminal, and gutter backgrounds matched, and kept syntax colors consistent between each theme's two variants.
- Preserved the Dark Modern 2026 and GitHub Dark Default palettes, apart from the cursor update below.

### b&w

- Introduced deeper grayscale backgrounds, with an editor background of `#0e0e0e`.
- Tuned the main text to a soft `#d0d0d0`, keeping it bright and readable without using pure white throughout the editor.
- Kept comments quieter and retained typography to distinguish syntax roles.

### Sublime Text 4 Dark

- Preserved the bordered theme's Sublime-style gray title bar (`#2e3238`).
- Blended the strip above the status bar into the dark surrounding surface while keeping the gray title bar.

### Cursors and design guidance

- Set editor and terminal cursors to bright white (`#FFFFFF`) in all 18 themes, including Dark Modern 2026 and GitHub Dark Default.
- Expanded the design principles to cover visual hierarchy, syntax contrast, and consistent cursor visibility.
- Checked explicit syntax foregrounds in the seven refreshed theme pairs for at least 4.5:1 contrast against their editor backgrounds and at least 3:1 against their selection backgrounds.

## 1.0.0

Initial release of Vine Theme Pack: nine dark palettes, each available in bordered and unbordered variants, for 18 themes total.

### Included palettes

- Sea Glass
- Dark Modern 2026
- Tokyo Night
- Chrome DevTools
- Sublime Text 4 Dark
- Firefox DevTools
- Rosé Pine Neutral
- GitHub Dark Default
- b&w

### Shared design

- Consistent workspace styling across the pack, with subtle dividers in bordered themes and blended surfaces in unbordered themes.
- Matching editor and terminal backgrounds.
- TextMate syntax highlighting and semantic token colors, with grayscale syntax and typographic distinctions in b&w.
- Familiar source control colors: yellow for modified files, green for added or untracked files, and red for deleted or conflicting files.
- Green, blue, and red editor gutter indicators for added, modified, and deleted lines, respectively.
- Theme-specific cursor colors, later standardized to white in v2.
- Screenshots, palette credits, and documented design principles.
