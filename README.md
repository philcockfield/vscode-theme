# vscode-theme

VSCode Theme Settings

<img width="1098" height="726" alt="image" src="https://github.com/user-attachments/assets/869cede5-9fd4-41c6-9d5e-3562bcf7e159" />

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
    "editor.lineHighlightBackground": "#2A3040",
    "editor.foldBackground": "#14192080",

    // Layout chrome:
    "sideBar.background": "#252B3B",
    "activityBar.background": "#151821",
    "titleBar.activeBackground": "#293042",

    // Status bar:
    "statusBar.background": "#151821",
    "statusBar.foreground": "#D3D7E0",
    "statusBar.noFolderBackground": "#151821",
    "statusBar.debuggingBackground": "#293042",

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
    "list.activeSelectionForeground": "#FFFFFF",

    "list.inactiveSelectionBackground": "#009FE64D",
    "list.inactiveSelectionForeground": "#FFFFFF",

    "list.hoverBackground": "#00B2FF55",
    "list.hoverForeground": "#FFFFFF"
  }
}
```
