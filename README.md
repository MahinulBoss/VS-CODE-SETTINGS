<h1>My Personal VS Code Setting.json and My Fav Extensions</h1>
<h2>My Fav VS Code Extensoions</h2>
<ul>
  <li>Auto Close Tag (Jun Han)</li>
  <li>Auto Rename Tag (Jun Han)</li>
  <li>Fluent Icons (Mingul Solorio)</li>
  <li>Icon Fonts (idleberg)</li>
  <li>Live Share (Microsf)</li>
  <li>Path Intellisense (Christian Kohler)</li>
  <li>PHP Debug (Xdebug)</li>
  <li>Prettier-Code formatter(Prettier)</li>
  <li>Sweet Dracula (PROxZIMA)</li>
  <li>Sweet vscode Icons (Eliver Lara)</li>
  <li>Symbols (Mingel Solorio)</li>
  <li>Tabnine:AI (TabNINE)</li>
  <li>Tailwind Snippets (ZS Software Studio)</li>
  <li>Auto Save on Window</li>
  <li>Class autocomplete</li>
  <li>Highlight Matching Tag (vincaslt)</li>
  <li>Code Runner (Jun Han)</li>
  <li>Codeium AI (Codeium)</li>
  <li>ESLint (microsoft)</li>
  <li>In your face</li>
  <li>live sass compiler</li>
  <li>live server (Five server)</li>
  <li>ident-rainbow</li>
  <li>MongoDB</li>
  <li>Stylelint (Stylelint)</li>
  <li>Tailwind CSS Intellisense (Tailwind Labs)</li>
</ul>






{
    "editor.fontSize": 15,
    "editor.tabSize": 2,
    "editor.wordWrap": "on",
    "editor.cursorSmoothCaretAnimation": true,
    "editor.cursorBlinking": "expand",
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.formatOnType": true,
    "workbench.colorCustomizations": {
      "editorGroupHeader.tabsBackground": "#32084e",
      "activityBar.background": "#290041",
      "sideBar.background": "#180029",
      "minimap.background": "#141422",
      "tab.activeBackground": "#592881",
      "tab.inactiveBackground": "#270047",
      "terminal.border": "#39005a",
      "terminal.background": "#2c2c54",
      "statusBar.background": "#28005c",
      "scrollbarSlider.background": "#12001d",
      "scrollbarSlider.hoverBackground": "#1a0044"
    },
    "editor.tokenColorCustomizations": {
      "comments": "#d9ff00"
    },
    "editor.linkedEditing": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs": true,
    "editor.guides.bracketPairsHorizontal": true,
    "editor.hover.enabled": false,
    "window.zoomLevel": 0,
    // Live Server 
    "liveServer.settings.CustomBrowser": "chrome:PrivateMode",
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.donotVerifyTags": true,
    // Live SASS Compiler
    "liveSassCompile.settings.formats": [
      {
        "format": "compressed",
        "extensionName": ".min.css",
        "savePath": "/css"
      }
    ],
    "liveSassCompile.settings.generateMap": true,
    // VS Code Theme Customization
    "workbench.iconTheme": "sweet-vscode-icons",
    "workbench.colorTheme": "Sweet Dracula",
    "workbench.editor.enablePreview": false,
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "terminal.integrated.fontSize": 20,
    "diffEditor.wordWrap": "off",
    "security.workspace.trust.untrustedFiles": "open"
    // "files.autoSave": "afterDelay",
    // "files.autoSaveDelay": 10,

    // Prettier Config
    "prettier.proseWrap": "always",
    "prettier.singleQuote": true,
    "prettier.arrowParens": "avoid",
      "editor.defaultFormatter": "esbenp.prettier-vscode",
      "[html]": {
      "editor.defaultFormatter": "vscode.html-language-features"
    },
    // Screencast Mode
    "screencastMode.onlyKeyboardShortcuts": true,
    "screencastMode.mouseIndicatorColor": "#2d0042",
    "screencastMode.verticalOffset": 0,

    // Enable Emmet support for JSX
     "emmet.includeLanguages": {
        "javascript": "javascriptreact"
     }
  }
