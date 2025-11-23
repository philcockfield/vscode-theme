# vscode-theme
VSCode Theme Settings

<p>&nbsp;</p>

## Open Settings (JSON)
Press **Cmd + Shift + P**, type “**Preferences: Open Settings (JSON)**”, and hit **Enter**.

<p>&nbsp;</p>

## Theme Overrides
These settings refine the overall editor appearance, tab bar, and tree-view selection behavior while keeping the `Monokai` color syntax intact.

```jsonc
{
  // --- Theme ----------------------------------
  "workbench.colorCustomizations": {
    // Editor:
    "editor.background": "#1B202C",
    "editorWidget.background": "#1B202C",

    // Layout chrome:
    "sideBar.background": "#252B3B",
    "activityBar.background": "#151821",
    "titleBar.activeBackground": "#293042",

    // Panels / aux views:
    "panel.background": "#293042",
    "panelTitle.inactiveForeground": "#5F6471",
    "terminal.background": "#212635",
    "minimap.background": "#212635",
    "input.background": "#252B3B",

    // Tab-bar:
    "tab.inactiveBackground": "#3A4154",
    "editorGroupHeader.tabsBackground": "#3A4154",

    // Tree-view:
    "list.activeSelectionBackground": "#009FE6",
    "list.inactiveSelectionBackground": "#009FE6",
    "list.activeSelectionForeground": "#FFFFFF",
    "list.inactiveSelectionForeground": "#FFFFFF",
    "list.hoverBackground": "#00B2FF55", // softer, translucent hover
    "list.hoverForeground": "#FFFFFF"
  },

}
```
