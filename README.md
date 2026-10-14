# Vite+ sample

A small TypeScript application created with the built-in Vite+ application template.

Use Node.js 24.11+ (24.x) with npm. Other supported Node.js versions are listed in `package.json`.

## Development

```sh
npm install
npm run dev
```

## Validation and production

```sh
npm run check
npm run build
npm run preview
```

`npm run check` checks formatting, linting, and types. The build script runs TypeScript and creates the production bundle in `dist/`.

The starter does not include tests. Once test files are added, run them with `npx vp test`.

For reproducible installs in CI, use `npm ci`.
