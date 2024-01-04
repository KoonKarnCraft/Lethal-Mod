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
