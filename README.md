<p align="center">
	<a href="https://www.maxximou5.com/">
		<img src="https://www.maxximou5.com/sourcemod/assests/img/deathmatch_csgo.png" alt="csgo deathmatch plugin" width="600" alt="csgo-deathmatch-logo">
	</a>
    <br>
    <a href="https://github.com/Maxximou5/csgo-deathmatch/releases">
        <img src="https://img.shields.io/github/release/Maxximou5/csgo-deathmatch.svg?style=flat-square" alt="Version">
    </a>
    <a href="https://github.com/Maxximou5/csgo-deathmatch/stargazers">
        <img src="https://img.shields.io/github/stars/Maxximou5/csgo-deathmatch.svg?style=flat-square" alt="Stars">
    </a>
    <a href="https://github.com/Maxximou5/csgo-deathmatch/network">
        <img src="https://img.shields.io/github/forks/Maxximou5/csgo-deathmatch.svg?style=flat-square" alt="Forks">
    </a>
    <a href="https://raw.githubusercontent.com/Maxximou5/csgo-deathmatch/master/LICENSE">
        <img src="https://img.shields.io/badge/license-GPLv3-blue.svg?style=flat-square" alt="License">
    </a>
    <a href="https://github.com/Maxximou5/csgo-deathmatch/issues">
        <img src="https://img.shields.io/github/issues/Maxximou5/csgo-deathmatch.svg?style=flat-square" alt="Issues">
    </a>
    <a href="https://travis-ci.org/Maxximou5/csgo-deathmatch">
        <img src="https://img.shields.io/travis/Maxximou5/csgo-deathmatch.svg?style=flat-square" alt="Issues">
    </a>
</p>

#### **[CS:GO] Deathmatch** - Enables deathmatch style gameplay (respawning, gun selection, spawn protection, etc).
*部分代码来自中国Neko社区大佬[Bklol](https://github.com/bklol/).**
### Main Features

- Weapon Menu
- Loadout Style
- Free For All (FFA)
- Client Preferences
- Workshop Map Support
- Display Panel for Damage
- Different Game Modes:
	- Headshot Only
	- Primary Weapons Only
	- Secondary Weapons Only
	- Random Weapons Only
- No Knife Damage (Guns Only)
- Objective Removal (C4/Hostage)
- Spawn Editor, Menu, and Statistics
- Fast Weapon Equip
- Replenish Grenades
- Replenish Ammo & Clip
- Hide Radar for Players
- Hide Award and Grenade Messages
- Kill Reward (HP/AP/Ammo/Grenades)
- Line of Sight Spawning
- 3rd Party Knife Plugin Support
- Multi-Language Support
	- English Supported
	- Spanish Supported
	- French Supported
	- Polish Supported
	- Brazilian Supported
	- German Supported

### Features to Add

- Integrated Stats (ELO)
- Team Selective Spawns

### Commands

- dm_spawn_menu - Opens the spawn point menu.
- dm_respawn_all - Respawns all players.
- dm_stats - Displays spawn statistics.
- dm_reset_stats - Resets spawn statistics.

### ConVars

	dm_enabled - (Default) 1 - Enable Deathmatch.
	dm_valve_deathmatch - (Default) 0 - Enable compatibility for Valve's Deathmatch (game_type 1 & game_mode 2) or Custom (game_type 3 & game_mode 0).
	dm_welcomemsg (Default) 1 - Display a message saying that your server is running Deathmatch.
	dm_free_for_all - (Default) 0 - Free for all mode.
	dm_hide_radar - (Default) 0 - Hides the radar from players.
	dm_display_panel - (Default) 0 - Display a panel showing health of the victim.
	dm_display_panel_damage - (Default) 0 - Display a panel showing damage done to a player.
	dm_sounds_bodyshots - (Default) 1 - Enable the sounds of bodyshots.
	dm_sounds_headshots - (Default) 1 - Enable the sounds of headshots.
	dm_headshot_only - (Default) 0 - Headshot only mode.
	dm_headshot_only_allow_client - (Default) 1 - Enable clients to have their own personal headshot only mode.
	dm_headshot_only_allow_world - (Default) 0 - Enable world damage during headshot only mode.
	dm_headshot_only_allow_knife - (Default) 0 - Enable knife damage during headshot only mode.
	dm_headshot_only_allow_taser - (Default) 0 - Enable taser damage during headshot only mode.
	dm_headshot_only_allow_nade - (Default) 0 - Enable grenade damage during headshot only mode.
	dm_remove_objectives - (Default) 1 - Disables bomb sites, and removes c4 and hostages.
	dm_respawning - (Default) 1 - Enable respawning.
	dm_respawn_time - (Default) 1.0 - Respawn time.
	dm_gun_menu_mode - (Default) 1 - 1) Enabled. 2) Primary weapons only. 3) Secondary weapons only. 4) Random weapons only. 5) Disabled.
	dm_los_spawning - (Default) 1 - Enable line of sight spawning.
	dm_los_attempts - (Default) 10 - Maximum attempts to find a suitable line of sight spawn point.
	dm_spawn_distance - (Default) 0 - Minimum distance from enemies at which a player can spawn.
	dm_spawn_protection_time - (Default) 1.0 - Spawn protection time.
	dm_loadout_style - (Default) 1 - When players can receive weapons. 1) On respawn. 2) Immediately.
	dm_fast_equip - (Default) 0 - Enable fast weapon equipping.
	dm_no_knife_damage - (Default) 0 - Knives do NO damage to players.
	dm_remove_weapons - (Default) 1 - Remove ground weapons.
	dm_replenish_ammo_empty - (Default) 1 - Replenish ammo when weapon is empty.
	dm_replenish_ammo_reload - (Default) 0 - Replenish ammo on reload action.
	dm_replenish_ammo_kill - (Default) 1 - Replenish ammo clip on kill.
	dm_replenish_ammo_type - (Default) 2 - Replenish type. 1) Clip only. 2) Reserve only. 3) Both.
	dm_replenish_grenade - (Default) 0 - Unlimited player grenades.
	dm_replenish_hegrenade - (Default) 0 - Unlimited hegrenades.
	dm_replenish_grenade_kill (Default) 0 - Give players their grenade back on successful kill.
	dm_hp_start - (Default) 100 - Spawn HP.
	dm_hp_max - (Default) 100 - Maximum HP.
	dm_hp_kill - (Default) 5 - HP per kill.
	dm_hp_headshot - (Default) 10 - HP per headshot kill.
	dm_hp_knife - (Default) 50 - HP per knife kill.
	dm_hp_nade - (Default) 30 - HP per nade kill.
	dm_hp_messages - (Default) 1 - Display HP messages.
	dm_ap_max - (Default) 100 - Maximum Armor Points (AP).
	dm_ap_kill - (Default) 5 - Armor Points (AP) per kill.
	dm_ap_headshot - (Default) 10 - Armor Points (AP) per headshot kill.
	dm_ap_knife - (Default) 50 - Armor Points (AP) per knife kill.
	dm_ap_nade - (Default) 30 - Armor Points (AP) per nade kill.
	dm_ap_messages - (Default) 1 - Display AP messages.
	dm_nade_messages - (Default) 1 - Disable grenade messages.
	dm_cash_messages - (Default) 1 - Disable cash award messages.
	dm_armor - (Default) 0 - Give players chest armor.
	dm_armor_full - (Default) 1 - Give players full armor.
	dm_zeus - (Default) 0 - Give players a taser.
	dm_nades_incendiary - (Default) 0 - Number of incendiary grenades to give each player.
	dm_nades_molotov - (Default) 0 - Number of molotov grenades to give each player.
	dm_nades_decoy - (Default) 0 - Number of decoy grenades to give each player.
	dm_nades_flashbang - (Default) 0 - Number of flashbang grenades to give each player.
	dm_nades_he - (Default) 0 - Number of HE grenades to give each player.
	dm_nades_smoke - (Default) 0 - Number of smoke grenades to give each player.
	dm_nades_tactical - (Default) 0 - Number of tactical grenades to give each player.

