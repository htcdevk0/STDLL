# stddll

`stddll` is a single-header C++ utility for portable dynamic library loading
across Windows (DLL) and POSIX systems (SO).

It provides a minimal, RAII-based interface for loading shared libraries,
resolving symbols, and managing library lifetimes safely and predictably.

The design goal is simplicity, correctness, and toolchain-level usability,
making it suitable for MinGW, MSYS2, Linux, and cross-platform C++ projects.

---

## Features

- Header-only
- Cross-platform (Windows / POSIX)
- RAII-based handle management
- Explicit symbol resolution
- Safe move semantics
- No runtime dependencies
- No ABI impact
- Suitable for plugin systems and loaders

---

## Installation

Simply place the header in your include path:

```cpp
#include <stddll>
