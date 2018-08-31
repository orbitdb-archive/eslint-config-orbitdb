# eslint-config-orbitdb

The eslint configuration used for orbit-db projects

## Using in your project

Install [eslint](https://eslint.org), the [OrbitDB linting rules](https://github.com/orbitdb/eslint-config-orbitdb) and add them to your project's dev dependencies:
```
npm install eslint @orbitdb/eslint-config-orbitdb --save-dev
```

Create `.eslintrc` file in your project's root directory:
```
touch .eslintrc
```

Edit `.eslintrc` to contain:
```json
{
  "extends": ["@orbitdb/eslint-config-orbitdb"]
}
```

Add a `lint` script to your project's `package.json`:
```json
"scripts": {
  "lint": "./node_modules/eslint/bin/eslint.js src/"
}
```

*Note: The lint script needs to call "./node_modules/eslint/bin/eslint.js" instead of "eslint" as users may have global installation of eslint which uses *only* the plugins installed globally and will not find @orbitdb/eslint-config-orbitdb module (nor its dependencies). See more info [here](https://github.com/eslint/eslint/issues/6732) or [here](https://github.com/eslint/eslint/issues/1238).*

Finally, to test it all works, run the linter:
```
npm run lint
```

## Contribute

Please feel free to file an issue, send your PR or just say "hi 👋 "! Before you start working on something, it'd be good to talk and make sure nobody else is working on it. You can reach us on IRC #orbitdb on Freenode, or in the comments of the issues section.

We also have regular community calls, which we announce in the issues in the @orbitdb welcome repository. Join us!

If you want to code but don't know where to start, check out the issues labelled "help wanted".

For specific guidelines for contributing to this repository, check out the Contributing guide. For more on contributing to OrbitDB in general, take a look at the orbitdb welcome repository. Please note that all interactions in @orbitdb fall under our Code of Conduct.

## License

MIT © 2018 Thiago Delgado
