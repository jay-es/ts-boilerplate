## Scaffolding commands

```shell
npm create vite@latest
```

```shell
npm create vue@latest
```

```shell
npx nuxi@latest init --force .
pnpm dlx nuxi@latest init
bunx nuxi@latest init
```

```shell
npm create next-app@latest
npx create-next-app@latest
```

## TSConfig bases

```shell
npm i -D @tsconfig/strictest
```

`tsconfig.json`

```jsonc
  "extends": "@tsconfig/strictest/tsconfig",

  "extends": [
    "@tsconfig/strictest/tsconfig",
    ...
  ],
```

## ESLint

```shell
npx eslint --init
```

```shell
npm i -D @typescript-eslint/eslint-plugin @typescript-eslint/parser
npm i -D eslint-plugin-simple-import-sort
```

## Prettier

```shell
npm i -D prettier eslint-config-prettier
```

## Biome

```shell
npm install --save-dev --save-exact @biomejs/biome
npx @biomejs/biome init
```

```json
  "formatter": {
    "indentStyle": "space"
  },
```

## Tailwind CSS

```shell
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

```shell
npm i -D prettier-plugin-tailwindcss
```

`prettier.config.js`

```javascript
  plugins: ['prettier-plugin-tailwindcss'],
```

### Tailwind CSS Typography

```shell
npm install -D @tailwindcss/typography
```

`tailwind.config.js`

```javascript
  plugins: [require('@tailwindcss/typography')],
```

### daisyUI

```shell
npm i -D daisyui@latest
```

`tailwind.config.js`

```javascript
  plugins: [require("daisyui")],
```

## Testing

```shell
npm i -D vitest vite-tsconfig-paths
```

### Vue

```shell
npm i -D @vue/test-utils
```

### React

```shell
npm i -D jsdom @testing-library/jest-dom @testing-library/react @testing-library/user-event
npm i -D eslint-plugin-jest-dom eslint-plugin-testing-library
```

## Husky + lint-staged

```shell
npm i -D husky lint-staged
```
