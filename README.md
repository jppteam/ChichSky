<div align='center'>
	<img src='CHICHSKY.png' alt="ChichSky logo"/>
</div>

**ChichSky** is Skyland config pack for [Terra](https://modrinth.com/plugin/terra) - world generation modding platform.
Inspired by [Aeropelago](https://github.com/Astrashh/Aeropelago) and [TerraOverworldConfig](https://github.com/PolyhedralDev/TerraOverworldConfig) (and 85% of the original code taken from them).

<p align="center" >
<kbd>Currently in beta</kbd>
</p>

---

## Installation

0. Download and install [Terra](https://modrinth.com/plugin/terra) for your platform
1. Download this repo
2. Unarchive it in your `/config/Terra/packs/` (for modded) or `/plugins/Terra/packs/` (for bukkit) folder
3. Now you can use the `generator.terra.chichsky/chichsky` world type in your client/server

## Customization

You can customize:

- Island settings (`island-*` values in [`customization.yml`](customization.yml) file)
- Scale of biomes (`biome-distribution` part in [`customization.yml`](customization.yml) file)
- Biomes colors (`color_*` files in [`biomes/abstract`](biomes/abstract/) folder)
- Enabling/disabling vanilla biomes in [`distribute_vanilla_biomes.yml`](biome-providers/stages/distribute_vanilla_biomes.yml) file
- Enabling/disabling custin biomes in [`distribute_custom_biomes.yml`](biome-providers/stages/distribute_custom_biomes.yml) file

## Implemented `custom` biomes

- `amethyst_hills`
- `ash_savanna_plains`
- `bushland`
- `birch_taiga`
- `blooming_valley`
- `cloud_forest`
- `desert_oasis`
- `forested_highlands`
- `glacial_chasm`
- `glass_pools` (community biome)
- `gravel_desert`
- `hot_springs`
- `ice_marsh`
- `lavender_valley`
- `moonlight_valley`
- `obsidian_peaks` (community biome)
- `sakura_valley`
- `tropical_jungle`
- `warped_mesa`
- `white_cliffs`

## Implemented `vanilla` biomes

- `badlands`
- `cherry_grove`
- `desert`
- `forest` (with `birch_forest`, `dark_forest` and `flower_forest`)
- `jungle` (with `bamboo_jungle`)
- `mushroom_fields`
- `plains` (with `sunflower_plains`, `snowy_plains` and `ice_spikes`)
- `savanna` (with `savanna_plateau`)
- `swamp` (with `mangrove_swamp`)
- `taiga` (as `snowy_taiga`)

## Credits

- [Terra](https://modrinth.com/plugin/terra)
- [Aeropelago](https://github.com/Astrashh/Aeropelago)
- [TerraOverworldConfig](https://github.com/PolyhedralDev/TerraOverworldConfig)

bro idk what to put here look at this epic 2+2 is 4 math $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
