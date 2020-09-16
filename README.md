# godot-titan
Precompiled builds of Godot 3.x with my modules and modifications, and selected third party modules.

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

* 0.19 LLightmap improved lightprobe generation code
* LPortal fixed order of operations bug (which caused single frame delay in culling)
* 0.18 LLightmap multithreaded backwards tracing, fixed small bug in low quality forward rendering setting
* 0.17 LLightmap new bidirectional backwards tracing, updated project settings and docs
* 0.16 LLightmap another texture sampling bug, improvements to backward tracing (artifacts and speed)
* 0.15 LLightmap improved error message boxes
* 0.14 LLightmap bug fix in texture sampling
* 0.13 LLightmap reworked more robust uvmapping
* 0.12 LLightmap lightprobes first implementation.
* 0.11
* 0.10 LLightmap mostly working but no lightprobes.

LPortal usable but needs some tidying to remove lightmap functionality that has moved to LLightmap.
LSimd should be okay, CPU detection code hasn't been tested under windows so it may be using non-SIMD path.
