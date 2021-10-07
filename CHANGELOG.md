v2.1.0-neko: KillTips(only overlay) neko edition...

v2.0.9:
- Updated: deathmatch.ini file with new changes
- Updated: dm_spawn_time is now dm_spawn_protection_time
- Updated: Some more old syntax to new syntax
- Updated: Replaced EntData with EntProp (what is this 2009?!)
- Updated: dm_headshot_only_allow_client now uses clientprefs
- Updated: New HS Only translations (translators please help)
- Updated: M4A1-S ammo reserve from 40 to 60 (v1.36.3.8 update)
- Added: dm_replenish_ammo_empty - Replenish ammo when weapon is empty
- Added: dm_replenish_ammo_reload - Replenish ammo on reload action
- Added: dm_replenish_ammo_kill - Replenish ammo clip on kill
- Added: dm_replenish_ammo_type - Replenish type: 1) Clip only 2) Reserve only 3) Both
- Added: dm_loadout_style - When players can receive weapons
- Added: dm_fast_equip - Enable fast weapon equipping
- Added: Workshop map support for spawns
- Added: Tactical, molotov, and incendiary rewards on kill
- Fixed: Grenades not being rewarded after kill
- Fixed: Incorrect HP & AP not being rewarded after kill
- Fixed: Spawn information being sent more than once
- Fixed: dm_headshot_only_allow_client not used properly
- Fixed: Commands not being displayed to proper clients
- Fixed: HS Client Only chat triggers not working
- Fixed: Ammo replenish reserve and clip being used incorrectly
- Fixed: Secondary weapon arraylist incorrectly set
- Removed: Auto-Updater, security risk and no longer useful
- Removed: FindSendPropInfo and other unnecessary code
- Removed: dm_replenish_ammo_clip & dm_replenish_ammo_reserve

v2.0.8:
- Updated: Syntax and naming convention
- Updated: Compiled for SM 1.10+ & MM 1.11+
- Updated: Consistency checks when not needed for validity
- Updated: Load-out improvements for bots and players
- Updated: Many performance improvements to general code and structure
- Added: German language is now supported (thanks to Shoxxo)
- Added: Clientprefs - All weapons are now saved on the server after a complete selection
- Added: dm_nades_tactical - tactical grenade
- Added: Cookies are reset when the gunmode is changed, only reset to "none" if none is required
- Added: dm_cash_messages - Cash messages are now depressed by default
- Fixed: Weapons limit menu not being updated properly
- Fixed: Missing and corrected invalid configuration entries
- Fixed: Correct weapon and grenade given when killed while selecting
- Fixed: Menus being sent when unnecessary or at inappropriate times
- Fixed: Issues with bots sometimes not being given random weapons
- Fixed: Spawns for de_dust2
- Removed: Menu options "Same weapons every round" and "Random weapons every round"
- Removed: Unnecessary code and client checks

v2.0.7a:
- Fixed: dm_headshot_only not working properly
- Fixed: Knife, grenade, and taser damage not being allowed when dm_no_knife_damage was enabled
- Fixed: dm_headshot_only_allow_knife not working when dm_no_knife_damage was enabled

v2.0.7:
- Updated: Improved ammo replenish system
	- dm_replenish_ammo - (Default) 1 - Replenish ammo on reload
	- dm_replenish_ammo_clip - (Default) 0 - Replenish ammo clip on kill
	- dm_replenish_ammo_reserve - (Default) 0 - Replenish ammo reserve on kill
- Updated: SDKHook performance and usage (thanks to Bacardi)
- Added: Support for late load, safely load the plugin at anytime
- Added: Primary only gun mode
	- dm_gun_menu_mode - (Default) 1 - 1) Enabled 2) Primary weapons only 3) Secondary weapons only 4) Random weapons only 5) Disabled
- Added: No knife damage
	- dm_no_knife_damage - (Default) 0 - Knives do NO damage to players
- Fixed: Wrong language phrase for secondary weapons when not selected
- Fixed: Native "SetConVarInt" reported: Invalid convar handle 0 (error 4)
- Fixed: Native "PrintHintText" reported: Language phrase "^" not found
- Fixed: P2000 sounding like a deagle P2000 must now be equipped in player's load-out

