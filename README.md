# PryAPI SDK - pryapi-public

PryAPI SDK for the pryapi-public package. A lightweight Node.js SDK for the PryAPI platform.

## Installation

```bash
npm install @pryapi/pryapi-public
```

## Usage

```js
const pryapi = require('@pryapi/pryapi-public');

console.log(pryapi.name);    // pryapi-public
console.log(pryapi.version); // 0.1.0
```

## API reference

See [docs/api.md](./docs/api.md) for the full API reference.

## Project structure

- `src/index.js` — SDK entry point (CommonJS)
- `src/features.js` — feature modules
- `src/fixes.js` — error-handling fixes
- `src/refactors.js` — simplified functions
- `src/performance.js` — optimized loops
- `src/style.js` — formatted code blocks
- `tests/` — test cases
- `docs/` — documentation
- `build/` — build configuration

## License

MIT
