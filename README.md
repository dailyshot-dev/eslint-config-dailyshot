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

## License

MIT
