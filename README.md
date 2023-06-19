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

### Nbt values that change player state on relog
- `Rotation`
- `SelectedItemSlot` - slot selected
- `XpP` - individual xp points
- `XpLevel` - xp levels
- `XpTotal` - total xp

### NBT values that don't change state when edited
- `Motion` - velocity
- `abilities.mayfly` (resets on reconnect) - whether you're able to fly 
- `abilities.flying` (resets on reconnect) - whether you're flying 
- `Dimension` (resets instantly)
- `playerGameType` (resets instantly) - gamemode


There are more that I haven't checked yet
