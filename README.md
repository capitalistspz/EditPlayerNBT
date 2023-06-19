# EditPlayerNBT
A mod that just removes the line preventing player NBT from being modified

### NBT values that change player state instantly
- `abilities.flySpeed` - alters vertical flight speed
- `abilities.walkSpeed` - alters walking speed
- `abilities.invulnerable` - makes you invulnerable
- `foodLevel` - hunger
- `Fire` - time on fire
- `Inventory`
- `EnderItems` - enderchest items
- `Pos` - position
- `AbsorptionAmount` - Amount of absorption

### NBT values that don't
- `Motion` - velocity - value is ignored
- `Rotation` - value is ignored
- `abilities.mayfly` - whether you're able to fly - value is ignored, and gets set to correct value on reconnect
- `abilities.flying` - whether you're flying - value is ignored, and gets set to correct value on reconnect
- `SelectedItemSlot` - slot selected
- `XpP` - individual xp points
- `XpLevel` - xp levels
- `XpTotal` - total xp
- `Dimension` - values is ignored, and always instantly changes to correct value
- `playerGameType` - gamemode - value is ignored, and always gets instantly set to the correct gamemode
