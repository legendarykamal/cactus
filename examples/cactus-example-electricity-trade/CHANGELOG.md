# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [1.1.0](https://github.com/hyperledger/cactus/compare/v1.0.0...v1.1.0) (2022-10-17)

### Bug Fixes

* **cactus-example-electricity-trade:** enable tsconfig strict flag an… ([f7e726c](https://github.com/hyperledger/cactus/commit/f7e726c2720ed21bc4a582f6c4f345d0b2c65af7)), closes [#2144](https://github.com/hyperledger/cactus/issues/2144)

### Code Refactoring

* **examples:** include sample apps in monorepo build ([51ac163](https://github.com/hyperledger/cactus/commit/51ac1630f53ca3ac881341c7f8847b6ae581b220))

### Features

* **sawtooth-ledger:** add single sawtooth test ledger image ([cd4c746](https://github.com/hyperledger/cactus/commit/cd4c7460f6e005ce56a0d79edea6f609756bf9d5)), closes [#2108](https://github.com/hyperledger/cactus/issues/2108) [#2030](https://github.com/hyperledger/cactus/issues/2030)
* **secret:** remove Validator/Verifier secret keys from repository ([59b4af4](https://github.com/hyperledger/cactus/commit/59b4af44835e2babafe398040a280ed23e9b490e))

### BREAKING CHANGES

* **examples:** building discounted-asset-trade app (or any future app that use indy validator)
                 requires Indy SDK to be installed on the build machine.

Closes: 2029

Signed-off-by: Michal Bajer <michal.bajer@fujitsu.com>
