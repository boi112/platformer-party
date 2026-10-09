# Platformer Party v0.8.0 (a Pizza Tower mod)

Play Pizza Tower as eleven platformer heroes, each with their own moves, physics, sounds and HUD.
Pick a lead and a partner, swap between them mid-level, and run Peppino's tower your way.

## Characters

| Character | From | Moves |
|---|---|---|
| **Sonic** | Sonic Mania | Mania physics, spin dash, drop dash, momentum run; the spin ball destroys badniks |
| **Tails** | Sonic Mania | Spin dash, flight (tap jump to lift) |
| **Knuckles** | Sonic Mania | Spin dash, glide, wall climb, ledge pull-up |
| **Mario** | Super Mario World | SMW physics with a P-meter, spin jump, wall kick, ground pound, stomps; **Fire Flower** (fireballs that bounce off walls) and **Cape Feather** (cape spin and SMW cape flight) |
| **Luigi** | Super Mario World | Floatier, slippery SMW physics; the same powerups |
| **Madeline** | Celeste | 8-way dash, climbing with stamina, wall jumps, super/hyper/wall-bounce jumps, live hair, dash-refill crystals |
| **The Knight** | Hollow Knight | Nail (side / up / pogo), Mothwing dash, Monarch Wings, Mantis Claw, Vengeful Spirit, Desolate Dive, Howling Wraiths, Focus, masks, soul, geo |
| **Mega Man** | Mega Man (NES) | Mega Buster with charge shot (pierces metal blocks), slide, beam-in, NES energy bar |
| **Yoshi** | Yoshi's Island | Yoshi's Island physics, flutter jump, tongue (swallow enemies into eggs), aimed egg throws that break every block, ground pound |
| **Kirby** | Kirby: Nightmare in Dream Land | NiDL physics, float, inhale / spit / swallow, slide, and **12 copy abilities** from the enemies you swallow: Fire, Ice, Spark, Needle, Cutter, Sword, Beam, Hammer, Parasol, Stone, Burning, Wheel |
| **Cuphead** | Cuphead | Cuphead's own physics, dash, parry, 8-way aim and lock, **all 9 weapons** with their EX shots, **3 Supers** and his **charms**, HP card and super meter |

Each character also has their own collectibles, HUD, TV faces, rank-screen pose, file-select art and an animated
character-select backdrop. Mario, Luigi and Mega Man have their own level themes.

**Customize your character:** Options > **Customize Character** (also from the pause menu): Cuphead's equip card
(Shot A, Shot B, Super, Charm), Kirby's copy ability, Mario / Luigi's power-up, Yoshi's eggs, Madeline's dashes,
the Knight's masks, Mega Man's energy.

**Duo mode:** pick a lead, then a partner (pick the same character twice to play solo). **Q** (keyboard) or **LT**
(gamepad) swaps who you're playing.

## Controls (default Pizza Tower bindings)

| | Jump (Z) | Grab (X) | Dash (Shift) | Other |
|---|---|---|---|---|
| Sonic / Tails / Knuckles | jump; again in the air = drop dash / fly / glide | hold to run | - | crouch + jump = spin dash |
| Mario / Luigi | jump | hold = run, tap = fireball / cape spin | spin jump | down in the air = ground pound |
| Madeline | jump / wall jump | hold = grab & climb | dash (aim with arrows) | hold dash after a ground dash = mach run |
| The Knight | jump / wall jump / double jump | nail (up/down to aim) | dash | **A** / pad **B**: spells (tap, up, down in the air), hold = Focus |
| Mega Man | jump | buster (hold to charge) | slide | |
| Yoshi | jump (hold = flutter) | tongue / spit | mach run at full speed | down with a full mouth = egg; **A** / pad Circle: aim, again = throw; down in the air = ground pound |
| Kirby | jump; again in the air = float | inhale / spit / ability attack | run (hold at full speed = mach) | down with a full mouth = swallow; down + jump = slide; **A** / pad Circle = drop ability |
| Cuphead | jump; again in the air = parry | shoot (hold) | dash | **C** / pad Triangle: EX (Super with 5 cards); **A** / pad Circle: switch weapon; **V** / pad R1: lock and aim |

## Requirements

- **Pizza Tower, Steam PC version**, build 16727860 (updated 2026-09-02). The mod only applies to this exact
  `data.win`: `SHA-256 E3FC286CAE3724F1B7BD97BD1E682C0B9696F9121F8EDA3AF910F332646FD4E1` (92,440,092 bytes).
