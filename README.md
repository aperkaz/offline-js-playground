# offline-js-playground
[![Build Status](https://travis-ci.org/aperkaz/offline-js-playground.svg?branch=master)](https://travis-ci.org/aperkaz/offline-js-playground)

[![Code Climate](https://codeclimate.com/github/ooade/NextSimpleStarter/badges/gpa.svg)](https://codeclimate.com/github/ooade/NextSimpleStarter) <br />
:neckbeard: Rapid JS ES6 development and testing, without UI.

## Features
- [X] Babel ES6 transpiling
- [X] Babel [stage-2](https://babeljs.io/docs/plugins/preset-stage-2/) preset
- [X] Testing by [Mocha](https://mochajs.org/)
- [X] Assertions by [Chai](http://chaijs.com)
- [X] ESLinting by [ESLint](http://eslint.org/)
- [X] Test coverage by [Istambul](https://istanbul.js.org)
- [X] Travis CI integration
- [X] Coveralls integration

## Scripts
| Name          | Function        |
| ------------- |:---------------:|
| `clean`       | Clean `/lib`    |
| `test`        | Execute test cases    |
| `test:watch`  | Watch `test`     |
| `cover`       | Yeld coverage    |
| `lint`        | Lint JS errors   |
| `build`       | Transpile ES6 to ES5  |
| `prepublish`  | Exec. `clean`, `lint`, `test` and `build`     |

## License
MIT © [Alain Perkaz](https://aperkaz.github.io)
