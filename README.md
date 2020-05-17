
# Dev environment setup - Tailbuds

- [Dev environment setup - Tailbuds](#dev-environment-setup---tailbuds)
  - [Required Programs](#required-programs)
  - [Optional Programs](#optional-programs)
  - [Recommended Code Editor](#recommended-code-editor)
  - [Recomended Extentions: VS Code](#recomended-extentions-vs-code)
  - [Recommended Settings: VSCode Preferences (JSON).](#recommended-settings-vscode-preferences-json)

## Required Programs

1. Chrome
2. Code editor like VS Code
3. Postman

## Optional Programs

1. Docker
2. Adobe XD
3. Adobe Photoshop
4. Adobe Illustrator

## Recommended Code Editor

Microsoft Visual Studio Code (VS Code)

## Recomended Extentions: VS Code

> Please feel free to suggest any removals or additions of the following extensions. The goal is to improve developer's experience and efficiency.

1. Activitus Bar
2. Angular Essentials (version 9) [A pack of 12 extensions]
3. Auto Close Tag
4. Auto import
5. Auto Rename Tag
6. BEM Helper
7. Better Comments
8. Bracket Pair Colorizer
9. Code Spell Checker
10. Docker
11. Docker Compose
12. Docker Explorer
13. Docker Linter
14. Docker Runner
15. Document This
16. filesize
17. Github
18. Github Markdown Preview
19. Graphql for VSCode
20. indent-rainbow
21. intelliSense for CSS class names in HTML
22. Javascript Booster
23. JS Refactor
24. Kite Autocomplete for Python and JavaScript (requires Kite engine installed in your system and running)
25. Live Share Extension Pack [A pack of 4 extensions]
26. Markdown All in one
27. Markdown PDF
28. Markdown Preview Github Styling
29. Markdownlint
30. Mithril Emmet
31. Node Essentials
32. Node Exec
33. Node-readme
34. Node.js Modules Intellisense
35. npm
36. npm Intellisense
37. NPM--Scripts
38. Polacode
39. Project Manager
40. Remote Development [A Pack of 3 extensions]
41. search node_modules
42. Settings Sync
43. SQLTools - Database tools
44. Test Explorer UI
45. Todo Tree
46. View Node Package
47. YAML

## Recommended Settings: VSCode Preferences (JSON).

Feel free to suggest any changes.

Shortcut: ```Ctrl+Shift+P```

Search 'Preferences'. Open 'Preferences: Open Settings (JSON)'

Clear out any settings and paste the following:

```{json}
{
  // window settings
  "window.zoomLevel": -1,

  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "liveshare.audio.startCallOnShare": true,

  // editor settings
  "editor.suggestSelection": "first",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,

  // prettier settings
  "prettier.singleQuote": true,
  "prettier.semi": true,
  "prettier.printWidth": 80,

  // file settings
  "files.insertFinalNewline": true,
  "files.autoSave": "off",

  // git settings
  "git.autofetch": true,

  // Enable per-language

  // html, css, javascript and json settings
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },

  // css settings
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // javascript settings
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",

  // json settings
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // json with comments settings
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // python settings
  "[python]": {
    "editor.defaultFormatter": "kiteco.kite"
  },

  // Kite settings
  "kite.enableSnippets": true,
  "kite.startKiteEngineOnStartup": true,
  "kite.showWelcomeNotificationOnStartup": false,

  // sync settings
  "sync.autoDownload": true,
  "sync.autoUpload": true,

  // gitlense settings
  "gitlens.codeLens.enabled": false,
  "gitlens.currentLine.enabled": false,
  "gitlens.views.compare.location": "scm",
  "gitlens.views.fileHistory.location": "scm",
  "gitlens.views.lineHistory.location": "scm",
  "gitlens.views.repositories.location": "scm",
  "gitlens.views.search.location": "scm",

  // Better comments settings
  "better-comments.multilineComments": true,
  "better-comments.highlightPlainText": true,
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "backgroundColor": "transparent"
    },
    {
      "tag": "todo",
      "color": "#FF8C00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "*",
      "color": "#98C379",
      "strikethrough": false,
      "backgroundColor": "transparent"
    }
  ],
  "files.associations": {
    "*.rmd": "markdown",
    "*.html": "html"
  },

  // icon theme
  "workbench.iconTheme": "material-icon-theme",

  // icon theme settings
  "material-icon-theme.folders.color": "#09d9e1",
  "material-icon-theme.opacity": 0.9,
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.activeIconPack": "angular_ngrx",
  "todo-tree.tree.showScanModeButton": false,

  // Activitus Bar settings
  "activitusbar.views": [
    {
      "name": "explorer",
      "octicon": "file-text"
    },
    {
      "name": "search",
      "octicon": "search"
    },
    {
      "name": "scm",
      "octicon": "repo-forked"
    },
    {
      "name": "debug",
      "octicon": "bug"
    },
    {
      "name": "extensions",
      "octicon": "package"
    },
    {
      "name": "extension.todo-tree-container",
      "octicon": "tasklist"
    }
  ],
  "cSpell.userWords": [
    "Tailbuds",
    "peerdeps"
  ]
}

```

Tweak to your comfort and enjoy coding with Tailbuds.

Dev Team

<img src="./Logo.png" width="200">
