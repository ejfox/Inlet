Inlet is a "plugin" for CodeMirror2 which pops up a slider whenever you click on a number or a color picker when you click on a Hex string (i.e. "#ff0000")

See an example at http://enjalot.github.com/Inlet

# About

This project is inspired by Bret Victor's talk ["Inventing on Principle"](https://vimeo.com/36579366)  

The the slider code is adapted from Gabriel Florit's [Water project](http://gabrielflor.it/water)  

The [Color Picker library](https://github.com/mudcube/Color-Picker)  

This project is used in enjalot's [Tributary](http://tributary.io)  


# Usage

All you need is the inlet.js file from src/inlet.js  
but you do need to make sure you have all of the libs this depends on (found in the example/lib folder):
ColorPicker  
CodeMirror2 ( >= 3.1 )  

Check out index.html to see how to put things together

The key bit of javascript code to kick things off is:
```javascript
var editor = CodeMirror('#editor', ...)
Inlet(editor)
```

Enjoy!
