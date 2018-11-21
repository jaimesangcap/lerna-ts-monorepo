This is a working setup for referencing local typescript package

`npx lerna bootstrap`

`tsc -b`

`cd packages/api`

`node lib/index.js`

there should be an error

```
Error: Cannot find module '@elts/common/testing/seed'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:581:15)
    at Function.Module._load (internal/modules/cjs/loader.js:507:25)
    at Module.require (internal/modules/cjs/loader.js:637:17)
    at require (internal/modules/cjs/helpers.js:20:18)
    at Object.<anonymous> (F:\sanay\lerna-ts-monorepo\packages\api\lib\index.js:3:14)
    at Module._compile (internal/modules/cjs/loader.js:689:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:700:10)
    at Module.load (internal/modules/cjs/loader.js:599:32)
    at tryModuleLoad (internal/modules/cjs/loader.js:538:12)
    at Function.Module._load (internal/modules/cjs/loader.js:530:3)
```

Any help would be appreciated :)
