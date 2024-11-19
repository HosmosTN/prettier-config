# @hosmostn/prettier-config [![npm](https://img.shields.io/npm/v/@hosmostn/prettier-config?style=for-the-badge)](https://www.npmjs.com/package/@hosmostn/prettier-config)

This is my preferred prettier configuration as an installable node package.

## Usage

Installation f. ex. using `npm`:

```
npm install --save-dev @hosmostn/prettier-config
```

Add to `package.json`:

```
{
  // ...
  "prettier": "@hosmostn/prettier-config"
}
```

To extend or override the configuration, use `.prettierrc.js`:

```
module.exports = {
	...require("@hosmostn/prettier-config"),
	semi: false,
};
```
