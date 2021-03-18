<h2 align="center">Visual Studio Code settings ⚙️</h2>

- [x] Theme: [Omni](https://marketplace.visualstudio.com/items?itemName=rocketseat.theme-omni)
- [x] Font: [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
- [x] Integrated Terminal: [Fish](https://fishshell.com/) 
- [x] Icons: [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

```json
{
  "terminal.integrated.fontSize": 13.5,
  "terminal.integrated.lineHeight": 23,
  "terminal.integrated.automationShell.linux": "fish",
  "terminal.integrated.shell.linux": "/usr/bin/fish",
  "terminal.integrated.detectLocale": "auto",

  "window.zoomLevel": 1.5,

  "workbench.colorTheme": "Omni",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.startupEditor": "newUntitledFile",

  "editor.tabSize": 2,
  "editor.fontSize": 13.5,
  "editor.lineHeight": 23,
  "editor.fontFamily": "JetBrains mono",
  "editor.letterSpacing": 0.5,
  "editor.fontLigatures": true,

  "npm-intellisense.importES6": true,
  "npm-intellisense.importQuotes": "'",
  "npm-intellisense.importLinebreak": ";\r\n",
  "npm-intellisense.importDeclarationType": "const",

  "files.associations": {
    "html": "njk",
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    ".prettierrc": "json",
    "*.tsx": "typescriptreact"
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
    "javascript": "javascriptreact"
  },

  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,

  "git.enableSmartCommit": true,

  "breadcrumbs.enabled": true,
  "editor.parameterHints.enabled": false,
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "editor.minimap.enabled": false,

  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.insertSpaces": true,
    "editor.detectIndentation": false
  },

  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2
  },

  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  "todo-tree.tree.showScanModeButton": false,

  "liveshare.authenticationProvider": "GitHub",

  "diffEditor.ignoreTrimWhitespace": false,

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
  }
}
```
