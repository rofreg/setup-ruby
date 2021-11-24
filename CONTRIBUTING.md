# Contributing

## Installing dependencies

```bash
$ yarn install
```

`npm` doesn't install the correct dependencies for `eslint` so we use `yarn`.

## Regenerating dist/index.js

```bash
$ yarn run package
```

It is recommended to add this as a `git` `pre-commit` hook:

```bash
$ cp pre-commit .git/hooks/pre-commit
```

## Adding a new Ruby version

Add the new version in `ruby-builder-versions.js` and in `dist/index.js`. Then update the "Supported Versions" section of the README as needed.
