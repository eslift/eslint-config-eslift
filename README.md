# ESLint Config

ESLint configuration used for TypeScript projects.

## Install

```
$ yarn add --dev eslint-config-tsx
```

## Usage

Modify your eslint config as follows.

### TypeScript (with or without React)

Add `"extends": "tsx"` to your eslint config. For example, if your eslint config is in package.json, it would look like this:

```json
{
  "eslintConfig": {
    "extends": "tsx"
  }
}
```

### React Native

Add `"extends": "tsx/react-native"` to your eslint config. For example, if your eslint config is in package.json, it would look like this:

```json
{
  "eslintConfig": {
    "extends": "tsx/react-native"
  }
}
```
