# base-lib

For building JavaScript libs.

## Usage

```
git clone https://github.com/richard-cargill/base-lib.git new-lib
cd new-lib
npm install
npm run dev
```

## Api
### Development 
Watches JavaScript files and runs tests in watch mode.

```
npm run dev
```

### Production
Builds production files

```
npm run build
```

### Linting
Lints and fixes JavaScript issues
```
npm run lint
```


After cloning you should update the `name`, `main` and `module` properties in the `package.json` file.

## Uses
- [Rollup.js](https://rollupjs.org) - to bundle to commonjs, esmodules and umd
- [XO](https://github.com/xojs/xo) - for linting
- [AVA](https://github.com/avajs/ava) - for testing
- [Babel](https://babeljs.io/) - for JavaScript transpilation



## License

[MIT](LICENSE).
