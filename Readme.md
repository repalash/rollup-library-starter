# Rollup library starter

A starter repo for creating libraries for browsers using TypeScript and Rollup.

## Usage

To start, click the `Use Template` button on Github (or download the zip file and run `git init`). Then clone the repo and install dependencies with `npm install`.

To create a new library, change the name, description, author, copyright notice, license and other properties in `package.json`, `LICENSE` and `README`.

Create source files in `src` and export them in `index.ts`.

To test the library, make tests/examples in `examples` and include them in `index.html`. Examples should access the builds from `../dist` and not the source files from the `src` directory.

To use the library locally, make a new project and include it in the `package.json` dependencies using `file:./../../path/to/this/repo`.

When pushing to Github on the master or main branch, the docs will be build using Github actions and pushed to Github pages. For this, Github pages must be enabled in the Github repository settings.

Build for development (Build and watch): 
```bash
npm run dev
```
To serve the local build and examples, run 
```bash
npm run serve
```


Build for production (Build): 
```bash
npm run build
```

Build docs
```bash
npm run docs
```

View docs locally
```bash
npm run serve-docs
```

Publish to npm 
```bash
npm run new:publish
```

Generate a packed `.tgz`
```bash
npm run new:pack
```

Generate a new version
```bash
npm version
```

## License
MIT

## References
Generated with [rollup-library-starter](https://github.com/repalash/rollup-library-starter)
