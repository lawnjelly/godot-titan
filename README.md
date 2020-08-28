# godot-titan
Builds of Godot 3.x with my modules and modifications

## Modules
These are the original repositories for the modules, which contain instructions:

#### Author : @lawnjelly
* LLightmap (https://github.com/lawnjelly/godot-llightmap)
* LPortal (https://github.com/lawnjelly/godot-lportal)
* LSimd (https://github.com/lawnjelly/godot-lsimd)

#### Author : @Geequlim
* ECMAScript (https://github.com/GodotExplorer/ECMAScript)

## Building
* The github action scripts in this repository show how the builds are made.
* The modules can be downloaded individually (from their repositories) and compiled together with the engine.
* For cutting edge you can also compile the repository https://github.com/lawnjelly/godot with the `titan` branch, although this may not be as stable as compiling the repositories.

## Releases

### 0.10 (LLightmap 0.27, LPortal 0.21, LSimd 0.10, ECMAScript) (August 27th 2020)
* LLightmap mostly working but no lightprobes.
* LPortal usable but needs some tidying to remove lightmap functionality that has moved to LLightmap.
* LSimd should be okay, CPU detection code hasn't been tested under windows so it may be using non-SIMD path.

