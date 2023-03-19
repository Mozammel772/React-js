
# Login Heroku
```
4TVV5NIKH8
OD25KFY75Q
D57YIWKEV3
9KA8ZOFP4J
Z4M1UMXNVN
SWHONJA6JZ
XDHNPYL3RX
5RCBY92YIP
YAJ6CQO02K
XQ6ZLGFV5W
```
# React Text Area Problem :

## 1. Warning: Use the `defaultValue` or `value` props instead of setting children on <textarea>.
```
1.1  Warning: Use the `defaultValue` or `value` props instead of setting children on <textarea>.
    at textarea
    at td
    at tr
    at tbody
    at table
    at div
    at div
    at KichenOrder (http://localhost:3000/static/js/bundle.js:1078:78)
    at RequireAuth (http://localhost:3000/static/js/bundle.js:1633:5)
    at RenderedRoute (http://localhost:3000/static/js/bundle.js:78309:5)
    at Routes (http://localhost:3000/static/js/bundle.js:78731:5)
    at div
    at App
    at Router (http://localhost:3000/static/js/bundle.js:78669:15)
    at BrowserRouter (http://localhost:3000/static/js/bundle.js:77001:5)

```

## 1.1 OutPut Error Solve :

```
1.1  defaultValue={a.message}
```






# React Error Handle :

## React Error Handle Comment Run ...

# 1. 'react-scripts' is not recognized as an internal or external command,

```bash
MdMoz@Mozammel-Hosen MINGW64 /d/projects/stand-success-client (main)
$ npm start

> profitshop-client@0.1.0 start
> react-scripts start

'react-scripts' is not recognized as an internal or external command,
operable program or batch file.
```
## OutPut Error Solve :   

```bash
 npm i -g react-scripts
```
# 2. Error: Cannot find module 'react'

```bash
MdMoz@Mozammel-Hosen MINGW64 /d/projects/stand-success-client (main)
$ npm start

> profitshop-client@0.1.0 start
> react-scripts start

node:internal/modules/cjs/loader:998
  throw err;
  ^

Error: Cannot find module 'react'
Require stack:
- C:\Users\MdMoz\AppData\Roaming\npm\node_modules\react-scripts\scripts\start.js
    at Module._resolveFilename (node:internal/modules/cjs/loader:995:15)
    at Function.resolve (node:internal/modules/cjs/helpers:109:19)
    at Object.<anonymous> (C:\Users\MdMoz\AppData\Roaming\npm\node_modules\react-scripts\scripts\start.js:43:31)
    at Module._compile (node:internal/modules/cjs/loader:1159:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1213:10)
    at Module.load (node:internal/modules/cjs/loader:1037:32)
    at Module._load (node:internal/modules/cjs/loader:878:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12)     
    at node:internal/main/run_main_module:23:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    'C:\\Users\\MdMoz\\AppData\\Roaming\\npm\\node_modules\\react-scripts\\scripts\\start.js' 
  ]
}

Node.js v18.12.0
```
## OutPut Error Solve :   

```bash
 npm install --save react react-dom @types/react @types/react-dom
```


```bash
    {
  // editor
  "editor.fontSize": 23,
  "editor.fontFamily": "Fira Code",
  "editor.fontWeight": "normal",
  "editor.fontLigatures": true,
  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },
  // cursor
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "expand",
  // config related to code formatting
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.tslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true,
  //terminal
  "terminal.integrated.fontSize": 18,
  "terminal.integrated.fontWeight": "bold",
  "terminal.integrated.fontFamily": "Fira Code",
  // terminal customization
  "workbench.colorCustomizations": {
    "terminal.background": "#1D2021",
    "terminal.foreground": "#c7bfb8fb",
    "terminalCursor.background": "#A89984",
    "terminalCursor.foreground": "#A89984",
    "terminal.ansiBlack": "#1D2021",
    "terminal.ansiBlue": "#0D6678",
    "terminal.ansiBrightBlack": "#665C54",
    "terminal.ansiBrightBlue": "#0D6678",
    "terminal.ansiBrightCyan": "#8BA59B",
    "terminal.ansiBrightGreen": "#95C085",
    "terminal.ansiBrightMagenta": "#8F4673",
    "terminal.ansiBrightRed": "#FB543F",
    "terminal.ansiBrightWhite": "#FDF4C1",
    "terminal.ansiBrightYellow": "#FAC03B",
    "terminal.ansiCyan": "#8BA59B",
    "terminal.ansiGreen": "#95C085",
    "terminal.ansiMagenta": "#8F4673",
    "terminal.ansiRed": "#FB543F",
    "terminal.ansiWhite": "#A89984",
    "terminal.ansiYellow": "#FAC03B"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "[css]": {
    "editor.defaultFormatter": "vscode.css-language-features"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "emmet.syntaxProfiles": {},
  "emmet.preferences": {},
  "emmet.triggerExpansionOnTab": true,
  "npm.exclude": "",
  "workbench.editor.enablePreviewFromCodeNavigation": true,
  "editor.bracketPairColorization.enabled": false,
  "tailwindCSS.includeLanguages": {
    "plaintext": "html"
  },

  "tabnine.experimentalAutoImports": true,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "workbench.iconTheme": "vscode-icons",
  "tailwindCSS.emmetCompletions": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "workbench.editor.enablePreview": false,
  "liveServer.settings.ChromeDebuggingAttachment": false,
  "liveServer.settings.CustomBrowser": "chrome",
  "workbench.colorTheme": "Community Material Theme Darker High Contrast",
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "emmet.useInlineCompletions": true
}

  ```
