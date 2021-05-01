<h2 align="center">Visual Studio Code settings ⚙️</h2>

- [x] Theme: [Omni](https://marketplace.visualstudio.com/items?itemName=rocketseat.theme-omni)
- [x] Font: [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
- [x] Integrated Terminal: [Fish](https://fishshell.com/) 
- [x] Icons: [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

```json
{
  "terminal.integrated.fontSize": 13,
  "terminal.integrated.automationShell.linux": "fish",
  "terminal.integrated.shell.linux": "fish",

  "window.zoomLevel": 1,

  "workbench.colorTheme": "Omni",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",

  "editor.parameterHints.enabled": false,
  "editor.minimap.enabled": false,
  "editor.quickSuggestions.comments": true,

  "editor.tabSize": 2,
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 13.5,
  "editor.letterSpacing": 0.2,
  "editor.fontLigatures": true,

  "editor.formatOnSave": true,

  "npm-intellisense.importES6": true,
  "npm-intellisense.importQuotes": "'",
  "npm-intellisense.importLinebreak": ";\r\n",
  "npm-intellisense.importDeclarationType": "const",

  "files.associations": {
    "html": "njk",
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json",
    "*.tsx": "typescriptreact",
    "*.jsx": "javascriptreact"
  },

  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true
    // "**/node_modules": true
  },

  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },

  "emmet.includeLanguages": {
    "njk": "html",
    "javascript": "javascriptreact",
    "typescript": "typescriptreact"
  },

  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,

  "git.enableSmartCommit": true,

  "breadcrumbs.enabled": true,

  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,

  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.detectIndentation": true
  },

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.detectIndentation": true
  },

  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.detectIndentation": true
  },

  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.detectIndentation": true
  },

  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "todo-tree.tree.showScanModeButton": false,

  "liveshare.authenticationProvider": "GitHub",

  "material-icon-theme.folders.associations": {
    "infra": "app",
    "entities": "class",
    "domain": "class",
    "schemas": "class",
    "typeorm": "database",
    "repositories": "mappings",
    "http": "container",
    "migrations": "tools",
    "modules": "components",
    "implementations": "core",
    "dtos": "typescript",
    "fakes": "mock",
    "websockets": "pipe",
    "protos": "pipe",
    "grpc": "pipe",
    "providers": "include",
    "subscribers": "messages",
    "useCases": "controller",
    "kafka": "scripts",
    "mappers": "meta",
    "_shared": "shared",
    "eslint-config": "tools",
    "kube": "kubernetes"
  },

  "errorLens.fontFamily": "Ubuntu",
  "errorLens.fontSize": "12",
  "errorLens.delay": 0,

  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.enabled": false,

  "label": "Test",
  "options": {
    "statusbar": {
      "hide": true
    }
  },

  "resmon.show.battery": false,
  "resmon.show.cpufreq": false,

  "prettier.singleQuote": true,
  "prettier.jsxSingleQuote": true,

  "git.confirmSync": false,

  "diffEditor.ignoreTrimWhitespace": false,
  "tabnine.experimentalAutoImports": true
}
```
