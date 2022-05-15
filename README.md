# Starter React Tailwind

Starter for react, tailwindcss toolchain


## Overview

```
$ git clone https://github.com/manojnakp/starter-rtw.git
$ cd starter-rtw
$ npm install
```

Running above commands in the terminal sets up react-tailwind toolchain. The
starter includes:

- [react](https://www.npmjs.com/package/react), [react-dom](https://www.npmjs.com/package/react-dom) and [tailwindcss](https://www.npmjs.com/package/tailwindcss) as dependencies.
- [babel](https://babeljs.io), [postcss](https://postcss.org), [eslint](https://eslint.org) and [webpack](https://webpack.js.org) as development dependencies.
- Eslint is configured with airbnb style guide for react.


## npm scripts

### `start`
Alias for `npm run watch`

### `build`

```
$ npm run build
```

Build `src/*` to `dist/*` using webpack and make bundles of js and css files.

### `build:css`

```
$ npm run build:css
```

Based on the classnames used in the pages, generate `dist/tailwind.css` using tailwindcss cli.

### `clear:dist`

```
$ npm run clear:dist
```

Remove older builds already present in `dist/` directory

### `lint`

```
$ npm run lint
```

Lint `src/*.js` and `src/*.jsx` using eslint.

### `lint:fix`

```
$ npm run lint:fix
```

Fix automatically fixable problems using eslint. Used for ease of development.

### `watch:css`

```
$ npm run watch:css
```

Run the tailwindcss cli and compile `dist/tailwind.css`. Watch source
directory for any changes.

### `watch`

```
$ npm run watch
```

Bundle the modules and serve them on a dev-server using webpack. Watch the source files for changes and reload automatically.


## Future plans
- [ ] To add `test` with jest or mocha
