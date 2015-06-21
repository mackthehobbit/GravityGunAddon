# GravityGunAddon
Addon for Minecraft Pocket Edition, which adds the Gravity Gun from Half-Life 2.
Inspired by iChun's PC mod (concept and item texture used with [permission](https://twitter.com/ohaiiChun/status/609983013447991296)).

For more info or support, please visit the [forum post](http://www.minecraftforum.net/forums/minecraft-pocket-edition/mcpe-mods-tools/2449773-0-11-1-gravity-gun-addon-pick-up-and-throw-mobs) or follow me on twitter [@mackthehobbit](http://twitter.com/mackthehobbit).

## Changelog
### v1.1:
 * The gravity gun can break blocks such as tall grass now
 * Added the Supercharged Gravity Gun - craftable with 1 Diamond, 4 Glowstone, 2 Iron Ingots, 1 Nether Reactor and 1 Obsidian
 * The mod is more balanced for survival mode now:
 	The force with which entities are pushed is proportional to the size of that entity
 	The normal gravity gun can only pick up smaller mobs (animals, spiders)
 	The supercharged gun can pick up humanoid + larger mobs, and pushes things much further
 * Fixed a few potential crashes involving empty hands
 * Fixed a potential problem with other mods setting the world time during cooldown
### v1.0.2:
 * Made picking up entities smoother (the player doesn't have to stand still to do so now)
 * Fixed a bug which made entities look like they take damage when pushing them
 * Added a (short) cooldown to pushing mobs
### v1.0.1:
 * Added a recipe for survival mode
 * Fixed in-hand rendering
### v1.0:
 * Initial release
 * The Gravity Gun is available in the creative mode inventory (weapons/tools tab)
 * Picking up/pushing/throwing mobs supported

## Todo
 * Open source?
 * Pick up boats/minecarts
 * Pick up blocks, like in the PC mod
 * Grab entities out of minecarts/boats?
 * Add weight of all riders on an entity

## Known issues
 * Entities twitch slightly when moving over chunk boundaries
 * Mobs' limbs move as though walking, when moving horizontally
 * Minecarts and boats cannot be picked up
 * Pushing a minecart with a mob inside while on rails continues moving for too long
