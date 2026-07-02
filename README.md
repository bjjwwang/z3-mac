# z3-mac

This repository builds Z3 4.15.4 from source on GitHub Actions `macos-14`.

The workflow installs the resulting headers and dynamic library into:

```text
z3.obj/
  bin/libz3.dylib
  include/*.h
```

The final uploaded artifact is `z3-4.15.4-arm64-macos-14.zip`, containing the
top-level `z3.obj` directory.
