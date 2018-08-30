# eslint-config-orbitdb

The eslint configuration used for orbit-db projects

## Installation

Our default export contains all of our ESLint rules.

**Requirements**

* `eslint`
* `eslint-plugin-import`
* `eslint-plugin-standard`
* `eslint-plugin-promise`
* `eslint-plugin-node`
* `eslint-config-standard`

If you use yarn, run `npm info "@orbitdb/eslint-config-orbitdb@latest" peerDependencies` to list the peer dependencies and versions, then run `yarn add --dev <dependency>@<version>` for each listed peer dependency. See below for npm instructions.

1. Install the correct versions of each package, which are listed by the command:

  ```sh
  npm info "@orbitdb/eslint-config-orbitdb@latest" peerDependencies
  ```

  Linux/OSX users can run:

  ```sh
  (
    export PKG=@orbitdb/eslint-config-orbitdb;
    npm info "$PKG@latest" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs yarn add --dev "$PKG@latest"
  )
  ```


2. Add `"extends": "@orbitdb/eslint-config-orbitdb"` to your .eslintrc

## Details

To setup `eslint` for a new project, please refer to the getting started page [here](https://eslint.org/docs/user-guide/getting-started#local-installation-and-usage), install it as a `devDependency`, pick a config file format (.eslintrc, YAML, json) and follow the rest of the instructions there :)

## Contribute

Please feel free to file an issue, send your PR or just say "hi 👋 "! Before you start working on something, it'd be good to talk and make sure nobody else is working on it. You can reach us on IRC #orbitdb on Freenode, or in the comments of the issues section.

We also have regular community calls, which we announce in the issues in the @orbitdb welcome repository. Join us!

If you want to code but don't know where to start, check out the issues labelled "help wanted".

For specific guidelines for contributing to this repository, check out the Contributing guide. For more on contributing to OrbitDB in general, take a look at the orbitdb welcome repository. Please note that all interactions in @orbitdb fall under our Code of Conduct.

## License

MIT © 2018 Thiago Delgado
