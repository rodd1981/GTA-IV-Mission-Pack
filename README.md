# GTA IV Mission Mod Pack (Source Code - for DEVS only!)

Source code for the GTA IV Mission Mod Pack V2.0 (it also comes with an API library coded by myself - very useful for those wanting to create new missions).

# Special thanks

Alex Blade - SCOCL (This mod wouldn't exist without this great tool).

Cosy       - Thanks for sharing the source code of your mini-menu (it was really useful to improve the UI of the missions).

Skorpro    - Thanks for sharing the source code of your ASI SCO Loader.

OhManMyBad - Thanks for sharing the source code of your GTA V Teleportation. 

# Requirements

SCOCL (to compile missions - Download: http://www.dev-c.com/gtaiv/scocl/)

# Installation

- Create a new directory and extract all files.
- Use SCOONE (to compile a single C source file) or SCOALL (to compile all C source files)
- Make sure you have SCOCL set on your PATH environment variable before compiling the sources

# Usage

Compile new missions: scoone <mission.c>
Compile all missions: scoall

- Source files should be sitting on the root directory
- SCO version will be written in PC directory

# Requirements

SCOCL (already added to the repo).

# License

As of November 1, 2015 Chat API is licensed under the GPLv3+: http://www.gnu.org/licenses/gpl-3.0.html.

# Legal

- If you make money off of it, please consider donating

# Misc

- Pull requests and improvements are always welcome
- Let me know if you port this to ScriptHook (I am in the hope that someone does that - preferrably aiming for a Mission Creator, similar to GTA V's).
