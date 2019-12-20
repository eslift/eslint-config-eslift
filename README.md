# ESLint Config

ESLint configuration used for TypeScript projects.

## Install

```
$ yarn add --dev eslint-config-tsx
```

## Usage

Modify `eslintConfig` in `package.json` as follows.

### TypeScript

```json
{
  "name": "cool-node-server",
  "eslintConfig": {
    "extends": "tsx"
  }
}
```

### TypeScript + React

```json
{
  "name": "awesome-react-website",
  "eslintConfig": {
    "extends": "tsx/react"
  }
}
```

### TypeScript + React Native

```json
{
  "name": "amazing-native-app",
  "eslintConfig": {
    "extends": "tsx/react-native"
  }
}
```
