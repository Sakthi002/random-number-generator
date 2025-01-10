# Random Number Generator

A simple JavaScript utility to generate random numbers within a specified range. This package is lightweight, easy to use, and ideal for a variety of use cases including games, simulations, and general utilities.

## Features

- Generate random integers within a specified range.
- Default range is 0 to 100.
- Designed for ease of use and flexibility.

## Installation

Install the package via npm:
```bash
npm install sakthi-random-num-generator-js
```

## Usage

### Import the Function

```javascript
import randomNumberGenerator from 'sakthi-random-num-generator-js';
```

### Example Usage

#### Generate a random integer:
```javascript
const randomInt = randomNumberGenerator(1, 10);
console.log(`Random Integer: ${randomInt}`); // e.g., 7
```

#### Generate a random integer with default range (0 to 100):
```javascript
const randomIntDefault = randomNumberGenerator();
console.log(`Random Integer (Default Range): ${randomIntDefault}`); // e.g., 42
```

## Parameters

- **min**: The minimum value in the range (inclusive). Defaults to `0`.
- **max**: The maximum value in the range (inclusive). Defaults to `100`.

## Notes

- The function uses `Math.random()` to generate the randomness.
- Ensure `min` is less than or equal to `max` to avoid unexpected behavior.

## License

This package is available under the [MIT License](LICENSE).

Feel free to use, modify, and distribute this package as needed!