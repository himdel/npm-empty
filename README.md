# npm-empty
empty npm package (for overrides)

Example usage:

`package.json`:

```
  ...
  "overrides": {
    "node-sass": "himdel/npm-empty",
  },
  ...
```

because npm 8+ provides the [`overrides`](https://docs.npmjs.com/cli/v8/configuring-npm/package-json#overrides) feature, and allows overriding with a different version, a http link, a git link or a github repo, but not a differently named npm package, as far as I can tell.
