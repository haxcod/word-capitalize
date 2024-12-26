# Word-Capitalize

`word-capitalize` is a lightweight utility package that capitalizes the first letter of every word in a given string. Perfect for formatting titles, sentences, and other text in JavaScript or Node.js applications.

---

## Features

- **Capitalizes Words:** Automatically capitalizes the first letter of every word in a string.
- **Whitespace Handling:** Cleans up excess whitespace for cleaner results.
- **Lightweight:** Minimal and efficient.
- **Compatible:** Works seamlessly in both JavaScript and Node.js projects.

---

## Installation

Install the package via npm:

```bash
npm install word-capitalize
```

---

## Usage

Here is an example of how to use `word-capitalize`:

### Importing the Package

```javascript
// ES Module
import capitalizeWords from 'word-capitalize';

// CommonJS
const capitalizeWords = require('word-capitalize');
```

### Example

```javascript
const text = "hello world from npm!";
const result = capitalizeWords(text);

console.log(result); // Output: "Hello World From Npm!"
```

---

## API Reference

### `capitalizeWords(input: string): string`

- **Description:** Capitalizes the first letter of each word in the input string.
- **Parameters:**
  - `input` *(string)*: The string to be formatted.
- **Returns:** *(string)*: The formatted string with capitalized words.

---

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue on the [GitHub repository](https://github.com/haxcod/word-capitalize).

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Keywords

- word-capitalization
- string-utils
- text-formatting
- text-capitalization
- capitalize-words
- string-manipulation
- javascript
- nodejs
- utility
