
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
## OutPut Error :   

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
## OutPut Error :   

```bash
 npm install --save react react-dom @types/react @types/react-dom
```




