

# Using svelte-query with Jest




## Get started

Install the dependencies...

```bash
cd jest-svelte-query
yarn
```

...then start Jest

```bash
yarn test:watch
```

...output is 

```
 ● Test suite failed to run

    Cannot find module '../../src/methods/node.js' from 'node_modules/@sveltestack/svelte-query/dist/index.js'

    Require stack:
      node_modules/@sveltestack/svelte-query/dist/index.js
      src/App.test.ts

      at Resolver.resolveModule (node_modules/jest-resolve/build/resolver.js:311:11)

```