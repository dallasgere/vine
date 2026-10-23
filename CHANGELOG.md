# Changelog

## 5.0.0 — 2026-10-23

- Added Atom One Dark, JetBrains New UI, and Night Owl, each with Bordered, Unbordered, and Uniform variants. Vine now includes fourteen palettes and 42 themes.
- Added a Uniform variant of every existing palette, combining a single workspace surface color with subtle dividers.
- Refined Atom One Dark syntax with neutral plain code and operators, cyan built-ins, green inherited classes, and separate variable and method rules. Comments and reds are lifted for readability.
- Adapted Night Owl with a muted slate-blue editor (`#1C2332`), coordinated workspace surfaces, readable comments (`#9AA9AC`), and soft mint-green syntax (`#9FD4B0`). Restored language-specific syntax distinctions and matched the original’s TextMate-driven highlighting approach while retaining upright, regular-weight text.
- Lifted comments in the three new palettes and darkened accent buttons and badges for readable text.
- Added a subtle divider under the tab row in Bordered and Uniform variants, with a softer divider in Uniform. Unbordered remains seamless.
- Removed the full-item activity bar highlight from all three Dark Modern 2026 variants so the active icon uses the accent bar.
- Refreshed the README gallery with one new screenshot per palette, aligned screenshot filenames with theme names, and documented all three variants together.

## 4.10.0 — 2026-10-23

- Fixed the VS Code theme validation warnings across all 22 themes: gave `editor.inactiveSelectionBackground` a slight transparency so it no longer obscures content, removed the unsupported `tab.unfocusedInactiveBorderTop` key, and dropped token background colors from the Sublime Text 4 Dark invalid-token rules, which VS Code does not support.
- Lifted both Vesper variants out of pure near-black to ease eye strain, matching the lightness of the rest of the pack. The editor and terminal move from `#101010` to `#181818`, and the bordered shell from `#070707` to `#0F0F0F`, with every tab, list, widget, input, and border layer raised by the same step so the hierarchy is unchanged. Syntax colors keep at least 4.5:1 contrast.
- Darkened Vesper comments from `#A3A3A3` to `#8B8B8B` so they read clearly quieter than the gray keywords and operators (`#B6B6B6`), while staying above 4.5:1 against the editor.
- Set the minimap and editor overview ruler backgrounds explicitly to each theme’s editor background across all 22 themes, so the strip around the minimap matches the editor and the minimap text no longer looks like it floats on a different shade. The minimap slider is transparent at rest, with hover and drag highlights retained.

## 4.9.0 — 2026-10-22

- Softened Vesper’s surrounding UI in both variants with darker active tabs, list selections, hover fills, and resize grips. Bordered Vesper also uses a deeper outer shell and quieter workspace frames; Unbordered keeps its blended backgrounds and transparent dividers.

## 4.8.0 — 2026-10-22

- Refined both Vesper variants to match the rest of the pack while keeping the near-black workspace. Widgets, tabs, line highlights, and selections layer just above the black, with clearer widget and input borders and translucent scrollbars. Workspace text is quieter than the code, and added lines in the gutter, diffs, and minimap use the shared green.

## 4.7.0 — 2026-10-22

- Added Vesper and Vesper Unbordered, inspired by [Vesper](https://github.com/raunofreiberg/vesper): a near-black workspace with white code, gray keywords, orange declarations, and peppermint strings. Comments are an opaque gray, editor and terminal backgrounds match, cursors are white, and Git status colors keep their familiar meanings. The pack includes 22 themes across eleven palettes.

## 4.6.0 — 2026-10-21

- Removed bold text styling across all 20 themes, including declarations, keywords, Markdown headings, and Markdown bold spans. TextMate and semantic highlighting use regular weight throughout, retaining underline and strikethrough cues.
- Removed both Rosé Pine Moon Neutral variants and their gallery screenshots, keeping regular Rosé Pine Neutral in both border styles. The pack now includes 20 themes across ten palettes.
- Deepened both Graphite variants to blue-gray charcoal (`#22262d`) with coordinated workspace surfaces and clearer grayscale text levels. Slightly brightened body text, keywords, strings, and declaration names while keeping comments and punctuation quieter.
- Deepened the editor, terminal, frame, and supporting surfaces in both Rosé Pine Neutral and Xcode 26 Dark variants for a richer, less flat appearance while preserving their syntax palettes.
- Refined Rosé Pine Neutral syntax roles against the original theme: neutral readonly variables, enum uses, and parameter references; rose method calls; and iris interface references with foam declaration names. Kept existing shades and workspace colors.
- Gently softened both Tokyo Night variants with slightly lighter blue-violet workspace surfaces and subtly moderated syntax and accents, retaining most of the original palette’s saturation and lavender body text. Removed the blanket orange treatment of readonly variables.
- Added a subtle, palette-matched sticky-scroll divider across all 20 themes to distinguish pinned code rows from scrolling content, with transparent sticky-scroll shadows in both border styles. Removed Poimandres’ editor scroll shadow beneath the breadcrumbs.
- Removed the divider below the tab strip in both Dark Modern 2026 variants so tabs blend into the editor.
- Reduced VSIX size by excluding gallery screenshots and internal design documentation. README screenshots load from GitHub; the extension icon remains bundled.

## 4.5.0 — 2026-10-21

- Refined TypeScript and TSX syntax in both Sublime Text 4 variants to better match Mariana: blue type references with orange declarations, teal constructors and decorator punctuation, neutral annotation colons, white section punctuation, pink async modifiers, red new operators, and plain enum members.
- Replaced green comments in both Dark Modern 2026 variants with a readable neutral gray (`#929292`), including comment punctuation and semantic highlighting.
- Brightened search matches across all 22 themes to use the same fills as cursor-based word highlights, with the stronger word-highlight fill for the current match. Kept outlines transparent and matched Search Editor highlights to the same strength.

## 4.4.0 — 2026-10-21

- Slightly lightened both Dark Modern 2026 variants from near-black to deep charcoal (`#17181A`), with coordinated editor, terminal, tabs, inputs, and widgets. Bordered retains a darker outer frame and subtle dividers; Unbordered keeps blended workspace surfaces.
- Removed search-match outlines across all 22 themes so editor Find, the search sidebar, and Search Editor use background highlights consistent with matching-word highlights.

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
