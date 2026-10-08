# Platformer Party v0.7 (a Pizza Tower mod)

Play Pizza Tower as seven platformer heroes, each with their own moves, physics, sounds and HUD.
Pick a lead and a partner, swap between them mid-level, and run Peppino's tower your way.

> **v0.7 / early release.** 1.0 will add three more characters.

## Characters

| Character | From | Moves |
|---|---|---|
| **Sonic** | Sonic Mania | Mania physics, spin dash, drop dash, momentum run; the spin ball destroys badniks |
| **Tails** | Sonic Mania | Spin dash, flight (tap jump to lift) |
| **Knuckles** | Sonic Mania | Spin dash, glide, wall climb, ledge pull-up |
| **Mario** | Super Mario World | SMW physics with a P-meter, spin jump, wall kick, ground pound, stomps; **Fire Flower** (fireballs) and **Cape Feather** (cape spin and float) dropped by enemies |
| **Luigi** | Super Mario World | Floatier, slippery SMW physics; the same powerups |
| **Madeline** | Celeste | 8-way dash, climbing with stamina, wall jumps, super/hyper/wall-bounce jumps, live hair (red/blue), dash-refill crystals in every room |
| **The Knight** | Hollow Knight | Nail (side / up / pogo down-slash), Mothwing dash, Monarch Wings double jump, Mantis Claw wall slide, Vengeful Spirit, Desolate Dive, Howling Wraiths, Focus healing, 5 masks that slowly regenerate, soul meter, geo |

Each character also has their own collectibles (rings / SMW coins / strawberry seeds / geo), HUD, TV faces,
rank-screen pose, file-select art and an animated character-select backdrop.

**Duo mode:** pick a lead, then a partner (pick the same character twice to play solo). Your partner follows you
and taunts with you. **Q** (keyboard) or **LT** (gamepad) swaps who you're playing. The follower can be switched
off on the partner screen (Up/Down).

## Controls (default Pizza Tower bindings)

| | Jump (Z) | Grab (X) | Dash (Shift) | Other |
|---|---|---|---|---|
| Sonic / Tails / Knuckles | jump; again in the air = drop dash / fly / glide | hold to run | - | crouch + jump = spin dash |
| Mario / Luigi | jump | hold = run, tap = fireball / cape spin | spin jump | down in the air = ground pound |
| Madeline | jump / wall jump | hold = grab & climb | dash (aim with arrows) | hold dash after a ground dash = Pizza Tower mach run |
| The Knight | jump / wall jump / double jump | nail (hold up/down to aim) | dash | **A** (gamepad Y): tap = Vengeful Spirit, up = Howling Wraiths, down in the air = Desolate Dive, hold = Focus |

Swap characters: **Q** / **LT**. Open the character select: press jump on the file-select screen with the mod
character selected (Up on the character toggle).

## Requirements

- **Pizza Tower, Steam PC version**, build 16727860 (updated 2026-09-02).
  The patch only applies to this exact `data.win`:
  `SHA-256 E3FC286CAE3724F1B7BD97BD1E682C0B9696F9121F8EDA3AF910F332646FD4E1` (92,440,092 bytes).
- An xdelta patcher: [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher), xdelta UI, or `xdelta3`.
- Not compatible with other mods that replace `data.win` (apply this to an unmodded game).

## Install

1. In Steam: right-click Pizza Tower, **Properties > Installed Files > Browse**.
2. **Back up `data.win`** (copy it somewhere safe).
3. Apply `PlatformerParty-v0.7.xdelta` to `data.win` with your patcher, e.g.
   `xdelta3 -d -s data.win PlatformerParty-v0.7.xdelta data_patched.win`
4. Replace `data.win` with the patched file (rename `data_patched.win` to `data.win`).
5. Check it: the patched file's SHA-256 should be the one in `checksums.txt`.
   (PowerShell: `Get-FileHash data.win`)

The character setting is saved to `sonicmod.ini` next to the game's other settings.

## Uninstall

Put your backed-up `data.win` back, or use Steam's **Verify integrity of game files**.

## Troubleshooting

- **Patch fails / wrong checksum:** your `data.win` isn't the vanilla Steam build above (another mod, or a
  different game version). Verify game files in Steam, then patch again.
- **The game shows an error box:** it's a GameMaker error message. Copy its text (Ctrl+C works in it) and open
  an issue with it, plus which character / level / move you were using.
- Pizza Tower updates will undo the mod; re-patch only once a matching release is posted.

## Compatibility and known issues

- Single player. Co-op wasn't tested.
- Character sizes are visual; everyone uses Pizza Tower's hitbox.
- The duo follower is visual (it doesn't collect items or attack).
- Some boss fights may play oddly with characters that can't grab (Madeline, the Knight).

## Credits

**Base game:** Pizza Tower by Tour De Pizza. You need to own it; this patch contains none of its original files.

**Characters, art and sound** (all property of their owners; used for a free, non-commercial fan mod):
- *Sonic Mania* (SEGA; Christian Whitehead, Headcannon, PagodaWest Games): Sonic, Tails and Knuckles sprites and sounds, HUD font, title-screen art, small animals.
- *Celeste* (Maddy Makes Games / Extremely OK Games): Madeline, her hair, sounds, strawberries and seeds, refill crystals, night-mountain backgrounds.
- *Hollow Knight* (Team Cherry): the Knight, nail and spell effects, HUD, sounds, the Hallownest backdrop.
- *Super Mario World* (Nintendo): Mario and Luigi.
  - Mario sprites: "Mario, Luigi, Toad & Toadette (SMW-Style, Expanded)" by **GlacialSiren484** (+ **MauricioN64**).
  - Luigi sprites: SNES *Super Mario World* (All-Stars) Luigi, ripped by **Mister Man**.
  - Super Mario wall-jump frames: expanded SMW Mario by **AwesomeZack**, **GlacialSiren484**, **LinkstormZ** (Vanny).
  - Caped Mario: "SMW Caped Mario" by **AwesomeZack**.
  - Ground-pound frames: "SMW Mario & Luigi Revamp" by **UnRandomSM**.
  - Fire Flower and the HUD font: SMW rips by **Barack Obama**; SMW status-bar rip (mariouniverse.com).
  - Hosted by mariouniverse.com and The Spriters Resource.
  - SMW sound effects: themushroomkingdom.net.
  - The fireball is a hand-made SMW-style sprite.

**Tools:** UndertaleModTool / UTMT CLI (the UTMT team, GPL-3.0); UnityPy; Pillow; NumPy; the games' own FMOD
runtime (for decoding sound banks).

**Made with AI:** this mod was built with **Claude Code** (Anthropic, model Claude Opus 5.5) working with the
mod's author, who directed and play-tested it. No AI-generated art or audio is used: every sprite and sound
comes from the games and credited artists above.

## License

The mod's own code (its GameMaker scripts) is released under the MIT License (see `LICENSE`).
The characters, art and sounds are **not** covered by that license; they belong to the companies and artists
credited above. If you're a rights holder and want something removed, open an issue and it will be.
