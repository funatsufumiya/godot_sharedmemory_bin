# godot_sharedmemory_bin

binary repository of [godot_sharedmemory](https://github.com/funatsufumiya/godot_sharedmemory)

if you need `godot_sharedmemory` [releases](https://github.com/funatsufumiya/godot_sharedmemory/releases) as `git submodule`, please use this repository.

## Simple usage example

```bash
cd PROJECT_DIR_OF_YOUR_GODOT
cd addons
git submodule add https://github.com/funatsufumiya/godot_sharedmemory_bin.git sharedmemory
# or simply: git clone https://github.com/funatsufumiya/godot_sharedmemory_bin.git sharedmemory
```

but I recommend to use `godotenv addons install`. see [GodotEnv's readme](https://github.com/chickensoft-games/GodotEnv?tab=readme-ov-file#initializing-godotenv-in-a-project). GodotEnv's `addons.jsonc` config is below (partial):

```json
    "sharedmemory": {
      "url": "https://github.com/funatsufumiya/godot_sharedmemory_bin",
      "checkout": "v0.1.0",
    },
```

