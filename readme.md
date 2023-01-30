## web-js-password-gen

Password generator using JS for Websites


## Installation

- Download or copy `passwordGenerator.js` from the root directoy [click here](https://www.github.com/alexisg24/web-js-password-gen#passwordGenerator.js)
- Move or create a file in your code directory
- For NodeJS [click here](https://www.github.com/alexisg24/js-password-gen)

## Usage
- Use Import of ES6+ Syntax
  ```javascript
  import generatePasswordWeb from '.**/passwordGenerator.js';
  const password = generatePasswordWeb(length, options);
  /*
  length: Number,
  options: { chars: boolean, upperCase?: boolean, numbers?: boolean, symbols?: boolean }
  */
  ```
- Example:
  ```javascript
  //index.js:
  import generatePasswordWeb from '.**/passwordGenerator.js';
  const password = generatePasswordWeb(16, {chars: true, symbols: true, numbers: true, upperCase:true})
  console.log(`password:`, password) //password: #YP]%#x]u3K:/Z0;
  ```

- Import in HTML code
  ```html
  ...
  <script src="./index.js" type="module"></script>
  ```

## length - Number
- Type `number`
- Default value: `8`
- Max value: `32`
## { options } - Object

| **Prop**          | **Type**   | **Description**                                                                                                                                                                                                                                                 | **Required** |
| ----------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| chars           | `boolean`   | Include characters in your password.                                                                                                                                                                | ✅            |
| upperCase           | `boolean`   | Include upper case characters in your password.                                                                                                                                       |              |
| numbers     | `boolean`   | Include numbers in your password. |              |
| symbols         | `boolean` | Include symbols in your password.                                                                                                                                                   |              | 

## Authors

- [@alexisg24](https://www.github.com/alexisg24)

![](https://img.shields.io/twitter/follow/MasterCR_)  ![](https://img.shields.io/github/followers/alexisg24?style=social) ![](https://img.shields.io/github/stars/alexisg24/web-js-password-gen?style=social)