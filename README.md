# RandomlyThingies

A standalone BedrockTools addon containing three visual modules:

- FPS Graph
- Chunk Fade
- Custom Camera Offsets

It builds a separate `libRandomlyThingies.so` and `RandomlyThingies.levipack`.

## Relationship to BedrockTools

RandomlyThingies is designed as an addon for the original BedrockTools runtime. It does not package or replace `libBedrockTools.so`.

The addon uses BedrockTools' public ABI (`BedrockTools_GetApi`) for signature resolution, client access, and event delivery.

## Build

GitHub Actions builds the Android ARM64 package automatically.

Output:

```text
RandomlyThingies.levipack
```

The package contains:

```text
manifest.json
libRandomlyThingies.so
icon.png
resources/minecraft.ttf
```

Author: Blurmistredist
