# Welsham Test

Staging build of [Welsham Railway](https://github.com/BrendanJamesLynskey/Welsham-Railway).
New features land here first, get checked, then graduate to the main game.
Same map (Welsham Circle), same unit (Class 701/5), same recorder — just
sat behind a password so casual visitors don't land on a half-broken build.

[Play it here](https://brendanjameslynskey.github.io/Welsham-Test/)

[Announcement recorder](https://brendanjameslynskey.github.io/Welsham-Test/recorder.html)
— record station announcements and security messages into audio files
for import into the sim.

## Access

The sim is gated by an access code on first load. Type it into the prompt
and press **ENTER**. The recorder page is not gated.

## Route

**Welsham Circle** — 22.9 km, 8 stations, urban biome. Same data as
the main game; see the parent repo's README for the timetable.

## Rolling Stock — Class 701/5

5-car Alstom Class 701/5, 101.8 m, 262 t, central driving position.
Identical to the main game's unit.

## Controls

| Key | Action |
|-----|--------|
| `↑` / `↓` | Notch power up / brake on |
| `Space` | AWS reset (acknowledge audible warning) |
| `D` | DRA toggle |
| `H` | Horn |
| `Tab` | Cycle HUD overlay |
| `C` | Toggle free-cam (WASD / Space / LCtrl to fly, drag to look, C again to return) |
| `Esc` | Quit to menu |

## Workflow

This repo exists so changes can be tried out without disturbing the public
Welsham Railway build. Typical loop:

1. Edit `index.html` (or `recorder.html`) here.
2. Push — GitHub Pages auto-deploys in ~30 s.
3. Test in the browser behind the gate.
4. When happy, port the change across to `Welsham-Railway` and push there too.

## Repo

[BrendanJamesLynskey/Welsham-Test](https://github.com/BrendanJamesLynskey/Welsham-Test)

## Licence

MIT.
