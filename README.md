# Linters config

> ** Archived: **
> stylelint config moved to <https://github.com/massimo-cassandro/stylelint-config>
> eslint config moved to <https://github.com/massimo-cassandro/eslint-config>

In `package.json`

```json
{
  "stylelint": {
    "extends": "@massimo-cassandro/linters-config/stylelintrc.js",
    "ignoreFiles": [
      "build/**/*.css"
    ],
    "rules": {}
  },
   "eslintConfig": {
    "extends": "./node_modules/@massimo-cassandro/linters-config/eslintrc.js",
    "ignorePatterns": [],
    "rules": {}
  }
}
```