### Compatibility

This plugin is tested on the following Sourcemod & Metamod Versions.

- <a href="https://www.sourcemod.net/downloads.php">Sourcemod 1.10.0+</a>
- <a href="https://www.sourcemm.net/downloads.php">Metamod 1.11.0+</a>

### Requirements

None.

### Instructions

- Extract zip file and place files in the corresponding directories of **/addons/sourcemod**
- /configs/deathmatch/deathmatch.ini
- /configs/deathmatch/spawns/*.txt
- /plugins/deathmatch.smx
- /scripting/deathmatch.sp (necessary only for compiling)

### Changelog

To view the most recent changelog visit the <a href="https://github.com/Maxximou5/csgo-deathmatch/blob/master/CHANGELOG.md">changelog</a> file.

### Download

Once installed, the plugin will update itself as long as you've done as described in the requirements section; otherwise, downloaded the latest release below.
Please download the latest **deathmatch.zip** file from <a href="https://github.com/Maxximou5/csgo-deathmatch/releases">my releases</a>.

### Bugs

If there are any bugs, please report them using the <a href="https://github.com/Maxximou5/csgo-deathmatch/issues">issues page</a>.

### Credit

A thank you to those who helped:

- <a href="https://forums.alliedmods.net/member.php?u=187003">Snip3rUK</a> (<a href="https://forums.alliedmods.net/showthread.php?t=189577">Original Plugin</a>)
- <a href="https://forums.alliedmods.net/member.php?u=26021">Dr!fter</a> (General Code Support)
- <a href="https://steamcommunity.com/id/DoomHammer69/">DoomHammer</a> (Debugging and Testing)
- <a href="https://steamcommunity.com/id/int64shrandy/">int64 Shrandy</a> (Fixing Ammo)
- <a href="https://forums.alliedmods.net/member.php?u=255924">szyma94</a> (Polish Translation)
- <a href="https://forums.alliedmods.net/member.php?u=260574">Rbt</a> (Brazilian Translation)
- <a href="https://forums.alliedmods.net/member.php?u=245683">splewis</a> (Weapon Skins Implementation)
- <a href="https://github.com/Shoxxo">Shoxxo</a> (German Translation)
- <a href="https://steamcommunity.com/profiles/76561198098268870/">MAJOR</a> (Debugging and Testing)

### Donate

If you think I am doing a good job or you want to buy me a beer or feed my cat, please donate.
Thanks!

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VSHQ7J8HR95SG"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" alt="csgo deathmatch plugin donate"/></a>
