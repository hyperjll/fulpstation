## List of all TG edits:

- .github\workflows\compile_changelogs.yml > Same as above.

- code/datums/greyscale/_greyscale_config.dm > Adds our greyscales folder to the sanity check

- code/game/area/areas/shuttles.dm > Plays ApproachingFulp instead of ApproachingTG

- code/game/world.dm > Marked by a "FULP EDIT" comment; copies a bit of code to make 'GLOB.fulp_changelog_hash' functional.

- code/modules/client/preferences.dm > Marked by a "FULP EDIT" comment; gives clients the 'last_fulp_changelog' var.

- interface\interface.dm > Changes the value of 'name' on '/client/verb/changelog' to "/TG/ Changelog"

- README.md > Replaces it with our own readme

- tgui/packages/tgui/routes.tsx > Add custom routing so fulp-specific interfaces can be found and loaded

- tgstation.dme > Adds our files to be included when compiling

- tools/build/build.js > Adds our folder to be read for changes when compiling.

- tools/pull_request_hooks/autoChangelog.js > Changes changelog folder to fulp_modules/data/html/changelogs, to preserve them across TGUs.

- tools/deploy.sh > Adds Fulp's ``icon`` and ``greyscale/json_configs`` folders to the list of folders that RustG uses to compile icons.

## All Fulp files not contained within /fulp_modules/

- code/__DEFINES/fulp_defines > Contains all of our defines
- _maps/fulp_maps > Contains all of our non-station maps (Ruins, Deathmatch maps, etc.)
- tgui/packages/fulpui-patches > Adds all Fulp TGUI files
- code/modules/unit_tests/screenshots > Contains Fulp antag & species screenshots for unit tests.

#### Maps & Shuttles
- _maps/map_files/Heliostation/Heliostation.dmm
- _maps/heliostation.json
- _maps/map_files/Solitairestation.dmm
- _maps/Solitairestation.json
- _maps/pubbystation.json
- _maps/map_files/TheiaStation/TheiaStation.dmm
- _maps/theiastation.json
- _maps/shuttles/arrival_fulp.dmm
- _maps/shuttles/cargo_fulp.dmm
- _maps/shuttles/emergency_theia.dmm

#### TGUI
- tgui/packages/tgui/interfaces/PreferencesMenu/antagonists/antagonists/bloodsucker.ts
- tgui/packages/tgui/interfaces/PreferencesMenu/antagonists/antagonists/bloodsuckerbreakout.ts
- tgui/packages/tgui/interfaces/PreferencesMenu/antagonists/antagonists/ghostinfiltrator.ts
- tgui/packages/tgui/interfaces/PreferencesMenu/antagonists/antagonists/monsterhunter.ts
- tgui/packages/tgui/interfaces/PreferencesMenu/antagonists/antagonists/vampiricaccident.ts
- tgui/packages/tgui/interfaces/PreferencesMenu/preferences/features/game_preferences/antag_tips.tsx
- tgui/packages/tgui/interfaces/PreferencesMenu/preferences/features/fulp_species_features.tsx
