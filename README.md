# swc-unexpected-token-with


Steps to reproduce:

```sh
git clone https://github.com/caugner/swc-unexpected-token-with.git
cd swc-unexpected-token-with
nvm use
npm i
npm start
```

Yields:

```
SyntaxError: Unexpected token 'with'
    at ESMLoader.moduleStrategy (node:internal/modules/esm/translators:119:18)
    at ESMLoader.moduleProvider (node:internal/modules/esm/loader:468:14)
    at async link (node:internal/modules/esm/module_job:68:21)
```