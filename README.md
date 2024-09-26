# cs2nadelineuppracticeconfig
a cs2 config to practice nade lineups on listen servers, originally meant for online servers but also usable offline
## Usage:
place the config file in the following directory:
`{cs2 directory}/game/csgo/cfg` (not to be confused with `{cs2 directory}/csgo/cfg`)
and execute it in the console by typing `exec practice.cfg`

alternatively, bind a key to execute it by typing in the console `bind KEY "exec practice.cfg"` (replace KEY with whatever key you'd like to press)

additional recommendations: binding `noclip`, `sv_rethrow_last_grenade` (only usable by the listen server host), and `"ent_fire smokegrenade_projectile kill"` (also only usable by the listen server host) to noclip around the map, rethrow the last grenade thrown, and kill smokes when necessary.
