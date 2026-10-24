# @x12i/xontext-docs usage example

Xontext docs knowledge SDK — install as a devDependency only. Catalog, use cases, and markdown packs for humans and agents.

This consuming application demonstrates **list the bundled guides and read a use case** using the published npm package, pinned to `1.0.1`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

This is a documentation knowledge SDK. It is installed as a development dependency. The example lists its books and use cases, then reads the first available use-case guide from the package.

## When to use the package

- Install @x12i/xontext-docs as a development dependency so the product guides and package index are available to developers and coding assistants.
- Read the bundled xontext documentation or use-case catalog without requiring a live documentation website.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/xontext-docs)
- [Implementation monorepo](https://github.com/x12i/xontext)
- [Reviewed package source](https://github.com/x12i/xontext/tree/7383f05fda8ece00db443a427dea980016fd1ebf/xontext-docs/packages/xontext-docs)

The current source snapshot has a different manifest version from the pinned npm dependency. This example is validated against the installed npm release.

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
