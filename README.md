# Chat Commands
A muck mod made to add quite a few cheat chat commands into the game


## Commands

`/god` enables god mode.
`/tp player name` teleports to a player. `Aliases: teleport, tp`
`/kick player name` Kicks a a player from the game (Host only).
`/fly` Toggles flight.
`/fs num` Changes your flight speed; default is 30. `Aliases: fs, flyspeed`
`/i item_name amount` Gives you an amount of items. `Aliases: i, giveitem`
`/p powerup_name amount` Gives you an amount of powerups. `Aliases: p, givepowerup`
`/time day/night` Changes the time (Host only).
`/nh` Removes hunger drain. `Aliases: nh, nohunger` 
`/ns` Removes stamina drain. `Aliases: ns, nostamina` 
`/help` Prints a help statement to the debug console.


## Changelog
### 1.1

 - Added commands `flyspeed, kick`
 - Added aliases to commands `fs, i, p, nh, ns`
 - Removed alias `tele`
 - Made a better `god` command.
 - Removed underlying `remove_powerup` function that old god relied on.
