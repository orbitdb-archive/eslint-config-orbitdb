# eslint-config-orbitdb

The eslint configuration used for orbit-db projects

## Usage

Our default export contains all of our ESLint rules.

**Requirements**

* `eslint-plugin-import`
* `eslint-plugin-standard`
* `eslint-plugin-promise`
* `eslint-plugin-node`
* `eslint-config-standard`
* `eslint`

If you use yarn, run `npm info "@orbitdb/eslint-config-orbitdb@latest" peerDependencies` to list the peer dependencies and versions, then run `yarn add --dev <dependency>@<version>` for each listed peer dependency. See below for npm instructions.

1. Install the correct versions of each package, which are listed by the command:

  ```sh
  npm info "@orbitdb/eslint-config-orbitdb@latest" peerDependencies
  ```

  Linux/OSX users can run

  ```sh
  (
    export PKG=@orbitdb/eslint-config-orbitdb;
    npm info "$PKG@latest" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs yarn add --dev "$PKG@latest"
  )
  ```


2. Add `"extends": "@orbitdb/eslint-config-orbitdb"` to your .eslintrc
