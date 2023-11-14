# eslint-config-dailyshot

## Install

```bash
npx install-peerdeps --dev eslint-config-dailyshot
```

## Usage

In your .eslintrc.js:

```javascript
module.exports = {
  extends: ['dailyshot'],
  parserOptions: {
    project: './tsconfig.json',
  },
};
```

In your .prettierrc.js:

```javascript
module.exports = require('eslint-config-dailyshot/.prettierrc.js');
```

In your .vscode/settings.json:


```javascript
{
  "typescript.tsdk": "node_modules/typescript/lib",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": true,
    "source.fixAll": true
  },
  "[javascript]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[typescript]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[typescriptreact]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[jsonc]": {
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact"]
}
```


## License

MIT
