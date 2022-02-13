# Font Minimal

A minimal font (only 3x5 pixels).

## Install

```sh
npm install https://github.com/niklauslee/simple-fonts
```

## Usage
 
```js
var font = require('simple-fonts/minimal');
// get graphic context 'gc' from a driver (e.g. 'ssd1306')
gc.setFont(font);
gc.setFontScale(3, 3); // Enlarge font size to be readible.
gc.drawText(0, 0, "LOREM IPSUM DOLOR SIT AMET...");
gc.display();
```
 
## Glyph

![logo](https://github.com/niklauslee/simple-fonts/blob/master/glyph-minimal.jpeg?raw=true)

