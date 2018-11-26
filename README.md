# node-sdl2
[A fork](https://github.com/RobLoach/node-sdl2/tree/update) of a fork of [node-sdl2](https://github.com/zetsin/node-sdl2) with better SDL bindings.

## SDL2 API Reference
https://wiki.libsdl.org/CategoryAPI

## Dependencies
* Requires [Windows Build Tools](https://github.com/felixrieseberg/windows-build-tools) installed.
* [Node.js v8](https://nodejs.org/dist/latest-v8.x/); I was not able to build the library using Node.js v10. As a workaround use v8.

## How to use
* In your *'package.json'* file add a new dependency with name "node-sdl2" with value "https://github.com/Captain-Chen/node-sdl2.git" then save the changes.
* Run *npm install* and it will download all the required dependencies. If you need to recompile the libraries run *npm rebuild*.
* In your file, add a reference to the package *'node-sdl2'* and begin using the library.

## Misc Notes
* If you are using the [original build of the SDL2 bindings](https://github.com/zetsin/node-sdl2) you will need to have [SDL2](https://www.libsdl.org/download-2.0.php).
* I was able to run the [example](https://github.com/zetsin/node-sdl2#tutorials) by having the compiled library inside the project folder.
