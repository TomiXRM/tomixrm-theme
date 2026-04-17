# tomixrm Theme

`tomixrm Warm Hybrid` is a VS Code color theme built from the palette in your personal `settings.json`.

## What is included

- Light workbench UI derived from `workbench.colorCustomizations`
- Dark editor, terminal, and lower panel areas with Monokai Pro-like syntax role balance
- A few small normalizations for contrast and theme-key compatibility

## What is not included

This extension only packages theme colors. Editor behavior, font, formatter, Git, terminal, and extension-specific settings should stay in your personal `settings.json`.

## Preview the theme

1. Open this folder in VS Code
2. Press `F5`
3. In the Extension Development Host, select `tomixrm Warm Hybrid`

## Notes

- The typo `inputValidation.errorForeground:` from the source settings was corrected to `inputValidation.errorForeground`
- `sideBarTitle.background` is not a standard theme color key, so it was not carried over directly
- Monokai Pro itself is not vendored or forked here; the syntax highlighting is an original implementation inspired by that category balance
