# Repository with submodules

## Project structure:
```
root-repository
├─ .vscode
|  ├─ .code-workspace
|  └─ launch.json
├─ app
|  └─ index.tsx
├─ admin (module)
|  ├─ src
|  |  ├─ components-module (module)
|  |  ├─ components
|  |  ├─ pages
|  |  ├─ utils
|  |  └─ index.tsx
|  └─ package.json
├─ modeler (module)
|  ├─ src
|  |  ├─ components-module (module)
|  |  ├─ components
|  |  ├─ utils
|  |  └─ index.tsx
|  └─ package.json
├─ package.json
├─ tsconfig.json
├─ webpack.config.json
├─ .prettierrc
└─ .eslint
```
![Project dependencies](/structure.jpg "Project dependency schema")