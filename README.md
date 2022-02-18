# i18next-webpack-locale-sync

Syncs i18next translations files against a master locale.

## Install

```console
npm install i18next-webpack-locale-sync --save-dev
```

**webpack.config.js**

```js
const i18nextLocaleSync = require('json-csv-sync').default

new i18nextLocaleSync({ masterLocale: 'en' }),

```

## Options

A CSV with the combined keys and values can be produced:

```js
new i18nextLocaleSync({ masterLocale: 'en', produceCSV: true }),

```
