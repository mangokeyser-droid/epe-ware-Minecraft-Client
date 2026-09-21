Installation
Install Fabric Loader for Minecraft 1.21.5 using the official installer — click Install, and pick the 1.21.5 game version.
Download Fabric API for 1.21.5 from Modrinth or CurseForge.
Open your Minecraft folder:
Windows — press Win + R, type %appdata%\.minecraft, press Enter
macOS — ~/Library/Application Support/minecraft
Linux — ~/.minecraft
If there is no mods folder inside it, create one.
Drop both these files into mods:
epe-ware-1.0-SNAPSHOT.jar
fabric-api-<version>.jar
Launch Minecraft and select the Fabric 1.21.5 profile.
Press INSERT in-game to open the ClickGui.
That's it — no other setup needed.

Troubleshooting
Problem	Fix
Mod doesn't appear in-game	Make sure Fabric Loader and Fabric API are both installed for 1.21.5, and that the jar is directly in mods (not in a subfolder).
Game crashes on startup	Usually a missing Fabric API, or the mod is on the wrong Minecraft version.
Nothing shows up / no menu	Press INSERT (the default menu key). If it conflicts, rebind it in the ClickGui.
Game won't start at all	Confirm you launched the Fabric profile, not the default vanilla one.
Disclaimer
This client is intended for private worlds, testing, and servers where client-side utilities are permitted. Server rules always take precedence — using client-side mods on servers that disallow them can get you banned.

Credits
Built on top of the open-source OyVey client base. Full credit to:

3arthqu4ke
alpha432
cattyn (@cattyngmd) — OyVey ported to 1.21.5
Original project: https://github.com/cattyngmd/oyvey-ported — licensed under the MIT License, which epe-ware keeps intact.

Need help? contact me on discord: epezejoko
