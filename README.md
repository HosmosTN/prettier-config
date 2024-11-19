# @HosmosTN/prettier-config [![npm](https://img.shields.io/npm/v/@HosmosTN/prettier-config?style=for-the-badge)](https://www.npmjs.com/package/@HosmosTN/prettier-config)

This is my preferred prettier configuration as an installable node package.

## Usage

Installation f. ex. using `npm`:

```
npm install --save-dev @HosmosTN/prettier-config
```

Add to `package.json`:

```
{
  // ...
  "prettier": "@HosmosTN/prettier-config"
}
```

To extend or override the configuration, use `.prettierrc.js`:

```
module.exports = {
	...require("@HosmosTN/prettier-config"),
	semi: false,
};
```
