# Minecraft Texture Hex Colors

JSON files mapping Minecraft texture files and bukkit material enums to their **dominant hex colors**. Each key is the **texture name/enum name** (without file extension), and each value is a **hex color code** representing the primary color of that texture.

This file is useful for:

- Resource pack development  
- Mods or plugins that need texture-based color data  
- Visualization or analysis of Minecraft textures  
- Generating color palettes for UIs or maps  

> [!CAUTION]
> If retrieving colors via the bukkit material enum name, use `material-colors.json`!

## Texture Example

```json
{
    "acacia_door_bottom": "#925631",
    "activator_rail_on": "#AAA294",
    "allium": "#BC7CEC",
    "acacia_planks": "#8C452C",
    "acacia_log": "#6C645C",
    "anvil_top": "#444444",
    "attached_melon_stem": "#8C8C8C",
    "acacia_trapdoor": "#994F2F",
    "acacia_sapling": "#755510",
    "attached_pumpkin_stem": "#8C8C8C",
    "activator_rail": "#AAA294",
    "acacia_log_top": "#B56034",
    "acacia_door_top": "#844D2C",
    "acacia_leaves": "#B4B4B4",
    "azalea_plant": "#506528",
    "bamboo_door_bottom": "#B6AC4C",
    "bamboo_block_top": "#5A6722",
    "azalea_leaves": "#3C4C24",
    "bamboo_block": "#84923C"
}
```

## Bukkit Enum Example

```json
{
    "GOLD_ORE": "#A4A4A4",
    "WAXED_EXPOSED_CUT_COPPER_SLAB": "#BC8474",
    "DEEPSLATE": "#36363E",
    "WEATHERED_CHISELED_COPPER": "#7AB499",
    "DEEPSLATE_COPPER_ORE": "#6E6E6E",
    "JUNGLE_PLANKS": "#B68461",
    "POLISHED_DEEPSLATE": "#616161",
    "WAXED_CUT_COPPER_SLAB": "#A25A42",
    "EXPOSED_CHISELED_COPPER": "#C6897E",
    "COPPER_ORE": "#7A7A7A",
    "BIRCH_PLANKS": "#9D8D64",
    "WAXED_OXIDIZED_CUT_COPPER_STAIRS": "#57AA8F",
    "CHISELED_COPPER": "#9E563E",
    "DEEPSLATE_IRON_ORE": "#74716E",
    "SPRUCE_PLANKS": "#74542C",
    "WAXED_WEATHERED_CUT_COPPER_STAIRS": "#65A36F",
    "OXIDIZED_COPPER": "#61B996",
    "IRON_ORE": "#757575",
    "OAK_PLANKS": "#68562D",
    "WAXED_EXPOSED_CUT_COPPER_STAIRS": "#BC8474",
    "WEATHERED_COPPER": "#64A774",
    "DEEPSLATE_COAL_ORE": "#303036",
    "WAXED_CUT_COPPER_STAIRS": "#A25A42"
}
```
