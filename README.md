# Cash Lazlo
## The economy add-on for Camp Lazlo

This add-on implements custom currency in Minecraft, which players can use for trading. Currently, there are five tiers in the currency system:
- Copper ![CopperCoin](https://github.com/Baconfry/cash-lazlo/blob/main/Cash%20Lazlo/Cash%20Lazlo%20Resource%20Pack/textures/items/copper_coin.png)
- Silver ![SilverCoin](https://github.com/Baconfry/cash-lazlo/blob/main/Cash%20Lazlo/Cash%20Lazlo%20Resource%20Pack/textures/items/silver_coin.png)
- Gold ![GoldCoin](https://github.com/Baconfry/cash-lazlo/blob/main/Cash%20Lazlo/Cash%20Lazlo%20Resource%20Pack/textures/items/gold_coin.png)
- Platinum ![PlatinumCoin](https://github.com/Baconfry/cash-lazlo/blob/main/Cash%20Lazlo/Cash%20Lazlo%20Resource%20Pack/textures/items/platinum_coin.png)
- Emerald ![EmeraldCoin](https://github.com/Baconfry/cash-lazlo/blob/main/Cash%20Lazlo/Cash%20Lazlo%20Resource%20Pack/textures/items/emerald_coin.png)

The superseding tier is worth five (5) coins of the previous tier, so one (1) silver coin is equivalent to five (5) copper coins, and so on. You can convert coins back and forth the tiers using the crafting table. This add-on also adds loot drops for hostile mobs, making them drop coins.

**PRO TIP:** If you haven't yet, check out the [currency converter](https://github.com/Baconfry/cash-lazlo-calculator/releases) written for Windows. It converts copper coins to mixtures of different coins. It's very useful if you're trading thousands of copper regularly!

Moreover, this add-on implements a special item that lets the banker (ar anyone in possession of the item) teleport to a specific set location, which is the bank in this case. This is handy when the bank has a customer that needs attending to and the banker is away.

## World prerequisites

As of Minecraft `1.17.2`, this add-on needs some settings to be configured in the world or server. Refer to the image below.

![Settings configuration](https://github.com/Baconfry/cash-lazlo/blob/main/Documentation/Settings.png)

Cheats are optional. Its function is to give coins to the  server players. An example is: 

`/give @s lazlo:copper_coins 64`

This command gives the current player 64 copper coins.

## Mod... modding?!

If you want to edit this mod and compile it for your own use, simply modify the files in the **Cash Lazlo Behavior Pack** and **Cash Lazlo Resource Pack** folders and compile them in a `.zip` file. Afterwards, rename the extension from `.zip` to `.mcaddon`.

## Known bugs

A known bug is that categories for the coins do not work properly. This is likely a Minecraft bug. There are currently no workarounds for this bug.

## Credits

This add-on is heavily inspired by Axelpvz's [Custom Economy Sistem](https://mcpedl.com/custom-economy-sistem/) mod. All of this wouldn't have been possible without his mod. Huge props to this chad modder.

The coins used in the add-on is provided by OhBirb.
