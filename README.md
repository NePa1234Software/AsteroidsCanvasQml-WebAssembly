# NePa1234Software.github.io

WebAssembly multi-threaded is not working yet.... Work in Progress....
Play online (some time hopefully soon): 
https://nepa1234software.github.io/AsteroidsCanvasQml-WebAssembly/appAsteroidsQml.html
Currently blocked by an error - ReferenceError: SharedArrayBuffer is not defined

WebAssembly single-threaded is not acceptable regarding performance. The timer is blocked for a short while on every user interaction. 

Issues regarding regarding keyboard scope persist and isAutoRelease flag of Key onPressed event not being set by the qt framework (multi-thread build) is solved using a (semi-optimal) workaround.

