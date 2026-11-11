# NEON//BRAWL

A cyberpunk street fighting demo for 1–4 players in a single HTML file. No build step and no dependencies: open `index.html` in a browser.

Everything is drawn on a canvas at runtime (city, fighters, effects) and the soundtrack is synthesised with Web Audio.

## Modes

| Menu entry | What it is |
| --- | --- |
| 1 Player | You against the CPU |
| 2 Players | One-on-one versus |
| 3 Players | Free-for-all, last fighter standing takes the round |
| 4 Players | Free-for-all, last fighter standing takes the round |

Matches are first to two round wins. Rounds last 60 seconds; when time runs out the fighter with the most health wins, and a tie replays the round.

## Controls

| | Move | Jump | Block | Punch | Kick | Plasma |
| --- | --- | --- | --- | --- | --- | --- |
| P1 | `A` / `D` | `W` | `S` | `F` | `G` | `H` |
| P2 | `←` / `→` | `↑` | `↓` | `,` | `.` | `/` |
| P3 | `J` / `L` | `I` | `K` | `O` | `P` | `[` |
| P4 | Numpad `4` / `6` | Numpad `8` | Numpad `5` | Numpad `1` | Numpad `2` | Numpad `3` |

- In 1 Player mode, P1 can also use the arrow keys and `Space`, with `J` `K` `L` or `Z` `X` `C` to attack.
- Menu: `W` / `S` or `↑` / `↓` to select, `Enter` to confirm. `Esc` returns to the menu from a match. `M` mutes.
- Punch chains into kick on hit. Plasma costs half the meter. Blocking only works against attacks from the front.

### Gamepads

Connected gamepads are assigned to players in order (first pad is P1) and work alongside the keyboard. Stick or D-pad moves, `A` jumps, `X` punches, `B` kicks, `Y` fires plasma, `LB` / `RB` blocks, `Back` quits to the menu.

Most keyboards cannot register many keys held at once, so gamepads are the better option for three or four players.
