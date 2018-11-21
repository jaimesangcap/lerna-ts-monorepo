This is a working setup for referencing local typescript package

`npx lerna bootstrap`

`tsc -b`

`cd packages/api`

`node lib/index.js`

there should be a console output

`Hello Jaime`

The example shows how `packages/api` referenced `packages/common` by importing it using `import { hello } from '@elts/common'` located at `packages/api/src/index.ts`

**`git checkout with-paths`** to see the setup which is not working when having nested folder (`@elts/common/testing/seed`) as import

there is a separate readme for the `with-paths` branch upon checkout
