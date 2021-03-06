# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="3.2.2"></a>
## [3.2.2](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v3.2.1...v3.2.2) (2019-02-04)



<a name="3.2.1"></a>
## [3.2.1](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v3.2.0...v3.2.1) (2019-01-31)



<a name="3.2.0"></a>
# [3.2.0](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v3.1.0...v3.2.0) (2018-11-23)


### Features

* remove dependency on ramda ([471ae16](https://github.com/vsimko/node-graphql-constraint-lambda/commit/471ae16))



<a name="3.1.0"></a>
# [3.1.0](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v3.0.0...v3.1.0) (2018-11-21)


### Features

* add function createValidationCallback in src/validators.js ([1ea5747](https://github.com/vsimko/node-graphql-constraint-lambda/commit/1ea5747))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v2.0.3...v3.0.0) (2018-11-21)


### improvement

* rename function `getSchemaDSL` into `getSDL` ([fe67663](https://github.com/vsimko/node-graphql-constraint-lambda/commit/fe67663))


### BREAKING CHANGES

* Clients should change to `getSDL()` in their code.



<a name="2.0.3"></a>
## [2.0.3](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v2.0.1...v2.0.3) (2018-11-20)


### Bug Fixes

* added exported functions from validators.js to index.js ([b48be3a](https://github.com/vsimko/node-graphql-constraint-lambda/commit/b48be3a))
* problem with empty string in maxLength and minLength ([039716d](https://github.com/vsimko/node-graphql-constraint-lambda/commit/039716d))



<a name="2.0.2"></a>
## [2.0.2](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v2.0.1...v2.0.2) (2018-11-20)


### Bug Fixes

* problem with empty string in maxLength and minLength ([039716d](https://github.com/vsimko/node-graphql-constraint-lambda/commit/039716d))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v2.0.0...v2.0.1) (2018-11-20)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v1.0.0...v2.0.0) (2018-11-20)


### Features

* validators and messages can be changed by user ([d910823](https://github.com/vsimko/node-graphql-constraint-lambda/commit/d910823))
* we now use callbacks for validation and error messages ([ec1c192](https://github.com/vsimko/node-graphql-constraint-lambda/commit/ec1c192))


### BREAKING CHANGES

* new functions are exported in `src/validators.js`
* validators are refactored into separate file



<a name="1.0.0"></a>
# [1.0.0](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v0.3.0...v1.0.0) (2018-11-19)


### Chores

* wrap constraint directive class in `module.exports` ([71a2ac9](https://github.com/vsimko/node-graphql-constraint-lambda/commit/71a2ac9))


### BREAKING CHANGES

* the constraint directive is now wrapped  in
`module.exports` as `{constraint}` instead of just returning the
whole class.



<a name="0.3.0"></a>
# [0.3.0](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v0.2.2...v0.3.0) (2018-11-13)


### Features

* add getSchemaDSL method ([c66917c](https://github.com/vsimko/node-graphql-constraint-lambda/commit/c66917c))



<a name="0.2.2"></a>
## [0.2.2](https://github.com/vsimko/node-graphql-constraint-lambda/compare/v0.2.1...v0.2.2) (2018-11-13)



<a name="0.2.1"></a>
## 0.2.1 (2018-11-13)


### Bug Fixes

* primary entry point `main` in packate.json ([97c872b](https://github.com/vsimko/node-graphql-constraint-lambda/commit/97c872b))



<a name="0.1.1"></a>
## 0.1.1 (2018-06-20)
