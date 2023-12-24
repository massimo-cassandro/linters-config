# Linters config


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
