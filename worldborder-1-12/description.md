This plugin is intended to efficiently provide a border for each of your worlds, which only people granted special bypass access are allowed beyond. These borders can be round/elliptic or square/rectangular. As the plugin has been written with performance as the most important goal, it should have no performance impact on your server. Additional world trimming and filling commands are available as well.

## Features

- You can set up a separate border for each world, but only one border per world.
- You can have either round/elliptic or square/rectangular borders. Square/rectangular borders are slightly higher performance, round/elliptic borders make for nicer display maps. - Different worlds can have different border shapes if you so choose.
- Configuration and border setup is done completely using commands in-game or through the server console. No need to ever edit the config file directly.
- Support for all permission plugins which interface with Bukkit's built-in "superperms" permission system.
- You can fully generate (fill) your world all the way to the border, filling in any missing chunks, including a configurable buffer zone just outside your border.
- You can trim off any world chunks beyond the border, getting rid of extraneous parts, with a configurable buffer zone left just outside your border.
- You can use a bypass command to allow specific players to go beyond all borders.
- Borders can be automatically displayed in DynMap if you use that plugin.
- All plugin data is automatically saved whenever any borders or settings are changed.
- If a player crosses a border while in a vehicle, the momentum of the vehicle is stopped and it is moved back inside the border with the player.
- When a player is moved back inside a border, they will be moved to a safe vertical location if needed.
- Borders for specific worlds can be set to wrap around instead of just knocking back players who cross the border, instead sending them to the opposite edge of the border.
