# vite-config-aspida

aspida & openapi2aspida for Vite.

example: <https://github.com/egahika-sandbox/firebase-vite>

## Install

```bash
yarn add -D vite-config-aspida aspida
```

```ts
// vite.config.ts
import ViteAspida from 'vite-plugin-aspida'

export default {
  plugins: [
    ViteAspida(),
  ],
}
```

### input swagger file

```ts
// vite.config.ts
import ViteAspida from 'vite-plugin-aspida'

export default {
  plugins: [
    ViteAspida({ input: 'https://petstore.swagger.io/v2/swagger.json' }),
  ],
}
```
