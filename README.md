Very Simplistic software rendering library written in C aiming to support as wide of a range of systems as possible (by not depending on C std lib).
Done in a very stupid way, but its not supposed to be smart.

Examples of how it can be used in terminal, web browser canvas (via WASM) and raylib as a window provider in the examples folder
- To build Examples (requires raylib)
```bash
  cc -o builder builder.c
  ./builder
```

The idea is to just use render.h and provide your custom things you need on top of that, which is shown in renderfull.h adding a couple of helpers (some require posix)
