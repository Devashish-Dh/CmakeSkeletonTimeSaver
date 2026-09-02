# CMake skeleton (time saver)

Copy-this layout for a new C++ project: root `CMakeLists.txt`, `src/`, `include/`, optional `docs/` and `libs/`, and a `build/` directory that stays local.

```
<project>/
  CMakeLists.txt
  README.md
  docs/          documentation
  src/           .cpp modules
  include/       headers
  libs/          third-party (if any)
  build/         cmake output (gitignored)
```

Configure from `build/`:

```bash
cmake -S . -B build
cmake --build build
```

Add `[Bb][Uu][Ii][Ll][Dd]` to `.gitignore` so binaries never get committed.
