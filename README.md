# ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```console
npm i -D eslint @alvinscheibe/eslint-config
```
Inside `.eslintrc.json`
```json
{
  "extends": [
    "@alvinscheibe/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```console
npm i -D eslint @alvinscheibe/eslint-config
```
Inside `.eslintrc.json`
```json
{
  "extends": "@alvinscheibe/eslint-config/react"
}
```

### Node.js

Install dependencies:
```console
npm i -D eslint @alvinscheibe/eslint-config
```
Inside `.eslintrc.json`
```json
{
  "extends": "@alvinscheibe/eslint-config/node"
}
```
