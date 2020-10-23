# RPGMaker MV Engine Updates

This is a set of updates based on RPGMaker MV 1.6.2 to use PixiJS 5.3.3

## Features

- Case insensitive file loading to better support Linux/Android out of the box
- Batch rendering
- With NWJS v0.45.6 plays webm (VP8/VP9) files properly

## Known Issues

- ShaderTilemap is not working properly falling back on Tilemap
- Maybe incompatible with some plugins if they are overriding image loading

## Further Work

- Cleanup of Javascript (using let/const)
- Add updates to plugins
