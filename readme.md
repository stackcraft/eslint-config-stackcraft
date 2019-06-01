# StackCraft ESLint Config

Shareable code style and best practice for StackCraft projects

## Installation

Client-side project:

```
yarn add --dev eslint @stackcraft/eslint-config eslint-plugin-fp eslint-plugin-import eslint-plugin-jest eslint-plugin-lodash-fp eslint-plugin-promise eslint-plugin-security eslint-plugin-vue
```

Server-side project:

```
yarn add --dev eslint @stackcraft/eslint-config eslint-plugin-fp eslint-plugin-import eslint-plugin-jest eslint-plugin-lodash-fp eslint-plugin-promise eslint-plugin-security
```

# Usage

Add this config to `.eslintrc`

Client-side project:

```
{
  "extends": [
    "@stackcraft/eslint-config/client",
  ]
}
```

Server-side project:

```
{
  "extends": [
    "@stackcraft/eslint-config/server",
  ]
}
```
