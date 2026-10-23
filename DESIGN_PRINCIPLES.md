# Vine design principles

Vine brings favorite dark palettes together with a consistent feel. These are the ideas behind the themes and a guide for anyone contributing changes.

## Keep code easy to read

Syntax should be clear without being harsh. Comments stay readable but quieter than the code around them. Selections, search highlights, and Git changes should leave the text easy to read.

Use upright, regular-weight text throughout every theme, including comments, declarations, types, parameters, Markdown headings, and Markdown emphasis. TextMate font styles and semantic token rules must not enable bold or italics. Underline and strikethrough remain available where appropriate.

Contrast includes the separation between syntax colors and between active and secondary UI elements. Avoid making every role equally bright: use deeper backgrounds, distinct syntax hues, and quieter comments and inactive controls. Keep explicit syntax foregrounds at least 4.5:1 against the editor background, and check selections and the current line separately.

Each palette keeps its own character. The Graphite themes use a deep blue-gray background with a hierarchy of grayscale tones: soft body text, brighter declarations, quieter strings and punctuation, and readable subdued comments. Brighter declaration names provide structure at the same regular weight as the rest of the text, with color reserved for status indicators and terminal output.

Rosé Pine Neutral pairs rose and pine syntax hues with deep neutral charcoal workspace surfaces. Its darker pine and comment colors are lifted for readability. Xcode 26 Dark uses deeper cool charcoal surfaces to give its softer syntax colors clear contrast. Vesper keeps its deep, neutral near-black workspace (lifted slightly off pure black to reduce eye strain) with white code, gray keywords, orange declarations, and peppermint strings. Slightly lighter widgets, tabs, and selections layer above the black, and quieter gray workspace text keeps the code brightest. Its surrounding UI uses subdued tab and list fills, hover states, and resize grips, with a deeper outer shell and subtle frames in the bordered variant. Its translucent comments are lifted to an opaque gray so they stay quieter than the code and remain readable.

## Keep the editor calm

Night Owl uses muted slate-blue surfaces (`#1C2332` in the editor), retaining a distinct blue character with less teal than the original navy. Widgets, selections, and workspace frames share this restrained blue tint and retain the lighter palette’s brightness. Its yellow-green syntax is softened to a clearer mint-green (`#9FD4B0`) to complement the slate-blue workspace. Its comments remain readable on the editor, current line, and selection. Syntax follows the original’s TextMate rules by default, preserving language-specific distinctions without broad semantic overrides; text remains upright and regular-weight.

Use simple backgrounds, subtle highlights, and restrained accents. Tabs should feel connected to the editor, and scrollbars and the minimap should stay in the background.

Matching words use translucent, palette-matched fills without outlines, including read, write, and textual occurrences. Search matches use the same fills as cursor-based word highlights without outlines, in the editor, Search Editor, and search sidebar. The current search match uses the stronger word-highlight fill.

Sticky scroll uses a subtle, palette-matched divider without a drop shadow in both variants, keeping pinned code rows distinct from scrolling content.

The terminal, minimap, and editor overview ruler share the editor background for a continuous workspace. The minimap viewport slider stays transparent at rest, with visible hover and drag highlights.

Editor and terminal cursors use bright white (`#FFFFFF`) in every palette so they remain easy to locate among syntax colors.

## Offer three ways to frame the workspace

- **Bordered:** very subtle dividers separate the editor, sidebar, and panels, including modern UI frames.
- **Unbordered:** the main backgrounds blend together, with transparent workspace dividers and modern UI frames.
- **Uniform:** the unbordered single-color surfaces, with the bordered variant's subtle dividers and modern UI frames kept visible.

All variants share the same syntax colors, editor background, and text styling. Hover states, active controls, and keyboard focus should remain easy to spot.

## Keep status colors familiar

File colors keep their usual meanings across the pack:

| File status            | Color  |
| ---------------------- | ------ |
| Modified               | Yellow |
| Added or untracked     | Green  |
| Deleted or conflicting | Red    |
| Ignored                | Gray   |

In the editor gutter, added lines are green, modified lines are blue, and deleted lines are red. Diff views use subtle green and red shading, with stronger shading on the changed text.

Errors and warnings keep their familiar red and yellow meanings. Existing badges, symbols, and status letters help communicate changes alongside color.

## Check changes in a real editor

Compare both variants with everyday code, comments, selections, search results, terminal output, and Git diffs. Check readability as well as appearance, and credit the projects that inspired each palette.
