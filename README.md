# cs2practiceconfig
a CS2 config for practicing nade lineups and wallbangs on listen servers, originally meant for online servers but also usable offline
## Usage:
download and place the config file `practice.cfg` in the following directory:
`{CS2 folder}/game/csgo/cfg` (not to be confused with `{CS2 folder}/csgo/cfg`, which would exist if CS:GO is installed alongside CS2), to open CS2's folder in your file browser, right click on the game in your Steam library, and click "Browse Local Files" under Manage
and start a server, then execute it in the console by typing `exec practice.cfg`

alternatively, bind a key to execute it by typing in the console `bind KEY "exec practice.cfg"` (replace KEY with whatever key you'd like to press)

## additional recommendations:
binding `noclip`, `sv_rethrow_last_grenade` (only usable by the listen server host), and `"ent_fire smokegrenade_projectile kill"` (also only usable by the listen server host) to noclip around the map, rethrow the last grenade thrown, and kill smokes when necessary.