- Windows with .NET Framework 4.5 or newer (built into Windows 10 / 11).
- Not compatible with other mods that replace `data.win`.

## Install

1. Download **PlatformerParty.exe** from the release and run it. (Windows may warn that it's from an unknown
   publisher: More info > Run anyway.)
2. If Pizza Tower is in the default Steam folder, it's found automatically. Otherwise open **SETTINGS** and pick
   your `data.win` (Steam: right-click Pizza Tower > Manage > Browse local files), or drag it onto the window.
3. Press **PLAY**. The launcher checks your `data.win`, keeps the original as `data.win.vanilla`, installs the mod
   and starts the game. The game opens straight on the character select.

Your `data.win` is only replaced after the modded file is fully built and its checksum matches `checksums.txt`.

## Uninstall

Launcher: **SETTINGS > Restore original data.win**. Or use Steam's **Verify integrity of game files**.

## Troubleshooting

- **"this data.win isn't the Steam version the mod was made for":** another mod or a different game version.
  Verify game files in Steam, then press PLAY again.
- **The game shows an error box:** copy its text (Ctrl+C works in it) and open an issue with it, plus which
  character / level / move you were using.
- Pizza Tower updates will undo the mod; reinstall once a matching release is posted.

## Compatibility and known issues

- Single player. Co-op wasn't tested.
- Character sizes are visual; everyone uses Pizza Tower's hitbox.
- Pizza Tower enemies don't have health bars: Cuphead's shots knock an enemy out after 8 damage, and bosses take
  a hit every 40.

## Credits

**Base game:** Pizza Tower by Tour De Pizza. You need to own it; the launcher contains none of its original files.

**Characters, art and sound** (all property of their owners; used for a free, non-commercial fan mod):
- *Sonic Mania* (SEGA; Christian Whitehead, Headcannon, PagodaWest Games): Sonic, Tails and Knuckles sprites and
  sounds, HUD font, title-screen art, small animals.
- *Celeste* (Maddy Makes Games / Extremely OK Games): Madeline, her hair, sounds, strawberries and seeds,
  refill crystals, backgrounds.
- *Hollow Knight* (Team Cherry): the Knight, nail and spell effects, HUD, sounds, the Hallownest backdrop.
- *Super Mario World* (Nintendo): Mario, his power-ups, items, the SMW level theme.
  - Luigi: "Luigi from Super Mario Maker 2's Super Mario World theme" by **Mister Man** and co. (mfgg.net).
  - Earlier sheets: GlacialSiren484, MauricioN64, AwesomeZack, LinkstormZ (Vanny), UnRandomSM, Barack Obama
    (mariouniverse.com, The Spriters Resource).
  - SMW sound effects: themushroomkingdom.net.
- *Mega Man* (Capcom): Mega Man sprite sheet from **Sprites INC.**; the Wily stage theme from *Mega Man 3*.
- *Yoshi's Island* (Nintendo): Yoshi. Physics read from the Yoshi's Island disassembly by **Raidenthequick** and
  **TheGreekBrit** (brunovalads/yoshisisland-disassembly).
- *Kirby: Nightmare in Dream Land* (HAL Laboratory / Nintendo): Kirby and his abilities. Formats and physics
  read from the **knidl** decompilation (overjt/knidl).
- *Cuphead* (StudioMDHR): Cuphead, his weapons, effects, equip card, HUD and sounds.

**Tools:** UndertaleModTool / UTMT CLI (the UTMT team, GPL-3.0); UnityPy; Pillow; NumPy.

**Made with AI:** this mod was built with **Claude Code** (Anthropic, model Claude Opus 5.5) working with the
mod's author, who directed and play-tested it. No image- or audio-generation models were used. A few small pieces
were drawn or synthesized by Claude in code: Yoshi's egg, tongue and aiming cursor; Kirby's spat star and air
puff; Mega Man's shots and pickups; and the Mega Man, Yoshi and Kirby sound effects (recreations, since those
games' sounds are sequenced). Everything else comes from the games and artists above.

## License

The mod's own code (its GameMaker scripts and the launcher) is released under the MIT License (see `LICENSE`).
The characters, art and sounds are **not** covered by that license; they belong to the companies and artists
credited above. If you're a rights holder and want something removed, open an issue and it will be.
