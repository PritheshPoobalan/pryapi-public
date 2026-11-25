# API Reference - pryapi-public

## Installation

```bash
npm install @pryapi/pryapi-public
```

## Import

CommonJS:

```js
const pryapi = require('@pryapi/pryapi-public');
```

## Entry point

The SDK entry point (`src/index.js`) exports a single object:

| Property | Type | Value | Description |
|----------|------|-------|-------------|
| `name` | string | `pryapi-public` | Package name |
| `version` | string | `0.1.0` | Package version |

## Example

```js
const pryapi = require('@pryapi/pryapi-public');

console.log('PryAPI SDK:', pryapi.name);
console.log('Version:', pryapi.version);
```

## Modules

| Module | Description |
|--------|-------------|
| `src/index.js` | SDK entry point, exports package name and version |
| `src/features.js` | Feature modules |
| `src/fixes.js` | Error-handling fixes |
| `src/refactors.js` | Simplified functions |
| `src/performance.js` | Optimized loop iterations |
| `src/style.js` | Formatted code blocks |

## License

MIT
