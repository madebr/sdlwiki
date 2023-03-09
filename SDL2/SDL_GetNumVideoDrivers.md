###### (This is the legacy documentation for stable SDL2, the current stable version; [SDL3](https://wiki.libsdl.org/SDL3/) is the current development version.)
# SDL_GetNumVideoDrivers

Get the number of video drivers compiled into SDL.

## Syntax

```c
int SDL_GetNumVideoDrivers(void);

```

## Return Value

Returns a number >= 1 on success or a negative error code on failure; call
[SDL_GetError](SDL_GetError)() for more information.

## Version

This function is available since SDL 2.0.0.

## Related Functions

* [SDL_GetVideoDriver](SDL_GetVideoDriver)

----
[CategoryAPI](CategoryAPI)
