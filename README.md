# Minecraft Texture Hex Colors

A JSON file mapping Minecraft texture files to their **dominant hex colors**. Each key is the **texture name** (without file extension), and each value is a **hex color code** representing the primary color of that texture.

This file is useful for:

- Resource pack development  
- Mods or plugins that need texture-based color data  
- Visualization or analysis of Minecraft textures  
- Generating color palettes for UIs or maps  

> [!CAUTION]
> If retrieving colors via the bukkit material enum, use material-colors.json!

## Example

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
