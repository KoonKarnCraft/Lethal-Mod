# 1.9.0

### Added

-   `Individual enemy cap` settings to configure how many enemies of any type can spawn
-   `Min enemies to spawn` configuration for a more reliable challenge
-   `Starting enemies` configuration to set a minimum amount of enemies to spawn in the level

### Fixed

-   Error when all weather chances were set to 0
-   No weather probability now works correctly without the `Allow every weather` option

### Modified

-   `Enemy spawn configurations` are now split between outside and inside enemies
-   Patches now will execute after other mods so they will override their settings (or amplificate them)

# 1.8.2

### Fixed

-   Weather chances not syncing when the users joins a host without opening the menu

# 1.8.1

### Fixed

-   Fixed soft crash when a planet did not have weathers
-   Fixed outside enemy spawn probabilities not applying

# 1.8.0

### Added

-   Configuration `Weather probability override` allows the user to set the probabilities more consistently.
-   Configuration `Allow every weather` allows any weather on any planet.
-   Configuration `Turret spawn multiplier` to allow to change the amount of turrets on each level.
-   Configuration `Landmine spawn multiplier` to allow to change the amount of landmines on each level.

### Fixed

-   Weather changes are now more reliable

# 1.7.4

### Added

-   New configurations for `Daytime speed` and `Daytime speed mode`.

# 1.7.3

### Fixed

-   Quota variables now follow the vanilla game scaling (a more consistant raise)

### Modified

-   Added an image of how the menu looks like in the readme

# 1.7.2

### Fixed

-   Fixed an oppsie when adding the failsafe that made the mod not patch methods correctly

# 1.7.1

### Fixed

-   Added a patch for compatibility with [Don't touch me](https://thunderstore.io/c/lethal-company/p/Kittenji/Dont_Touch_Me/)
-   Now those mods without compatibility won't crash (added a failsafe)

# 1.7.0

### Added

-   New configuration for starting quota, quota increase and quota exponential increase

### Modified

-   Changed the mod icon. Do you like it?
-   Experience multiplier is no longer considered experimental

# 1.6.0

### Added

-   New configuration to modify weather chances

### Fixed

-   Added missing information to the mod readme

### Modified

-   Updated mod descriptions
-   Updated ConfigurableCompany dependency

# 1.5.4

### Added

-   New configuration **Experience multiplier** to modify the amount of experience you earn/lose while playing. _After testing seems to work correctly, however is marked as experimental just in case I missed something during sync_

### Modified

-   Configurations now display on their correct page

# 1.5.3

_Nothing added, just and update to make people know the mod works correctly_

# 1.5.2

### Added

-   Compatibility with v47

### Fixed

-   Code cleanup

# 1.5.1

### Fixed

-   Fixed enemy spawn probability not syncing with configuration value between matches

# 1.5.0

### Added

-   Individual enemy spawn probabilities

### Modified

-   Changed ship door config description to clarity what it does [Thanks to @rayneontop]

### Fixed

-   Modifying deadline days on an already existing game could cause enemies to now spawn

# 1.4.2

### Fixed

-   Corrected scrap value multiplication

# 1.4.1

### Fixed

-   Beehives now correctly show their scrap value multiplied

# 1.4.0

### Fixed

-   Fixed scrap multiplier to correctly calculate scrap values
-   Now the scrap price multiplier affects items such as keys and the lung apparatus
-   Project cleanup

# 1.3.0

### Added

-   Configuration to disable signal translator limit (terminal input limit remains)

### Fixed

-   Made sure every configuration works correctly with the new Config API, this includes changes to
-   Enemy power and capacity wont overflow themselves anymore
-   Changing the quota deadline wont break enemy spawn
-   Weather is now hided correctly in the planet description
-   Correctly set death penalty display
