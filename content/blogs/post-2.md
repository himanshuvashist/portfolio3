---
title: "My VSCode setup"
date: "2021-09-06"
draft: false
path: "/blog/my-vscode-setup"
---

### Font

- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

### Extensions

- [Palenight Theme](https://vscodethemes.com/e/whizkydee.material-palenight-theme)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Noctis Theme](https://marketplace.visualstudio.com/items?itemName=liviuschera.noctis)
- [Horizon Theme](https://marketplace.visualstudio.com/items?itemName=jolaleye.horizon-theme-vscode)
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
- [Dracula Theme](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Mayukai Theme](https://marketplace.visualstudio.com/items?itemName=GulajavaMinistudio.mayukaithemevsc)
- [Github Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
- [Monokai Pro](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode)

### Style/Formatting

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Useful/Extra

- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  - Display inline the size of the required/imported package
- [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  - Evaluate code/logs inline and show results in the editor

# User settings

```json
{
  "explorer.openEditors.visible": 0,
  //   "workbench.colorTheme": "Monokai Dimmed",
  //   "workbench.colorTheme": "Mayukai Alucard",
  "workbench.colorTheme": "Monokai Pro (Filter Machine)",
  "editor.fontFamily": "'Anonymous Pro', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.fontSize": 15,
  "editor.fontWeight": "bold",
  "editor.wordWrap": "on",
  "workbench.iconTheme": "material-icon-theme",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.cursorBlinking": "phase",
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "window.zoomLevel": 1
}
```
