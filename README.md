# Player-facing Dustgrave Data for Comp/Con

## Installation

```js
npm add @massif/dustgrave-data
//or
yarn add @massif/dustgrave-data
```

## Usage

```js
import * as dustgrave from '@massif/dustgrave-data';

const dustgraveFrameData = dustgrave.frames;
```

## Building LCP

```js
yarn && yarn build
// or
npm install && npm run build
```

produces a versioned LCP file in `dist/`
