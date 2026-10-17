# Vine design principles

Vine brings favorite dark palettes together with a consistent feel. These are the ideas behind the themes and a guide for anyone contributing changes.

## Keep code easy to read

Syntax should be clear without being harsh. Comments stay readable but quieter than the code around them. Selections, search highlights, and Git changes should leave the text easy to read.

Each palette keeps its own character. The b&w themes use grayscale and typography to distinguish syntax, with color reserved for status indicators and terminal output.

## Keep the editor calm

Use simple backgrounds, subtle highlights, and restrained accents. Tabs should feel connected to the editor, and scrollbars and the minimap should stay in the background.

The terminal and editor share the same background for a continuous workspace.

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