v2.0.6:
- Updated: Plugin name changed to correctly match the game it was designed for
- Updated: Overhaul on syntax, now using 18+ syntax!
- Updated: Spawns for de_nuke & de_cache
- Updated: Translation file
- Added: Compatibility for Valve's Deathmatch (game_type 1 & game_mode 2) or Custom (game_type 3 & game_mode 0)
	- dm_valve_deathmatch - (Default) 0 - Enable compatibility for Valve's Deathmatch (game_type 1 & game_mode 2) or Custom (game_type 3 & game_mode 0)
- Added: Armor addition, players now can gain armor
	- dm_ap_max - (Default) 100 - Maximum Armor Points (AP)
	- dm_ap_kill - (Default) 5 - Armor Points (AP) per kill
	- dm_ap_headshot - (Default) 10 - Armor Points (AP) per headshot kill
	- dm_ap_knife - (Default) 50 - Armor Points (AP) per knife kill
	- dm_ap_nade - (Default) 30 - Armor Points (AP) per nade kill
	- dm_ap_messages - (Default) 1 - Display AP messages
- Added: Enable or disable sounds (bodyshots & headshots)
	- dm_sounds_bodyshots - (Default) 1 - Enable the sounds of bodyshots
	- dm_sounds_headshots - (Default) 1 - Enable the sounds of headshots
- Fixed: Weapon skins for all but (usp-s & hkp2000)
- Fixed: Welcome message creating an invalid index
- Fixed: Damage Panel creating an invalid index
- Fixed: Spawn system not correctly judging LoS

v2.0.5:
- Added: New R8 weapon
- Added: Hide radar for all players
- Fixed: Incorrect ammo for shared weapon names
- Fixed: Welcome message not working

v2.0.4d:
- Fixed: Chest armor not working if full armor wasn't selected (thanks to sk1ll)

v2.0.4c:
- Added: BuildPaths, you can now utilize different SM paths
- Added: Brazilian translation (thanks to Rbt)

v2.0.4b:
- Fixed: Armor not spawning on player

v2.0.4a:
- Fixed: Translation file, incorrect color syntax due to new include
- Added: Polish translation (thanks to szyma94)

v2.0.4:
- Fixed: Random weapons not parsing from the deathmatchini
- Fixed: Error: Line 1051, deathmatchsp::Event_Say()
- Fixed: Error: Line 1730, deathmatchsp::RefillWeapons()
- Fixed: Display panel not being shown despite being set yes in deathmatchini file
- Fixed: Spawn location glitches on maps
- Added: New spawn locations for new maps
- Added: Armor (chest) & Armor (full)
- Added: dm_replenish_grenade_kill (Give players their grenade back on successful grenade kill)

v2.0.3:
- Changed the way ammo replenish works (thanks to int64 Shrandy)
- Added new cvars:
	- dm_replenish_ammo & dm_replenish_clip
	- dm_display_panel & dm_display_panel_damage
- Added new display panel for damage info
- Added Multi-Lanugage support
	- English Supported
	- Spanish Supported
	- French Supported
- Added csgocolors (need csgocolorsinc for compiling)
- Fixed blood splatter issue when turning hsonly off & on
- Fixed bots not having or not equiping guns
- Fixed timer message (client index 0)

v2.0.2c:
- Fixed an issue with same all not remembering it's job

v2.0.2b: 
- Added Pistol only mode, available through gun_menu_mode
- Fixed issue with welcome message
- Fixed issue with bots and weapons (hopefully)
- Fixed issue with gun menu being available to admins when it shouldn't

v2.0.2a:
- Fixed issue with spawning with wrong weapon or no knife
- Fixed Headshot Only mode displaying blood on body shots
- Fixed minor issues that went unnoticed
- Added support for 3rd party knife plugins
- A thank you to klexen & Kryptos

v2.0.2:
- Added Headshot Only mode
	- Allow world kills
	- Allow knife kills
	- Allow taser kills
	- Allow grenade kills
- Added HP for grenade kills
- Fixed Native "IsClientInGame" reported: Client index 0 is invalid
- Fixed Native "SetEntProp" reported: Entity 1 (1) is invalid
- A thank you too versatile_bfg again

v2.0.1:
- Added spawn points for maps de_cbble & de_overpass
- Changed plugin to allow load without updater dependency
- A thank you too versatile_bfg

v2.0.0:
- Initial Public Release
