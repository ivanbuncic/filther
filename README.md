
[![Wallaby.js](https://img.shields.io/badge/wallaby.js-powered-blue.svg?style=for-the-badge&logo=github)](https://wallabyjs.com/oss/)

# Filther - your best array duplicates extinguisher

Filtering Arrays for duplicates with Set and back

## Install

npm i filther

## Usage

```js 
import f from 'filther';

let arr = [23, 23, 23, 23, 23, 45, 45, 45, 567, 67, 67, 67, 67, 67];

let filtered = f(arr);

console.log(filtered) // should return [23,45,567,67] 
```

Good luck!
