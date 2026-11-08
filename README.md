# FIB resources

The game files for ForceItemBattle: the resource pack, the worldgen
datapack and what the server needs alongside the [plugin](https://github.com/McPlayHDnet/ForceItemBattle).

| Path | What |
|---|---|
| `ForceItemBattle/` | Resource pack: item icons for the bossbar, tab and chat |
| `unicodeItems.json` | Tells the plugin which pack glyph is which item |
| `FIB_Worldgen/` | Worldgen datapack: the custom structures |
| `pack-overrides/` | Custom textures |
| `seeds/` | Curated seed lists for `/reset <biome>` |
| `config.yml` | The plugin config |

## Using the pack

Each [release](https://github.com/eltobit0/fib-resources/releases/latest) has the pack, the datapack
and the matching `unicodeItems.json`. Use all three from the same release: the glyphs only line up
within one.

```properties
resource-pack=https://github.com/eltobit0/fib-resources/releases/latest/download/ForceItemBattle.zip
resource-pack-sha1=<from the release notes>
```

`unicodeItems.json` and `FIB_Worldgen.zip` go in `plugins/ForceItemBattle/`.
