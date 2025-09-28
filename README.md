made with [packwiz](https://packwiz.infra.link/)

## Mods list
everything is *vanilla-friendly* and mostly client-side

QoL improvements that add/change functionality
1. BetterF3
2. client-tweaks - minor things like stop placing offhand torches with food in hand
3. controlling - keybind search
4. essential - easy playing with friends
5. infinite-music - it pauses when you play disc music
6. lamb dynamic lights - glowing blocks glow when held in hand
7. lighty - light overlay to see where mobs spawn
8. mod menu - show installed mods and quickly adjust mod configss
9. Mouse Tweaks - QoL inventory management
10. stack-to-nearby-chests - Terraria "quick stack" button
11. TrashSlot - delete unwanted items

performance optimizations
1. bad optimizations
2. c2me-fabric - massive chunk load speed boost
3. cull-less-leaves
4. entity culling
5. more culling
6. ferrite-core - halves RAM usage
7. ksyxis - faster world load
8. lithium
9. noisium - faster worldgen
10. sodium
11. sodium extra - more setting options, e.g. 96 render distance

pure cosmetics
1. 3D skin layers
2. blur-plus - blur background when opening inventory/UI's
3. iris - ✨shaders✨
4. simple-health-bar
5. Zoomify

<br>

## Working with modpack
Update mods using `+update-mods.bat`
Add mods using [this command reference](https://packwiz.infra.link/tutorials/creating/adding-mods/)

To add configs for the mods
1. Create a test client ([guide](https://packwiz.infra.link/tutorials/installing/packwiz-installer/)) and start the game.
    1. use `+run-server-locally.bat` to get the server URL
2. The mods will create their config files.
3. Edit them either using a text editor (configs are stored in `<client instance>\.minecraft\config\`), or in-game using `mod-menu` (included in modpack).
4. Once configured, copy-paste the config files you *care about* into `<modpack>\config\`.

Once done making changes, run `+refresh.bat`
