# Simple Fonts for Kaluma

This module includes several bitmap fonts for Kaluma as below:

- `minimal` : A minimal font (3x5 pixels).
- `leros` : A monotype font (5x10 pixels).
- `yamaha` : A monotype font (6x11 pixels).
- `lee-sans` : A variable-width font (10x10 pixels).

## Install

```sh
npm i https://github.com/niklauslee/simple-fonts
```

## Usage

```js
var font = require('simple-fonts/minimal');
// var font = require('simple-fonts/leros');
// var font = require('simple-fonts/yamaha');
// var font = require('simple-fonts/lee-sans');

// get graphic context 'gc' from a driver (e.g. 'ssd1306')
gc.setFont(font);
gc.drawText(0, 0, "LOREM IPSUM DOLOR SIT AMET...");
gc.display();
```
 
## Glyphs

__minimal__

![glyph-minimal](https://github.com/niklauslee/simple-fonts/blob/main/images/minimal.png?raw=true)

__leros__

![glyph-leros](https://github.com/niklauslee/simple-fonts/blob/main/images/leros.png?raw=true)

__yamaha__

![glyph-yahama](https://github.com/niklauslee/simple-fonts/blob/main/images/yamaha.png?raw=true)

__lee-sans__

![glyph-lee-sans](https://github.com/niklauslee/simple-fonts/blob/main/images/lee-sans.png?raw=true)

## License

[MIT](LICENSE)
