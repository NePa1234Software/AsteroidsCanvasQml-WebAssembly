# AsteroidsCanvasQml-WebAssembly

WebAssembly multi-threaded is not working yet.... Work in Progress....

## Play Online
Play the single threaded version here online (some time hopefully multi-threaded will work soon).

URL:
https://nepa1234software.github.io/AsteroidsCanvasQml-WebAssembly/appAsteroidsQml.html

Fallback use Single-Threaded build URL: https://nepa1234software.github.io/AsteroidsCanvasQml-WebAssembly-SingleThreaded/appAsteroidsQml.html

## Licensing
See the license file and License Folder for details
- The game is build using the Qt Framework opensource version (https://www.qt.io/licensing/)
- The vector battle font is provided from dafont (https://www.dafont.com/vector-battle.font)
- WebAssembly build powered by emscription SDK (https://emscripten.org/docs/introducing_emscripten/emscripten_license.html)

## Known Issues
WebAssembly multi-threaded will not start - ReferenceError: SharedArrayBuffer is not defined !!

WebAssembly single-threaded is not brilliant regarding performance, especially on android. 

The timer is blocked for a short while on every user interaction.
I have reduce a large number of console logs to get an acceptable flow on Windows Desktop.

NOTE - The keyboard context only works when you click on one of the control buttons first. This is not a problem for desktop builds !
