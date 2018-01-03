# bs-court-dimensions

[![NPM](https://nodei.co/npm/bs-court-dimensions.png)](https://www.npmjs.com/package/bs-court-dimensions)

## Installation

`npm i bs-court-dimensions`

## Usage

```js
const { courtConfigZoomed, generateCourt } = require('bs-court-dimensions');

// Generate a FIBA basket court at your desired zoom level
const courtZoomed = courtConfigZoomed(60);

// Display the basket-ball court inside the svg
// Use same zoomMultiplicator as the courtConfigZoomed function
generateCourt('#app', courtZoomed, 60);
```

All functions are curried.

### Example

`npm run example` then go to `http://localhost:1234`
