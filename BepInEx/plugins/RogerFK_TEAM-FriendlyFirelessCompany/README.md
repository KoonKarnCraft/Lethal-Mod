# Friendly Fireless Company
## _scale friendly fire to your heart's desire!_

# **EVERYONE IN THE SERVER IS REQUIRED TO HAVE THIS PLUGIN OR THEY WILL RECEIVE FRIENDLY FIRE!**
# Installation
I recommend using the Thunderstore app, but that's just me.

Otherwise, install inside the `BepInEx/plugins` folder like every other mod.


# Configuration
The config file is located at `BepInEx/config/FriendlyFirelessCompany.cfg`

**DamageScale**:
Multiplies the damage by the value set. 0 means no damage, 0.5 half damage, 1 full damage, 2 double damage, etc.
> Example:
> 
> `DamageScale = 0.5` will make all damage be half of what it normally is.

# Changelog
0.1.0 - Initial release. I haven't tested it thoroughly so if any enemy uses a player to damage another player, it might misbehave. Feel free to ping me to let me know in the [Lethal Company discord](https://discord.gg/XeyYqRdRGC).

# Disclaimers
## Untested stuff
- Setting the damage scale to negative values might heal the player. Consider it a preview for a "healing" mod I want to work on if it works.
- I haven't tried the Zap-Gun or Stun Grenades at all but I'm guessing they have nothing to do with it. If they do, let me know.
## Regarding the picture
The picture is clearly just a Bing AI picture paired with a very lazy Paint 3D job. I'm not an artist, I'm a programmer. I'm sorry if it bothers you, although I believe this petty thing shouldn't hurt anyone, I'm more than happy to change it! Feel free to make a better icon and send it to me through the Discord! Even hand-drawn stuff is fine, if it's better than this I'll use it. :)

# Changelog
### 0.1.0
Initial release
### 0.2.0
- Added hacky shotgun support. Please report any bug to the Discord, and feel free to ping me.
- Damage scaling value syncs with players who have FFC installed, and now requires LC_API to be installed.
    1. Friendly fire is correctly set to 1 (no change) when leaving and joining servers.
    2. Everyone needs the plugin for it to function correctly.
- Attaching ~~SCP-035~~ the Tragedy mask gives a window of opportunity for your teammates to bypass friendly fire.
### 0.2.1
- Fixed the user who used Tragedy once would have friendly fire permanently enabled for the remainder of the session (patch untested)

# Credits
- **RogerFK**, a.k.a. me. It took me like half an hour. In fact, it's taking me more to write this README, so I'm happy you actually read it. :)
    - Note: 0.2.0 took me a day's worth of work to make and test. Damn.