# Lethal company variables

[Contact me](###Additional-info)
[Compatibility](###Compatibility)

This mod allows the user (you) to modify the game to your liking. All within the game with a configuration menu that allows you to have different settings on each save file.

There are still plenty of configurations im planning to add in the future. You can submit your suggestions by contacting me or in the corresponding thread in the [Lethal company modding discord](https://discord.com/invite/lcmod).

![Ingame image of the configuration menu](https://i.imgur.com/tXdIKgF.png)

**[`Host`]** Configurstions mean only the host needs the mod.  
**[`Host` & `Client`]** Mean both host and the client need the mod installed. Configuration will sync automatically.

The list of options you can modify:

-   ### **Enemy spawn multiplier** [`Host`]

    Modifies the amount of enemies that spawns each in-game hour
    _Keep in mind that there are two other limit for the amount of enemies that can be spawned, those are **Enemy power level** and **Enemy cap**._

    > **WARNING**  
    > This configuration does not affect the spawn of turrets or landmines, you should use it's configuration.

-   ### **Min enemies to spawn** [`Host`]

    Allows to set a fixed amount of enemies that will spawn every hour
    This setting still follows the spawning rules so if the maximum power or capacity is reached, enemies won't spawn.  
    _This value is not affected by **Enemy spawn multiplier** settings._

-   ### **Starting enemies** [`Host`]

    Change the amount of enemies that will be on the planet when you land.
    _This value is not affected by **Enemy spawn multiplier** settings._

-   ### **Enemy power multiplier** [`Host`]

    Modifies the maximum of total enemies that can be spawned on the level, both inside and outside enemies are affected.  
    _There is still an **individual cap** for evey enemy._

-   ### **Enemy cap multiplier** [`Host`]

    Modifies the maximum amount of each individual enemy.
    _For example there is a maximum of 5 coil-heads in the level, now you can modify that!_

-   ### **Starting money** [`Host`]

    Allows you to customize the amount of money you start the game with

-   ### **Deadline days** [`Host`]

    Changes the amount of days you have to fulfill the quota

-   ### **Hide weather** [`Host` & `Client`]

    Hides the level weather and replaces it with an **(Unknown)** mark.

-   ### **Scrap amount multiplier** [`Host`]

    Multiplies how much scrap will spawn on the level  
    _(Does not change the amount of beehives)_

-   ### **Scrap price multiplier** [`Host`]

    Changes the value of the scrap. This works for every kind of scrap, even items such as Keys and the Apparatus

-   ### **Player death penalty** [`Host` & `Client`]

    Changes the percent of credits that you lose for each individual death (setting it to 100% will clear all your money, even if just **one** player dies and their body is not recovered)

-   ### **Ship door power** [`Host`]

    Modifies how long can the ship door remain closed.  
    Greater values mean the door will remain closed for a longer time before overheating, thus automatically opening.

-   ### **Disable ship item limit** [`Host`]

    Disables the default limit of items inside the ship.

-   ### **Disable signal translator limit** [`Host` & `Client`]

    Disables the default limit of 10 characters that the signal translator has.

    > **INFO**  
    > Does not change the limit of the terminal input (a config for that will be added in future releases)

-   ### **Enemy spawn probability multiplier** [`Host`]

    Allow to modify the chances of every single enemy in the game to spawn.  
    This configuration is dynamically generated for each registered enemy type so if other mods implement their enemies correctly, they will also work with this configuration.

-   ### **Experience multiplier** [`Host` & `Client`]

    Allows to modify how much experience you earn by playing. (Keep in mind experience can be both gained or lost and this multiplier will affect both).

-   ### **Weather chance multipliers** [`Host` & `Client`]

    Change how often planets will have a specific weather.
    Also allows you to change the behavior of how weather is choosen for a more reliable configuration or a more vanilla-like experience.  
    _This configuration is dynamically generated for each registered weather so if other mods implement their weathers with the game enumeration, they will be compatible_.

-   ### **Allow every weather** [`Host` & `Client`]

    Allows every planet to have any weather (Keep in mind that this might be unfair in some maps with specific weathers)

-   ### **Starting quota** [`Host`]

    Sets the quota that the game starts with, this value is only used then you create the game file.

-   ### **Quota increase base** [`Host`]

    Sets the quota that will be added after each completed deadline. _Keep in mind that this is the base value and will be scaled according to the rest of the configuration_.

-   ### **Quota steepness** [`Host`]

    Smooths out how much quota is raised after each deadline. Higher values mean the quota will raise slower.

-   ### **Quota multiplier** [`Host`]

    Allows to modify how much quota is added after each deadline by multiplying the `increase base`.

-   ### **Daytime speed** [`Host`]

    Allows you to change the speed at which the day passes. Higher values mean the day will last less.

-   ### **Daytime speed mode** [`Host` & `Client`]

    Changes how hours should pass by in the game, has two modes.

    -   **Balanced**: Works as vanilla, the day starts the moment you step on a planet.
    -   **Fixed**: Time won't pass until the ship landes.

-   ### **Turret spawn multiplier** [`Host`]

    Changes the amount of turrets that can spawn with the level (high values will grant at least one spawn)

-   ### **Landmine spawn multiplier** [`Host`]

    Changes the amount of landmines that can spawn with the level (high values will grant at least one spawn)

This mod makes use of my other mod [ConfigurableCompany](https://thunderstore.io/c/lethal-company/p/AMRV/ConfigurableCompany/). If you are a modder, you might want to look at it ;)

---

### Compatibility

No compatibility issues.

Every mod that adds a new enemy is compatible and the eneny will be shown in the config.

If you find any, contact me and will be fixed asap.

> **WARNING**  
> Keep in mind if another mod changes the same features as this mod, these settings might not work.

---

### Additional info

![the_ansuz](https://img.shields.io/badge/Discord_user-the__ansuz-5865F2?style=flat&logo=discord&logoColor=%237f8afa&link=https%3A%2F%2Fdiscordapp.com%2Fusers%2F341967365908594700)

![Modding discord](https://img.shields.io/badge/Discord_server-Lethal_company_modding-5865F2?style=flat&logo=discord&logoColor=%237f8afa&link=https%3A%2F%2Fdiscord.com%2Finvite%2Flcmod)

If you find any issue or have any suggestion, feel free to [contact me](https://discordapp.com/users/341967365908594700) or ask in the [discord's corresponding channel](https://discord.com/channels/1168655651455639582/1193627690960437369).
