# Artifact Payments

Payments solution for Artefact server

## Overview

The Payments solution seeks to provide a way to:
- Accept Paypal, credit card and Bitcoin Payments
- Make individual transfers via Dev Coins (virtual currency)
- Bounty functionality 

See `todo` folder for todo list and move overview of solution specs.

### Install

- clone this repo
- `yarn install` - install dependencies 

## Development environment

Please see the `docs` folder, in particular `docs/env-setup/library-dev.md` 
which describes the full development environment, how it was configured etc.

### Run Test or Test suite

`npm test`

Write tests using either:
- [ava](https://github.com/ava/ava)
- or [mocha-test-dsl](https://www.npmjs.com/package/mocha-test-dsl) if you prefer using [mocha]

Note that Ava can use `spec` syntax via [ava-spec]()

- Ava testing framework: [ava](https://github.com/ava/ava)
- BDD: [ava-spec](https://www.npmjs.com/package/ava-spec)
- test doubles: [testdouble.js]()

## License

MIT