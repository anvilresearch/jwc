# JWC (_trust/jwc_) 

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![Build Status](https://travis-ci.org/anvilresearch/jwc.svg?branch=master)](https://travis-ci.org/anvilresearch/jwc)
[![codecov](https://codecov.io/gh/anvilresearch/jwc/branch/master/graph/badge.svg)](https://codecov.io/gh/anvilresearch/jwc)

> JSON Web Certificate for JavaScript

This package implements [JWC][jwc] for use in JavaScript applications.

Certificates are presented as secure [JWTs][jwt], the underlying cryptography for which is provided by [W3C Web Cryptography API][w3c-webcrypto], available natively in browsers and [via npm][node-webcrypto] in Node.js.

[jwc]: https://tools.ietf.org/html/draft-smith-jose-json-web-certificate-00
[jwd]: https://tools.ietf.org/html/draft-smith-jose-json-web-document-01
[jwt]: https://tools.ietf.org/html/rfc7519
[jws]: https://tools.ietf.org/html/rfc7515
[jwe]: https://tools.ietf.org/html/rfc7516
[jwa]: https://tools.ietf.org/html/rfc7518
[jwk]: https://tools.ietf.org/html/rfc7517
[jwkset]: https://tools.ietf.org/html/rfc7517#section-5
[w3c-webcrypto]: https://www.w3.org/TR/WebCryptoAPI/
[node-webcrypto]: https://www.npmjs.com/package/@trust/webcrypto
[json-schema]: http://json-schema.org/
[json-doc]: https://www.npmjs.com/package/@trust/json-document

## Table of Contents

- [Security](#security)
- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Develop](#develop)
- [API](#api)
- [Contribute](#contribute)
- [Contributors](#contributors)
- [License](#license)

## Security

TBD

## Background

TBD

## Develop

## Install

```bash
$ npm install @trust/jwc --save
```

## Usage

### Node.js

```javascript
const { JWC } = require('@trust/jwc')
```

### Browser

TBD

## Develop

### Install

```bash
$ git clone git@github.com:anvilresearch/jwc.git
$ cd jwc
$ npm install
```

### Test

```bash
$ npm test      // Node.js
$ npm run karma // Karma (browser)
```

## API

## Contribute

### Issues

* please file [issues](https://github.com/anvilresearch/jwc/issues) :)
* for bug reports, include relevant details such as platform, version, relevant data, and stack traces
* be sure to check for existing issues before opening new ones
* read the documentation before asking questions
* it's strongly recommended to open an issue before hacking and submitting a PR
* we reserve the right to close an issue for excessive bikeshedding

### Pull requests

#### Policy

* we're not presently accepting *unsolicited* pull requests
* create an issue to discuss proposed features before submitting a pull request
* create an issue to propose changes of code style or introduce new tooling
* ensure your work is harmonious with the overall direction of the project
* ensure your work does not duplicate existing effort
* keep the scope compact; avoid PRs with more than one feature or fix
* code review with maintainers is required before any merging of pull requests
* new code must respect the style guide and overall architecture of the project
* be prepared to defend your work

#### Style guide

* [Conventional Changelog](https://github.com/bcoe/conventional-changelog-standard/blob/master/convention.md)
* [EditorConfig](http://editorconfig.org)
* ES6
* Standard JavaScript
* jsdocs

#### Code reviews

* required before merging PRs
* reviewers SHOULD run the code under review

### Collaborating

#### Weekly project meeting

* Thursdays from 1:00 PM to 2:00 Eastern US time at [TBD]
* Join remotely with Google Hangouts

#### Pair programming

* Required for new contributors
* Work directly with one or more members of the core development team

### Code of conduct

* @trust/jwc follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.

### Contributors

* Christian Smith [@christiansmith](https://github.com/christiansmith)
* Greg Linklater [@EternalDeiwos](https://github.com/EternalDeiwos)
* Dmitri Zagidulin [@dmitrizagidulin](https://github.com/dmitrizagidulin)
* Ioan Budea [@johnny90](https://github.com/johnny90)

## License

MIT © 2017 MIT Connection Science
