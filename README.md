# offline-js-playground
:neckbeard: Rapid JS ES6 development and testing, without UI.

## Features
- [X] Babel ES6 transpiling
- [X] Babel [stage-2](https://babeljs.io/docs/plugins/preset-stage-2/) preset
- [X] Testing by [Mocha](https://mochajs.org/) and [Istambul](https://istanbul.js.org)
- [X] Assertions by [Chai](http://chaijs.com)

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
