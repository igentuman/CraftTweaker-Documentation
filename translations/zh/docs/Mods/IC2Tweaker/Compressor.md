# Compressor

## 所属包名

`import mods.ic2.Compressor;`

## Methods

- **[IItemStack](/Vanilla/Items/IItemStack/) output**
- **[IIngredient](/Vanilla/Variable_Types/IIngredient/) input**

## 添加配方

```zenscript
mods.ic2.Compressor.addRecipe(IItemStack output, IIngredient input);

mods.ic2.Compressor.addRecipe(<minecraft:diamond_block>, <minecraft:dirt> * 64);
```

## Removal

To remove an existed recipe, simply remove the corresponding line in `config/ic2/compressor.ini`