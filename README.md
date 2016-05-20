MTW
===
Mind the Word - Chrome Extension for learning new languages
-----------------------------------------------------------

This package uses `jspm` to manage modules for javascript.

Run the following commands in your cloned directory.

```shell
npm install -g jspm gulp gulp-cli jsdoc
npm install
jspm install
```

Install the extension in Chrome as an unpacked extension.

**To start the chrome application**, run

```shell
gulp watch
```

**To generate docs**, run

```shell
jsdoc -c config.json
```

Content Script: `mtw.js`

Event Page (background script): `eventPage.js`
