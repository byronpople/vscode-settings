
# 🚀 My VS Code React Development Setup

This repo documents my personal Visual Studio Code setup for **React development**.  
It includes my settings, extensions, and recommendations for a solid front-end workflow.

___

## Font

Geist truly represents the coding and design spirit within Vercel's creative community.
---

## 🎨 Settings

```json
{
  "workbench.colorTheme": "Monokai Pro (Filter Ristretto)",
  "workbench.iconTheme": "Monokai Pro (Filter Ristretto) Icons",
  "editor.fontSize": 13,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,
  "editor.lineHeight": 20,
  "editor.tabSize": 2,
  "editor.formatOnPaste": false,
  "editor.inlineSuggest.enabled": true,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.suggestSelection": "first",
  "editor.codeActionsOnSave": {
    "source.fixAll": true,
    "source.fixAll.eslint": true
  },
  "eslint.enable": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html"
  ],
  "files.autoSave": "onWindowChange",
  "files.exclude": {
    "**/.git": true,
    "**/.DS_Store": true,
    "**/node_modules": true,
    "**/dist": true,
    "**/build": true
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "git.autofetch": true,
  "git.openRepositoryInParentFolders": "never",
  "markdown.preview.fontSize": 36,
  "screencastMode.keyboardOptions": {
    "showCommandGroups": false,
    "showCommands": false,
    "showKeybindings": true,
    "showKeys": false,
    "showSingleEditorCursorMoves": true
  },
  "search.exclude": {
    "**/*.code-search": true,
    "**/bower_components": true,
    "**/node_modules": true
  },
  "search.useIgnoreFiles": false,
  "terminal.integrated.fontSize": 13,
  "window.zoomLevel": 1.25,
  "workbench.editor.labelFormat": "medium",
  "workbench.editor.showTabs": "none",
  "workbench.sideBar.location": "right",
  "workbench.startupEditor": "newUntitledFile",
  "workbench.statusBar.visible": false,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[handlebars]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```

---

## 🔌 Extensions

### Terminal instalation

```bash
 cat vs-extensions.txt | xargs -L1 code --install-extension
 ```

### Current Installed Extensions

```bash
adpyke.codesnap
bradlc.vscode-tailwindcss
christian-kohler.npm-intellisense
dbaeumer.vscode-eslint
dotjoshjohnson.xml
dsznajder.es7-react-js-snippets
esbenp.prettier-vscode
monokai.theme-monokai-pro-vscode
rangav.vscode-thunder-client
streetsidesoftware.code-spell-checker
yoavbls.pretty-ts-errors
```

---

### 📈 Recommended Additional Extensions

```bash
# React / JS / TS
ms-vscode.vscode-typescript-next
OfHumanBondage.react-proptypes-intellisense
patrys.vscode-code-outline
christian-kohler.path-intellisense
wix.vscode-import-cost

# Git
eamodio.gitlens

# Productivity
formulahendry.auto-rename-tag
formulahendry.auto-close-tag
```

---

## ⚙️ Notes

- **ESLint** and **Prettier** are configured to format and lint on save for consistency.
- **Tailwind CSS IntelliSense** provides auto-completion and linting for Tailwind classes.
- **Thunder Client** allows lightweight API testing inside VS Code.
- **GitLens** offers powerful Git features and history.
- **Pretty TypeScript Errors** improves readability of TypeScript errors in the editor.
- **CodeSnap** helps take beautiful code screenshots for documentation or sharing.

---

## ✅ Conclusion

This is a solid and modern VS Code setup for React + TypeScript + Tailwind CSS development.  
It's flexible, fast, and tuned for a good developer experience.

---

_Keep this README.md version-controlled so that you can easily share your personal VS Code environment across machines and projects._  
Happy coding! 🚀
