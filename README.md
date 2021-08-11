# webookrepo-common
A TypeScript package used in the webookrepo project.

## Dependencies

You must have already installed and configured in your workspace:

* [Node.js](https://nodejs.org/en/)
* [Yarn](https://yarnpkg.com/getting-started)

## Installation

For local development, you must install the local dependencies, running the command:
```bash
yarn install
```
## Scripts

The building, cleaning and publishing features of this package are implemented in the `package.json`, via the following scripts:

### Build
Generates the Javascript code via TypeScript compileer `tsc`:
```bash
yarn build
```

### Clean
Removes the build output:
```bash
yarn clean
```
### Publish
Publishes the package codebase to the to NPM Registry, given the appopriate credentials.
```bash
yarn pub
```
The result of the publishing script can be inspected in the respective [npmjs page](https://www.npmjs.com/package/@webookrepo/commonp).
