# Changelog

## 4.3.0 — 2026-10-21

- Gave bordered Dark Modern 2026 a darker outer frame, sidebar, and matching status bar so the bottom inset blends into the surrounding workspace. Connected the tab strip to the editor, improved sidebar text and icon contrast, and coordinated neutral selection and active-tab backgrounds in both variants; Unbordered retains blended surfaces.
- Removed italics from syntax, Markdown emphasis, and semantic highlighting across all 22 themes, preserving other text styles.

## 4.2.0 — 2026-10-21

- Replaced matching-word outlines with palette-matched background highlights across all 22 themes, covering selections and read, write, and textual occurrences. Single-click symbol highlights use stronger fills to keep matching references easy to spot.
- Softened workspace dividers and modern UI editor, panel, and activity bar frames in Bordered variants. Made those borders transparent in Unbordered variants for a seamless appearance in both classic and modern UI.

## 4.1.0 — 2026-10-19

- Removed the active-tab accent borders in both Dark Modern 2026 and Poimandres variants so classic VS Code tabs use background highlighting consistently with the other themes.
- Gave Dark Modern 2026 active tabs a distinct background using the palette's existing selected-tab color.

## 4.0.0 — 2026-10-19

- Refreshed all 22 theme screenshots, named them by palette and border style, and ordered the README gallery alphabetically.
- Added Xcode 26 Dark and Xcode 26 Dark Unbordered, inspired by Xcode 26 with cooler charcoal surfaces, soft pink/coral syntax, pale mint references, cyan declarations, and lavender library symbols. Includes Swift scope refinements, readable comments, shared editor/terminal backgrounds, white cursors, and familiar Git colors. The pack includes 22 themes across eleven palettes.
- Refined both Graphite variants with a deeper blue-gray editor/terminal surface (`#282c34`), softer body text, subtly brighter bold declarations, and quieter strings, punctuation, comments, and surrounding UI. Softened keyword weight and type italics, and removed blanket bold styling from function calls and readonly names, retaining grayscale syntax, white cursors, familiar status colors, and both border styles.
- Added Rosé Pine Neutral and Rosé Pine Neutral Unbordered with the original palette’s softer rose and pine hues, the same neutral charcoal surfaces as Moon Neutral, and Vine’s readability and status-color conventions.
- Added Rosé Pine Moon Neutral and Rosé Pine Moon Neutral Unbordered: Moon-inspired syntax on neutral charcoal surfaces, with lifted pine and comments, white cursors, familiar Git colors, and matching editor/terminal backgrounds.
- Refined both Sublime Text 4 variants against the bundled Mariana scheme: distinguished TypeScript function/method calls from definitions in TextMate highlighting, added semantic definition modifiers, and restored decorator, mapping-key, and markup details. Gently brightened blue-gray editor and terminal surfaces to `#202832`, preserving white cursors, familiar Git colors, and both border styles.
- Brightened both Tokyo Night variants to a blue-violet editor and terminal background (`#1a1b26`), with coordinated sidebar, widget, hover, and guide colors. Preserved the syntax palette, quiet UI text, white cursors, Git colors, and bordered/unbordered styling.
- Brightened both Firefox DevTools variants to Firefox’s charcoal editor and terminal surface (`#232327`), with lighter widgets, selections, and supporting surfaces. Matched comments, properties, parameters, and operators more closely to the Firefox palette while retaining Vine’s quiet UI, white cursors, familiar Git colors, and bordered/unbordered styling.

## 3.0.0 — 2026-10-18

- Refreshed and renamed all 16 theme screenshots for the Marketplace listing.
- Lifted both Chrome DevTools variants toward lighter charcoal surfaces, with editor and terminal backgrounds of `#1c1c1c`, slightly brighter supporting UI text, and unchanged syntax colors.
- Replaced b&w and b&w Unbordered with Graphite and Graphite Unbordered: Chrome-inspired blue-gray editor and terminal backgrounds (`#363c46`), soft-white code text (`#f0f0f0`), readable secondary text, and balanced selections and guides. Monochrome syntax styles, familiar Git colors, and pure-white cursors are retained.
- Softened navigation text, toolbar icons, panel borders, and Explorer selections across all themes so the surrounding UI is quieter than the code. Syntax colors, code and terminal text, white cursors, keyboard focus indicators, and Git colors are preserved.
- Made the original-side diff gutter background transparent across all themes so inline additions do not get a misleading red spacer. Added-line shading stays green, and actual deletions retain their red line and text highlights.
- Removed two legacy palette pairs and their theme definitions, screenshots, and current-pack references.
- Added Vine: Poimandres and Vine: Poimandres Unbordered, bringing the current pack to 16 themes across eight palettes. These retain Poimandres' navy, mint, and pale-blue character with opaque comments and types, clearer selections, white cursors, and consistent TextMate and semantic syntax roles.
- Matched the Sublime Text 4 Dark bordered title bar to the dark surrounding surface.
- Removed the broad readonly semantic color override in both Sublime variants so `const` variable names stay light gray and remain distinct from purple keywords.
- Muted editor and Explorer indent guides across the pack, with slightly brighter active guides. Graphite uses blue-gray guides suited to its lighter background.

## 2.0.0

A visual refresh focused on reducing the faded appearance of several palettes, improving syntax separation, and making cursors easier to find.

### Contrast and readability

- Deepened backgrounds and refined contrast in the existing palettes, including Tokyo Night, Chrome DevTools, Sublime Text 4 Dark, Firefox DevTools, and b&w, including both bordered and unbordered variants.
- Enriched syntax colors in the affected color palettes while preserving each theme's character.
- Gave properties and parameters distinct colors in several palettes, including Tokyo Night, Chrome DevTools, and Firefox DevTools, with matching TextMate and semantic token rules.
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

### Shared design

- Consistent workspace styling across the pack, with subtle dividers in bordered themes and blended surfaces in unbordered themes.
- Matching editor and terminal backgrounds.
- TextMate syntax highlighting and semantic token colors, with grayscale syntax and typographic distinctions in b&w.
- Familiar source control colors: yellow for modified files, green for added or untracked files, and red for deleted or conflicting files.
- Green, blue, and red editor gutter indicators for added, modified, and deleted lines, respectively.
- Theme-specific cursor colors, later standardized to white in v2.
- Screenshots, palette credits, and documented design principles.
