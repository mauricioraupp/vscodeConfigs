# vscodeConfigs

# Install JetBrains Mono
```
https://www.jetbrains.com/pt-br/lp/mono/#how-to-install
```
After the file is extracted, select all the fonts and install

# Go to (JSON) Open user settings
Execute command Ctrl + Shift + P and search for:
```
Preferences: Open User Settings (JSON)
```
and paste the codes:
```
{
    "window.zoomLevel": 0.7,
    "workbench.iconTheme": "symbols",
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.useLocalIp": true,
    "workbench.colorTheme": "Min Dark",
    "symbols.hidesExplorerArrows": false,
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontSize" :14,
    "editor.lineHeight": 1.8,
    "editor.rulers": [80, 120],
    "workbench.startupEditor": "newUntitledFile",
    "editor.renderLineHighlight": "gutter",
    "editor.fontLigatures": true,
    "workbench.editor.labelFormat": "short",
    "explorer.compactFolders": false,
    "editor.semanticHighlighting.enabled": false,
    "breadcrumbs.enabled": false,
    "editor.minimap.enabled": false,
    "editor.scrollbar.horizontal": "hidden",
    "editor.scrollbar.vertical": "hidden",
    "workbench.statusBar.visible": false,
    "workbench.activityBar.location": "hidden",
    "apc.electron": {
        "titleBarStyle": "hiddenInset",
        "frame": false,
    },
    "apc.header": {
        "height": 36
    },
    "apc.font.family": "Inter",
    "apc.stylesheet": {
        ".title-label > h2": "display: none",
        //".editor-actions": "display: none",
        ".pane-header": "padding: 8px",
        ".pane-body": "padding: 8px",
        ".split-view-view:first-child pane-header": "display: none !important;",
    },
    "workbench.layoutControl.enabled": false,
    "window.commandCenter": false,
    "explorer.fileNesting.enabled": true,
    "explorer.fileNesting.patterns": {
        "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-lock*, package-lock*, bun.lockb",
        "tailwind.config*": "tailwind.config*, postcss.config*",
        ".env.local": ".env*",
        ".env": ".env*",
    },
    "terminal.integrated.fontSize": 14,
    "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
}
```

## PS: Paste the code under the initial code just in case any line is missing, if any line is duplicated, just delete the old one.
