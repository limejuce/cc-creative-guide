<h2>II.2. Commands - Plotting</h2>

The plot command is the important on this creative. Speaking of plots, this server uses PlotSquared as the plot plugin. We will use /p for the rest of this section. Let's asssume the owner is you.

| Commands | Description |
| --- | --- |
| /p auto | Claims a random plot. You can claim 2 plots as a normal player, 4 as a Donator 1, 6 as a Donator 2, and 8 as a Donator 3
| /p claim | Claims an empty plot, use this commands inside an empty plot.
| /p buy | Buys a selled plot.
| /p delete | Deletes your plot from the existence. Watch out.
| /p home<br>/p h<br>/p visit<br>/p v<br>/p goto | Goes to a plot. If there is no identifier, it will teleport you to your own plot. If there is a number, it will teleport you to your plot that you specify. ("/p h 2" goes to your second plot). If there is a player name, it will teleport you the player's (first) plot. ("/p h Pixel5958" goes to my first plot). Add a number and it will teleport you to the specified player's plot. ("/p h Pixel5958 2" goes to my second plot). You can also use coordinates to go to a specific plot. ("/p h 0;1" goes to the spawn plot)
| /p info | Tells you about a plot. Stand in a plot, use the command, and you will get informations about the plot.
| /p add | Adds a player to the plot. They can build on your plot when the owner online.
| /p trust | Trust a player to the plot. They can build on your plot even the you offline. Be careful with this command
| /p kick | Kicks a player from your plot. They can go back to your plot at any time.
| /p deny | Denies (bans) a player from your plot. They can't go to your plot anymore.
| /p remove<br>/p r<br>/p untrust<br>/p ut<br>/p undeny<br>/p ud | Removes (unadds), untrust, or undenies a player from your plot.
| /p biome | Sets your plot biome.
| /p music | Sets your plot music.
| /p chat | Switches the chat to the plot chat. Do the command again to talk to the global chat again.
| /p middle | Teleports you to the middle of a plot.
| /p toggle | Toggles you some settings. This may useful, or maybe not.
| /p flag<br>/p f | The flag command, see PLOT FLAGS.


These commands are useless in this server, you can check them out if you want.

```
/p save, /p download, /p set, /p plugin, /p merge, /p unmerge, /p inbox, /p comment
```

### Plot Flags

There are a lot of flags that you can use on your plot. First of all, you can use "/p flag add [flag] [value]" to add a flag, "/p flag delete [flag]" to delete a flag, and "/p flag set [flag] [value]" to set a flag. I will list some flags you need to know, and you can check the rest on "/p flag list". If some of the flag isn't set, nothing would happened.

| Flag | Description |
| --- | ---
| titles |	The text when you enter a plot (Owned by ...). This can be enabled or disabled by either "true" or "false" as the values.
| greeting | The chat text when you enter a plot. You can make any greeting text as the value. (even with color codes)
| farewell | The chat text when you leave a plot. You can make any farewell text as the value. (even with color codes)
| notify-enter | The text that notifies you and your visitors about someone who enters the plot. This can be enabled or disabled by either "true" or "false" as the values.
| notify-leave | The text that notifies you and your visitors about someone who leaves the plot. This can be enabled or disabled by either "true" or "false" as the values.
| fly | The ability to fly. This can be enabled or disabled by either "true" or "false" as the values.
| gamemode | The gamemode that will be set when someone enters your plot. The values are creative and survival.
| guest-gamemode | Same as the gamemode flag, but it will applies to the visitors. Notice that your gamemode won't affected.
| time | The time of your plot. The values are from 0 to 20000. (5000 is morning, 10000 is noon, 15000 is afternoon)
| weather | The weather of your plot. The values are rain and clear.
| music | The music that will be played on your plot. The values are the music disc IDs (2256-2267). It would be easier to use /p music.
| place<br>break<br>use | The block IDs that the visitor can place/break/use. If you want your visitors only able to use a chest, do "/p flag set use 54". If you want your visitors only able to use a chest and a wooden button, do "/p flag set use 54,143". Notice that I don't use a space to speperate the items. Set the value to 0 if you want your visitors can place/break/use anything.
| price | The price of your plot, if you want to sell it. The values are... the price of your plot. The visitors can use /p buy to buy a plot, if a price is set.
| no-worldedit | Disables WorldEdit on your plot. This can be enabled or disabled by either "true" or "false" as the values.
| item-drop | If set to false, visitors can't drop items on the plot. This can be enabled or disabled by either "true" or "false" as the values.
| disable-physics | Disables physics, such as falling blocks. This can be enabled or disabled by either "true" or "false" as the values.
| pvp |	The ability to fight versus player (PVP) for visitors. This can be enabled or disabled by either "true" or "false" as the values.

(I'm not sure what forcefield use)

These flags is rarely used in this server, you can check them out if you want.

```
feed, heal, invicible, instabreak, mob-cap, animal-cap, hostile-cap, entity-cap, vehicle-cap, drop-protection, pve, explosion, player-interact, hostile-interact, hostile-attack, animal-interact, animal-attack, tamed-interact, tamed-attack, misc-interact, hanging-place, hanging-break, vehicle-use, vehicle-place, vehicle-break, redstone, device-interact, liquid-flow, forcefield, modified-blocks, blocked-cmds, villager-interact, deny-exit, mycel-grow, ice-form, block-ignition, snow-melt, snow-form, ice-melt, fire-spread, sleep, gras-grow, liquid-flow, block-burn, soild-dry, mob-place, analysis, deny-teleport, done.
```
