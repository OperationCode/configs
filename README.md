# eslint-plugin-custom-rules

Custom ESLint Rules for [Operation Code](https://github.com/operationCode/) Projects.

## Installation

```bash
yarn add --dev @operation_code/eslint-plugin-custom-rules
```

## Usage

Add `@operation_code/custom-rules` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
  "plugins": ["@operation_code/custom-rules"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "@operation_code/custom-rules/proptype-definition-above-fn": "error"
  }
}
```

## Supported Rules

- `proptype-definition-above-fn`
