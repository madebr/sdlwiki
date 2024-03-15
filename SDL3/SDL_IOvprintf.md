###### (This is the documentation for SDL3, which is under heavy development and the API is changing! [SDL2](https://wiki.libsdl.org/SDL2/) is the current stable version!)
# SDL_IOvprintf

Print to an [SDL_IOStream](SDL_IOStream) data stream.

## Syntax

```c
size_t SDL_IOvprintf(SDL_IOStream *context, SDL_PRINTF_FORMAT_STRING const char *fmt, va_list ap) SDL_PRINTF_VARARG_FUNCV(2);

```

## Function Parameters

|                 |                                                        |
| --------------- | ------------------------------------------------------ |
| **context**     | a pointer to an [SDL_IOStream](SDL_IOStream) structure |
| **fmt**         | a printf() style format string                         |
| **ap**          | a variable argument list                               |

## Return Value

Returns the number of bytes written, or 0 on error; call
[SDL_GetError](SDL_GetError)() for more information.

## Remarks

This function does formatted printing to the stream.

## Version

This function is available since SDL 3.0.0.

## Related Functions

* [SDL_IOFromConstMem](SDL_IOFromConstMem)
* [SDL_IOFromFile](SDL_IOFromFile)
* [SDL_IOFromMem](SDL_IOFromMem)
* [SDL_ReadIO](SDL_ReadIO)
* [SDL_SeekIO](SDL_SeekIO)
* [SDL_WriteIO](SDL_WriteIO)

----
[CategoryAPI](CategoryAPI)
