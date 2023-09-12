## Scaffolding commands

```shell
npm create vite@latest
```

```shell
npm create vue@latest
```

```shell
npx nuxi@latest init --force .
```

```shell
npx create-next-app@latest
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

## Tailwind CSS

```shell
npm i -D tailwindcss
npx tailwindcss init
```

```shell
npm i -D prettier-plugin-tailwindcss
```

`prettier.config.js`

```javascript
  plugins: ['prettier-plugin-tailwindcss'],
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
