# Vine design principles

Vine brings favorite dark palettes together with a consistent feel. These are the ideas behind the themes and a guide for anyone contributing changes.

## Keep code easy to read

Syntax should be clear without being harsh. Comments stay readable but quieter than the code around them. Selections, search highlights, and Git changes should leave the text easy to read.

Contrast includes the separation between syntax colors and between active and secondary UI elements. Avoid making every role equally bright: use deeper backgrounds, distinct syntax hues, and quieter comments and inactive controls. Keep explicit syntax foregrounds at least 4.5:1 against the editor background, and check selections and the current line separately.

Each palette keeps its own character. The Graphite themes use a deep blue-gray background with a hierarchy of grayscale tones: soft body text, brighter declarations, quieter strings and punctuation, and readable subdued comments. Restrained bold declarations provide structure, while keywords and type references use regular weight, with color reserved for status indicators and terminal output.

Rosé Pine Neutral and Rosé Pine Moon Neutral pair their respective syntax hues with the same neutral gray workspace surfaces. Their darker pine and comment colors are lifted for readability.

## Keep the editor calm

Use simple backgrounds, subtle highlights, and restrained accents. Tabs should feel connected to the editor, and scrollbars and the minimap should stay in the background.

The terminal and editor share the same background for a continuous workspace.

Editor and terminal cursors use bright white (`#FFFFFF`) in every palette so they remain easy to locate among syntax colors.

## Offer two ways to frame the workspace

- **Bordered:** subtle dividers separate the editor, sidebar, and panels.
- **Unbordered:** the main backgrounds and dividers blend together.

Both variants share the same syntax colors, editor background, and text styling. Hover states, active controls, and keyboard focus should remain easy to spot.

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
