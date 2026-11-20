# Classic Item Slots with Smart HUD & Classic Tweaks

*Code written with AI assistance (Claude Opus 5.5)*

**Classic Item Slots & Smart HUD for Ocarina of Time (Switch 2), version 1.1.1**

Default Layout

<img width="327" height="216" alt="Default layout" src="images/default-layout.png" />

Slots Only

<img width="258" height="149" alt="Slots only layout" src="images/slots-only.png" />

N64 Layout

<img width="497" height="142" alt="N64 layout" src="images/n64-layout.png" />


Legacy style item buttons: ZR plus three extra item slots (X, L, R), set separately for young and adult Link, with a
new context sensitive HUD. Removed control guides from bottom of screen.

## Download

Version 1.4.6:

- **Lichii**: [Classic-Item-Slots-v1.4.6.zip](https://github.com/sonofsilvanus/OoTNS2-Classic-Item-Slots/releases/download/v1.4.6/Classic-Item-Slots-v1.4.6.zip) (Switch buttons), [Classic-Item-Slots-v1.4.6-Xbox.zip](https://github.com/sonofsilvanus/OoTNS2-Classic-Item-Slots/releases/download/v1.4.6/Classic-Item-Slots-v1.4.6-Xbox.zip) or [Classic-Item-Slots-v1.4.6-PlayStation.zip](https://github.com/sonofsilvanus/OoTNS2-Classic-Item-Slots/releases/download/v1.4.6/Classic-Item-Slots-v1.4.6-PlayStation.zip). Install only one.
- **Longshot (PC)**: [Longshot-OoT-Mods-v2.zip](https://github.com/sonofsilvanus/OoTNS2-Classic-Item-Slots/releases/download/v1.4.6/Longshot-OoT-Mods-v2.zip) (see [Longshot (PC)](#longshot-pc) below).

**[Download the latest version](../../releases/latest)**: `Classic-Item-Slots-vX.zip` (Switch buttons), `-Xbox` or
`-PlayStation`. Install only one.

## Features

* Now with themes and in-game customizable layout!
* Assign multiple items from Items menu: up to 3 extra item slots on L, X (or B) and R.
* Context sensitive A/ZR buttons that flip dynamically N64 style
* Move, resize or hide the game's hearts, magic meter, D-pad row and map too
* Removed Tutorials/Control Guides
* Features from other mods:
  * Classic Enemy Respawn: dungeon enemies respawn when you leave a room and come back.
  * Classic Targeting: classic-style Z-targeting and aiming.
  * Disable Snap-to-Target: Link no longer homes or slides toward nearby enemies/objects when you swing without targeting.
  * Classic Hit Sounds: N64-style sword and projectile hit sounds.
  * Classic Puzzle Chime: the N64 puzzle-solved chime.

### What's new in v1.4.6

* HUD editor: your layout is now kept in option.sav and shared by every save. Older saves' settings move there the first time they load.
* HUD editor: the hearts, magic meter, D-pad row and map can each be made see-through.
* Faster: the game's state is looked up once per controller read.

## How to use it

Item selection is from the pause menu's Items tab like the original game. Use ZL and ZR to change tabs. Pressing A on
a highlighted item assigns it to ZR like default. Pressing X, L or R on the highlighted item assigns it to that slot.

X in the Items menu assigns to whichever button Put Away was on, so if X is your jump button it goes to B instead. For
this reason Swap Jump Controls is recommended, but it works either way.

With the Put Away button now free for an item slot, Put Away is on A when you're standing still, like the original
game. It won't happen while you're targeting with ZL, and with a bomb out A drops it instead.

While targeting with ZL, A says Jump when the stick is held back or to the side (back flip, side hop), and A with the
stick centered does the jump attack without having to hold forward. On a horse, A says Go and the jump button says
Dismount.

All tutorial control guides are removed for cleaner look and moved to the A and ZR buttons that are context sensitive
and flip N64 style when they change. Shows ammo counts and casts left for magic spells. The pause menu shows your
assignments under the rupee counter.

## In-game editor controls (Switch)

Click both sticks together when playing or paused to enter edit mode. Controls as follows:

| Button | Does |
|---|---|
| L / R | Switch layout, currently three themes: Default button diamond, item slots only, and N64 style. |
| Left stick ← / → | Cursor selects between whole cluster or individual element, then (while playing) the game's hearts, magic meter, D-pad row and map. These keep the same place in every layout. |
| Left stick ↑ / ↓ | Adjust scale |
| Right stick ↑ / ↓ | Adjust opacity |
| D-pad | Adjust position |
| X | Hide/show element |
| Y | Reset element's size and position |
| Minus | Reset to default layout, hidden elements stay hidden. |
| A | Save and close edit mode |
| B | Undo changes and close edit mode. |

## Requirements

- Ocarina of Time (Switch 2), version 1.1.1
- Tested with Lichii, launching the game's .nup (booting an extracted folder won't load the mod's code and the game
  won't start)

## Install (Lichii)

1. Right click game > Configure game
2. Import mod from ZIP
3. Toggle it on

## Install (Longshot)

* Ensure Longshot Launcher is up to date and game is on latest nightly, tested on v623 as of latest build.
* Build the game once in the Longshot Launcher if you never have.
* Ensure Longshot Launcher is up to date and game is on latest nightly,
* Extract the whole ZIP anywhere and double-click Install or remove mods.cmd. If Windows warns, choose More info > Run anyway (the scripts are plain text).
* It finds your Longshot game folder (or asks), checks it, then asks y/n per mod. Enter keeps a mod as it is. It shows the plan and asks "Go?" before changing anything.
* Rebuild the game from the Longshot Launcher to the same directory, then play!
* To remove a mod, run it again, answer n for that mod, then Build.

## Uninstall

Untick or delete the "Classic Item Slots" folder.

## Compatibility

Fog and graphics mods are fine. Mods that change the HUD or menu layouts, or the US English text, will conflict. Other
languages work, but the pause menu tab hints still show L/R.

Additional features are WIP, mod is not thoroughly tested in all scenarios. Xbox/PS layouts untested.
Planned: Incorporating edit mode into in-game options menu.

## Longshot (PC)

**Longshot OoT Mods** is an all-in-one installer for Longshot that installs Classic Item Slots together with other tweaks, answer y/n per mod. Download `Longshot-OoT-Mods-v2.zip` from the [Download](#download) section above. Tested on Longshot nightly-623.

| Mod | What it does |
|---|---|
| Classic Item Slots v1.4.6 | N64-style item buttons: ZR plus X, L, R slots per age, new HUD, live HUD editor. Standard, Xbox or PlayStation button art. |
| Classic Enemy Respawn v2 | Dungeon enemies respawn when you leave a room and come back. |
| Classic Targeting v1 (experimental) | Classic-style targeting and aiming. Experimental on Longshot. |
| No Melee Auto-aim | Link no homes/turns/slides toward a nearby enemy/object when swinging without Z-targeting. |
| Classic Hit Sounds | N64-style sword and projectile hit sounds (sound files only). |
| Classic Puzzle Chime | The N64 puzzle-solved chime (sound files only). |

Run `Install or remove mods.cmd`, answer y/n per mod, then press Build in the Longshot Launcher. Use it instead of Classic Item Slots v1.4.6's own Longshot installer, which leaves a file in `.longshot_exefs` that breaks Longshot's build.

## How it was made

- `src/slots.c`, `src/hooks.S`: the mod, freestanding ARM64 C, linked by `src/link_module.ld` into its own code module
  (`exefs/subsdk9`, an NSO with a `MOD0` header, `src/module.S`) loaded right after `subsdk0`. Everything reaches the
  game through PC-relative addresses.
- `build.py`: compiles and links (LLVM: clang, ld.lld), writes the NSO and an IPS32 patch for `main` with only the
  hook points (five controller reads, the control guide and hand-state setups, the HUD and pause overlay setups, and
  the pause menu's own item assignments).
- `tools/`: the romfs side. `hud_layout.py` (with `buil.py`, a writer for the game's BFFH UI layouts) adds the HUD and
  pause-menu panes and repacks the UI archive at its exact size; `draw_buttons.py` draws the button art per theme;
  `make_icons.py` turns it into the game's BNTX textures (ASTC, with this console's block-linear layout);
  `menu_tabs.py`, `no_item_guides.py`, `hide_a_prompt.py`: the text and guide edits; `make_release.py`: the packages.
- Needs a dump of the game (1.1.1) to build the romfs files; it is only read. The tools use the zstd/SARC helpers of
  the OoT Fog Mod tools and the BYML reader of the OoT remake dev tool (paths at the top of each script).

## Credits

- Claude wrote the mod's code: the ARM64 C/assembly code module and its hooks into the game, the build scripts, and
  the tools that edit the HUD/pause-menu layouts, text and control-guide tables.
- Claude helped reverse-engineer the game (finding the functions and memory values the mod uses) from the game's code
  and live memory reads.
- The button art is drawn by a Python script Claude wrote (plain shapes and text), not by an AI image generator. Item
  icons are the game's own.
- Design, feature decisions and all in-game testing: sonofsilvanus.

Special thanks: [platinumagpie](https://github.com/platinumagpie) for [OoT Dev Tool](https://github.com/platinumagpie/oot-remake-devtool): its live connection to the game (memory reads and writes, inputs and screenshots) and its GameData readers were used throughout development and testing.
