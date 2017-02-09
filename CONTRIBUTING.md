### RFCs

See the [README](./README) page for instructions on working with RFCs.

### Consistent format

To ensure that every RFC has a consistent markdown format we require some packages are installed.

### Requirements

Yarn is required to install the  [remark](https://github.com/wooorm/remark-lint) markdown linting package.

-   [Yarn](https://yarnpkg.com/en/docs/install)

### Setup

Use Yarn to install the required packages.

```bash
yarn install
```

### Testing

> Checkout the [remark editor integrations](https://github.com/wooorm/remark-lint#editor-integrations) as well.

```bash
yarn test
```

### Pull Request

Once you've made your pull request (PR) we use [CircleCI](http://circleci.com/) to run this same testing script.  All PRs are required to pass this CI run in order to be merged.
