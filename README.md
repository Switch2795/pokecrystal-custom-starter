# Pokémon Crystal - Custom Starter ROM

This is a **non-PSR-official, modified** version of the disassembly of Pokémon Crystal. Modifications are made to offer starter customization for the player, as well as workarounds for RNG manipulations and spinners.

It builds the following ROM:

- Pokemon Crystal pokecrystal.gbc `sha1: 397d0e6d43a3064f601d5a13a22d5bc283f1a04b` `crc32: FCAC0DA8`

To set up the repository, see [INSTALL.md](INSTALL.md).

If you only need to apply the changes to an existing vanilla ROM, see [**PATCHES.md**](PATCHES.md)

## Main changes
- Custom starter menu available before New Game, through the Option menu.
- Instant Text has been Implemented
- 5 Repels given by Elm's Assistant when exiting the Lab the first time.
- 5 Master Balls given in exchange of Poké Balls by Elm's Assistant when exiting the Lab the second time.
- Master Balls sell for 100 each (same as Poké Ball).
- Route 29 : only L2-3 Sentrets during Morning/Day times.
- Route 30 : only L4 Hoppips during Morning/Day times, only L4 Poliwags during Night time.
- Route 31 : only L5 Bellsprouts during Morning/Day times, only L4 Poliwags during Night time.
- Route 34 : only L10 Abras
- Route 36 : only L5 Growlithes during Morning/Day
- Sprout Tower : only L4 Gastly at Night
- Ilex Forest : only L7 Psyduck at Night
- Randomly spinning trainers (or "spinners") have been adjusted to guarantee a dodge with an average reaction time.
- Douglas (spinner in Mahogany Gym) faces away from the player's path.

## Visuals
![Image of Option menu](https://i.imgur.com/b7vM1id.png)
![Image of Starter menu](https://i.imgur.com/0KuyUBi.png)

## See also

- **Gen 1-3 Pokémon Speedrunning:** [Discord][speedrun-discord]

- [**FAQ**](FAQ.md)
- [**Documentation**][docs]
- [**Wiki**][wiki] (includes [tutorials][tutorials])

Other disassembly projects:

- [**Pokémon Red/Blue - Custom Starter**][pokered-custom-starter]
- [**Pokémon Crystal**][pokecrystal]

[speedrun-discord]: https://discord.gg/NjQFEkc
[pokered-custom-starter]: https://github.com/Arcaseriam/pokered-custom-starter
[pokecrystal]: https://github.com/pret/pokecrystal
[docs]: https://pret.github.io/pokecrystal/
[wiki]: https://github.com/pret/pokecrystal/wiki
[tutorials]: https://github.com/pret/pokecrystal/wiki/Tutorials
