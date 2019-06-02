# loadFile
The loadFile is node.js version of the synchronous download of the file.

## Packaged Builds
The easiest way to use loadFile in your code is by using the built source at `build/loadFile.js`.
These built JavaScript files bundle all the necessary dependencies to run loadFile.

In your `head` tag, include the following code:
```html
<script src="https://raw.githack.com/anhr/loadScriptNodeJS/master/build/loadFile.js"></script>
```

Now you can use window.loadFile for synchronous download of the file.

### loadFile.sync( url )

Synchronous download of the file.

url: URL of an external file for downloading.
returns file content

### Example
```
//Synchronous download of the element.html file into "elID" element
document.getElementById( "elID" ).innerHTML = loadFile.sync('element.html');
```

## Directory Contents

```
└── build - Compiled source code.
```

## Building your own customController

In the terminal, enter the following:

```
$ npm install
$ npm run build
```

## npm scripts

- npm run build - Build development and production version of scripts.

## Thanks
The following libraries / open-source projects were used in the development of customController:
 * [Rollup](https://rollupjs.org)
 * [Node.js](http://nodejs.org/)

 ## Have a job for me?
Please read [About Me](https://anhr.github.io/AboutMe/).
