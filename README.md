# svg-to-png-lite

> Converter SVG to PNG

## HOW TO START

_Start:_

1. Install a dependency with `npm i --save svg-to-png-lite`

2. Import a library:
````javascript
import svgpng from 'svg-to-png-lite';
````
Example 1:
````javascript
// Passing o ID do SVG
svgpng("svg-id").then(console.log).catch(console.error)
````

Example 2:
````javascript
// Determining Width and Height - Passando e Opções
svgpng("svg-id", {width:300, height:300}).then(console.log).catch(console.error)
````
## OPTIONS

### WIDTH `Number`.  Default `Default SVG width`

Determines the width of the image.

### HEIGHT `Number`. Default `Default SVG height`

Determines the height of the image.

### EXT `String`. Default `PNG`

Determines the extension of the image: PNG or JPEG
