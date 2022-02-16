<h1 align="center">React Native Hashing</h2>

<p align="center">
  <a href="https://www.npmjs.com/package/react-native-hashing"><img src="https://img.shields.io/npm/dm/react-native-hashing.svg?style=flat-square" alt="NPM downloads"></a>
  <a href="https://www.npmjs.com/package/react-native-hashing"><img src="https://img.shields.io/npm/v/react-native-hashing.svg?style=flat-square" alt="NPM version"></a>
  <a href="/LICENSE"><img src="https://img.shields.io/npm/l/react-native-hashing.svg?style=flat-square" alt="License"></a>
</p>

A hashing library for react native written in C++

## Installation

```sh
npm install react-native-hashing
```

or

```sh
yarn add react-native-hashing
```

## Usage

```js
import { sha256, md5 } from "react-native-hashing";

// ...

const result = sha256('Hello world');

or

const result = md5('Hello world');
```

## Acknowledgements

Big thanks to Stephan Brumme for the C++ implementation of the hashing algorithms. [Link to his library](https://github.com/stbrumme/hash-library)

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
