Please run:

```
yarn vite
```

You should get the following error:

```
File: /Users/david/repos/preconstruct-repro/packages/a/dist/myrepo-a.esm.js
  1  |  import { data } from "./data";
     |                        ^
  2  |  
  3  |  export function fn1() {
      at formatError (/Users/david/repos/preconstruct-repro/node_modules/vite/dist/node/chunks/dep-1bdbec90.js:45829:46)
      at TransformContext.error (/Users/david/repos/preconstruct-repro/node_modules/vite/dist/node/chunks/dep-1bdbec90.js:45825:19)
      at normalizeUrl (/Users/david/repos/preconstruct-repro/node_modules/vite/dist/node/chunks/dep-1bdbec90.js:47314:26)
      at async TransformContext.transform (/Users/david/repos/preconstruct-repro/node_modules/vite/dist/node/chunks/dep-1bdbec90.js:47443:57)
      at async Object.transform (/Users/david/repos/preconstruct-repro/node_modules/vite/dist/node/chunks/dep-1bdbec90.js:46027:30)
      at async transformRequest (/Users/david/repos/preconstruct-repro/node_modules/vite/dist/node/chunks/dep-1bdbec90.js:61624:29)
      at async /Users/david/repos/preconstruct-repro/node_modules/vite/dist/node/chunks/dep-1bdbec90.js:61732:32
```