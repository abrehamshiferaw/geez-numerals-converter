# Ge'ez Numerals Converter

A lightweight JavaScript/npm library for converting numbers between **Arabic numerals and Ge'ez numerals**. Build Ethiopian, Amharic, multilingual, educational, and cultural software with a simple API.

[![npm version](https://img.shields.io/npm/v/geez-numerals-converter)](https://www.npmjs.com/package/geez-numerals-converter) [![license](https://img.shields.io/npm/l/geez-numerals-converter)](LICENSE)

<p><a href="https://github.com/sponsors/abrehamshiferaw">💖 Sponsor Ge'ez Numerals Converter</a></p>

## Why support this project?

Sponsorship helps maintain the npm package, improve conversion accuracy, expand tests and documentation, and support open-source Ethiopian language and cultural technology.

## Features

- Bidirectional Arabic/English ↔ Ge'ez numeral conversion
- Lightweight and fast for browser and Node.js applications
- Simple JavaScript API with TypeScript-friendly usage
- Useful for Ethiopian calendars, localization, education, and cultural software

## Installation

```bash
npm install geez-numerals-converter
```

## Usage

```javascript
const geezConverter = require('geez-numerals-converter');

const geezNumber = geezConverter.intToGeez(311);
console.log(geezNumber);

const integer = geezConverter.geezToInt('፫፻፲፩');
console.log(integer);
```

## API

### `intToGeez(number)`

Converts an integer to its Ge'ez numeral representation.

### `geezToInt(geezNumeral)`

Converts a Ge'ez numeral string to an integer.

## Contributing

Bug reports, tests, documentation improvements, and pull requests are welcome. Please [star the project](https://github.com/abrehamshiferaw/geez-numerals-converter), open an issue, or [sponsor Ge'ez Numerals Converter](https://github.com/sponsors/abrehamshiferaw).

## License

MIT License. See [LICENSE](LICENSE).
