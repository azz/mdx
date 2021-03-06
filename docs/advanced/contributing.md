# Contributing

:pray: Thanks in advance for your contribution!

To get started, after cloning the repo:

```
npm i
npm t
```

## Project structure

MDX is a monorepo that uses [lerna][].

- All packages are found in `./packages`
- All documentation is found in `./docs` and can be viewed with `npm run docs -- -o`
- There's an `./examples` directory where examples for different tools and frameworks

## Releases

In order to release a new version you can follow these steps:

- Draft a release for the next version (vX.X.X)
- Release a prerelease
  - `lerna publish`
  - Select prepatch/preminor/premajor
  - Sanity check in a project or two with the prerelease
- `lerna publish`
- Publish release on GitHub

[lerna]: https://lernajs.io
