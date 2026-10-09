# Pokémon Ruby & Sapphire NDS

Pokémon Ruby and Sapphire, remade on the Nintendo DS inside Pokémon Black 2. The whole Hoenn region is rebuilt in Black 2's 3D overworld, and the complete story plays out with Black 2's music and battle system. Hoenn's characters are their original sprites, resized and animated for the DS.

<p>
<img src="screenshots/sapphire/01_title_sapphire.gif" alt="Sapphire title screen" width="256">
<img src="screenshots/ruby/01_title_ruby.gif" alt="Ruby title screen" width="256">
</p>

**This repository contains patches only.** No ROMs are provided. You need your own dump of Pokémon Black Version 2.

## Two versions

**Pokémon Sapphire NDS:** Team Aqua plans to expand the seas by awakening the legendary Kyogre, and you chase them from Slateport's harbour to the depths of Seafloor Cavern.

**Pokémon Ruby NDS:** Team Magma plans to expand the land by awakening the legendary Groudon. You face Maxie, Tabitha and Courtney, explore Magma Hideout, and meet Groudon under a scorching sky.

## Modern quality-of-life features

- Field moves work without teaching HMs: just the badge and the HM in your Bag.
- A Gen 6-style Exp. Share you switch on and off. Opponent levels are scaled to match it.
- Every trade evolution happens in-game, by level-up or by using an item.
- Emerald's event islands (Southern Island, Faraway Island, Birth Island and Navel Rock) unlock in-game, no Mystery Gift needed.
- A bigger post-game: the National Dex, seven roaming legendaries, Jirachi, Celebi, Mirage Island and Altering Cave.
- Your choice at the start of the adventure: the Fairy type (with Gen 6's type chart and new Fairy moves), modern or classic physical/special split, and Hoenn's original soundtrack (played on Black 2's instruments) or Black 2's music.
- The Hoenn Battle Tower, and the Pokémon World Tournament on the Battle Tower island.
- The Hoenn town map and Pokédex.

## Screenshots

| Sapphire | Ruby |
|---|---|
| <img src="screenshots/sapphire/02_sootopolis_city.png" width="256"> | <img src="screenshots/ruby/06_lilycove_drought.png" width="256"> |
| <img src="screenshots/sapphire/03_fortree_city.png" width="256"> | <img src="screenshots/ruby/04_meteor_falls.png" width="256"> |
| <img src="screenshots/sapphire/06_lilycove_storm.png" width="256"> | <img src="screenshots/ruby/07_team_magma_battle.png" width="256"> |
| <img src="screenshots/sapphire/07_team_aqua_battle.png" width="256"> | <img src="screenshots/ruby/09_groudon_appears.png" width="256"> |
| <img src="screenshots/sapphire/08_double_battle.png" width="256"> | <img src="screenshots/ruby/05b_underwater_dive.png" width="256"> |
| <img src="screenshots/sapphire/05_route113_ash.png" width="256"> | <img src="screenshots/ruby/10_groudon_battle.png" width="256"> |

More shots, with captions, are in [screenshots/](screenshots/).

## How to play

1. Get your own dump of **Pokémon Black Version 2** (USA/Europe, game code `IREO`). It must match exactly:
   - size 536,870,912 bytes
   - CRC32 `D4427FD1`
   - SHA-1 `e51e6dfb8678a3d19dcd2a10691b96a569ca0abb`
2. Download `Pokemon_Sapphire_NDS_v16.1.bps` or `Pokemon_Ruby_NDS_v16.1.bps` from [Releases](../../releases).
3. Apply it to your dump with a BPS patcher, such as [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) (in the browser), Floating IPS or beat.
4. Play the patched `.nds` in an emulator such as melonDS, DraStic or DeSmuME.

Use in-game saves. When you update to a new version, your save carries over, but emulator save states don't.

## Coming soon

- **Pokémon Emerald NDS**

## Credits

- **Game Freak, Nintendo, Creatures and The Pokémon Company:** Pokémon Ruby, Sapphire, Emerald and Black 2.
- **[pret](https://github.com/pret):** the pokeruby and pokeemerald decompilations.
- **[pokebw2](https://github.com/fuddlesworth/pokebw2):** the Pokémon Black 2 / White 2 decompilation.

Tools used:
- **ds-decomp (dsd)** by AetiasHax: DS disassembly.
- **CTRMap / CTRMapV** by HelloOO7: DS 3D model writing.
- **apicula** by scurest: DS model tools.
- **DeSmuME**, **py-desmume** and **melonDS**: testing.
- **Python, NumPy and Pillow**: build tools.

AI (Claude by Anthropic) was used to help code this project.

This is a non-commercial fan project. It is not affiliated with or endorsed by Nintendo, Game Freak, Creatures or The Pokémon Company. Please support the official games.
