# Unreleased
## Features
## Bug Fixes
## BREAKING CHANGES
## Others

# 0.7.1
## Others
* [#169](https://github.com/epaew/react-liff/pull/169) Update .eslintrc to use `@epaew/eslint-config` and fix ESLint errors.
* [#186](https://github.com/epaew/react-liff/pull/186) Refactoring: Introduce the new jsx transform.
* [#191](https://github.com/epaew/react-liff/pull/191) Started supporting `@line/liff@2.6`.

# 0.7.0
## Others
* [#167](https://github.com/epaew/react-liff/pull/167) Started supporting `react@16.14` `react@17.0` and `@line/liff@2.5`.

# 0.6.2
## Bug Fixes
* [#120](https://github.com/epaew/react-liff/pull/120) Get compatible w/ `@line/liff@2.4.1`.

# 0.6.1
## Bug Fixes
* [#113](https://github.com/epaew/react-liff/pull/113) Fixup the version range of `@line/liff` dependency.

# 0.6.0
## Bug Fixes
* [#107](https://github.com/epaew/react-liff/pull/107) Fixup type error with `@line/liff@2.4.0`.

## BREAKING CHANGES
* [#109](https://github.com/epaew/react-liff/pull/109) Rename `loggedIn` in LiffContext to `isLoggedIn`.

# 0.5.0
## Features
* [#45](https://github.com/epaew/react-liff/pull/45) Add `@line/liff` as optionalDependency.

# 0.4.2
## Others
* [#23](https://github.com/epaew/react-liff/pull/23) Change the module specification of tsconfig.json: from es2015 to commonjs.

# 0.4.1
## Others
* [#21](https://github.com/epaew/react-liff/pull/21) Change the target version of tsconfig.json: from ES2019 to ES2015.

# 0.4.0
## Features
* [#14](https://github.com/epaew/react-liff/pull/14) Update the stub implementation: make login state updatable.
* [#15](https://github.com/epaew/react-liff/pull/15) Add `loggedIn` state in LiffContext

# 0.3.0
## Features
* [#10](https://github.com/epaew/react-liff/pull/10)
  * Add new export `createLiffContext<T>()`, for TypeScript user, now you can overload the context type definition of liff object.
  * Define propTypes of `LiffProvider`, for non-TypeScript user.
## Others
* [#10](https://github.com/epaew/react-liff/pull/10)
  * Split the codes.
  * Remove optional dependency of `liff-type`.

# 0.2.0
## Features
* [#2](https://github.com/epaew/react-liff/pull/2) Add export `LiffConsumer`
* [#4](https://github.com/epaew/react-liff/pull/4) Add flag to check "is liff ready?"
## Others
* [#2](https://github.com/epaew/react-liff/pull/2) Move dependency of package `liff-type` from peer to optional
* [#4](https://github.com/epaew/react-liff/pull/4) Add tests
* [#5](https://github.com/epaew/react-liff/pull/5) Update README.md and add CHANGELOG.md

# 0.1.0
Initial release
