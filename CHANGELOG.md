# Changelog

## 0.8.0 - 2026-10-08

For Pizza Tower Steam build 16727860.

### New
- **Launcher** (PlatformerParty.exe): pick your data.win and press PLAY; it installs the mod (keeping the original
  as data.win.vanilla) and starts the game. Replaces the xdelta patch.
- The game boots straight to the character select (no intro).
- Four new characters: **Mega Man**, **Yoshi**, **Kirby** (12 copy abilities), **Cuphead** (9 weapons, EX shots,
  3 Supers, charms).
- **Options > Customize Character**: Cuphead's equip card, Kirby's ability, Mario / Luigi's power-up, Yoshi's eggs,
  Madeline's dashes (two = pink hair), the Knight's masks, Mega Man's energy.
- Mario and Luigi now use Super Mario World's own sprites and palettes, with cape flight like SMW and a Fire Flower
  shot that bounces off walls (4 bounces). Luigi uses the Super Mario Maker 2 SMW-style sheet.
- Level themes for Mario, Luigi and Mega Man.

### Changed
- The Knight's spells are on gamepad B; gamepad buttons now work on every controller slot.
- The camera is 10% closer.
## 0.7.1 - 2026-10-08

For Pizza Tower Steam build 16727860.

### Fixed
- Luigi faced backwards in every pose (the source sheet draws him facing left); all of his frames, including Fire
  and Cape Luigi, now face the right way.
- Fire Mario / Fire Luigi lost their white-and-red / white-and-green palette in the wall-slide, wall-kick and
  ground-pound poses; those poses now use the same colours as the rest.
- Mario's colours normalised to Super Mario World's (the source sheet used pink reds and cyan highlights).

Note: the character-select corner still reads "v0.7".

## 0.7.0 - 2026-10-08 (first public release)

For Pizza Tower Steam build 16727860.

### Characters
- Sonic, Tails and Knuckles (Sonic Mania): Mania physics, spin dash, drop dash, flight, glide and climb, ring
  collectibles and HUD, badnik-destroying jump ball with rebound.
- Mario and Luigi (Super Mario World): SMW physics with a P-meter, spin jump, wall kick, ground pound, stomps
  that defeat enemies, SMW coins, SMW status bar and sounds.
  - Fire Flower and Cape Feather drop from enemies; any hit or enemy contact knocks the powerup off.
- Madeline (Celeste): Celeste physics, 8-way dash, climbing with stamina, wall jumps, super / hyper / wall-bounce
  jumps, live hair, strawberry seeds, Celeste-style counter, dash-refill crystals.
- The Knight (Hollow Knight): nail with pogo, dash, double jump, wall slide, Vengeful Spirit, Desolate Dive,
  Howling Wraiths, Focus, 5 regenerating masks, soul, geo, Hollow Knight HUD.

### Features
- Character select carousel with an animated backdrop per character.
- Duo mode: lead + partner, Q / LT to swap, a follower that taunts with you; the follower can be turned off.
- Distinct character sizes; Madeline's and the Knight's movement scaled to their size.
- Per-character TV faces, rank poses, file-select art and title cards.

### Planned for 1.0
- Three more characters.
