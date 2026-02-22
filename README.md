# CSC_43043_EP — Project Template

Template code for the **CSC_43043_EP** project.


## Build

### With CMake (recommended)

```bash
cmake --preset debug
cmake --build --preset debug
./project
```

Other presets: `release`, `relwithdebinfo`.

### With Make

```bash
make
./project
```

To rebuild from scratch: `make clean && make`.

## Controls

Controls depend on the scene but the default camera uses:

- **Left mouse button** — rotate
- **Right mouse button / scroll** — zoom
- **Middle mouse button** — pan

An ImGui panel is available on the left side of the window for runtime parameters.
