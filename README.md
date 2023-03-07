# VS Code Settings

## Extensions

For Comment Notes 
- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

For C++ 
- [C/C++ Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)

To complile & Run multiple programming language with a single click.
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)

For Screenshot
- [CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)

For Competitve Programming
- [CPH](https://marketplace.visualstudio.com/items?itemName=DivyanshuAgrawal.competitive-programming-helper)

To Integreate ESLint with VScode
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

For Java
- [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

To Change the only the font size of editor with keyboard shortcuts not the whole IDE
- [FontSize Shortcuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)

Makes indentation easier to read (Most useful in python):
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  
Manage npm, yarn, pnpm, dependencies from sidebar:
- [NPM](https://marketplace.visualstudio.com/items?itemName=idered.npm)

Format javascript, JSON, CSS, Sass:
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

JavaScript and TypeScript playground in your editor.
- [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)

Vim emulation for Visual Studio Code
- [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)

 Icons for Visual Studio Code
- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

## Theme

- [Tokyo Night](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night)

- [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl)

- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

- [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)

## Fonts

- [Cascadia Mono PL](https://github.com/microsoft/cascadia-code)
- [Operator Mono](https://www.typography.com/fonts/operator/styles) (if want italic feels)
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
- [Anonymous Pro](https://fonts.google.com/specimen/Anonymous+Pro)

## Extras
Create files anywhere in your workspace from the keyboard
- [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)

Open pdf file in VSCode: 
- [vscode-pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf)

To use Github Codespace in VSCode:
- [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces)
Autocomplete npm imports
- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
Displays a message in package.json files for packages with newer versions available.
- [npm Outdated](https://marketplace.visualstudio.com/items?itemName=mskelton.npm-outdated)
For jupitor Notebook
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

For CSS
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
- [CSS Var Complete](https://marketplace.visualstudio.com/items?itemName=phoenisx.cssvar)

For React 
- [React CSS modules](https://marketplace.visualstudio.com/items?itemName=viijay-kr.react-ts-css)

## Settings

```json
{
  //Search Prefs
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/*.code-search": true
  },
  "search.useIgnoreFiles": false,

  //Workbench Prefs
  "workbench.sideBar.location": "right",
  "workbench.iconTheme": "vscode-icons",
  "workbench.colorTheme": "Tokyo Night",
  "workbench.editorLargeFileConfirmation": 2048,
  //for theme night-owl - Separate the Editor from the Sidebar only
  /*  "workbench.colorCustomizations": { 
    "[Night Owl]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "editorGroup.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8BADC1"
    },
    "[Night Owl (No Italics)]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "editorGroup.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8badc1"
    }
  }, */

  "explorer.openEditors.visible": 0,
  "explorer.confirmDelete": false,
  "editor.suggestSelection": "first",
  "editor.snippetSuggestions": "top",
  "editor.linkedEditing": true, //Automatically edit a closing tag when editing an opening tag
  "editor.formatOnPaste": true,
  "editor.emptySelectionClipboard": false,
  "editor.formatOnSave": true,
  "editor.minimap.enabled": false,
  "editor.fontFamily": "'Cascadia Mono PL','Operator Mono','JetBrains Mono'",
  "editor.fontSize": 16,
  "editor.indentSize": "tabSize",
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.scrollBeyondLastLine": false,
  "editor.wordWrap": "on",

  "editor.lineHeight": 1.8,
  "files.autoSave": "afterDelay",
  "files.exclude": {
    "**/.*": true
  },

  //terminal prefs
  "terminal.integrated.fontFamily": "'Anonymous Pro'",
  "terminal.integrated.fontWeight": "bold",
  "terminal.integrated.fontSize": 18,

  "git.autofetch": true,
  "diffEditor.ignoreTrimWhitespace": false, //for git tarce

  "vsicons.dontShowNewVersionMessage": true,
  "extensions.ignoreRecommendations": true,
  "terminal.external.osxExec": "iterm.app",
  "terminal.explorerKind": "external",
  "editor.mouseWheelZoom": false,

  //rest custome prefs goes here time to time
  "code-runner.runInTerminal": true,
  "javascript.updateImportsOnFileMove.enabled": "always",

  "window.restoreWindows": "preserve",
  "cph.general.defaultLanguage": "java",
  "eslint.enable": true,
  "eslint.validate": ["vue", "react", "typescript", "javascript"],

  "prettier.tabWidth": 2,

  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "[python]": {
    "editor.formatOnType": true
  }
}
```
