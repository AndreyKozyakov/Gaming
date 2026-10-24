# Gaming

Browser games. Each game lives in its own folder as plain HTML, CSS and JavaScript, with no build step. Open a game's `index.html` in a browser and it runs.

## Games

| Game | Folder | Status |
|---|---|---|
| **Rattle Rex** | [`rattle-rex/`](rattle-rex/) | Trial build: one night, three halls, one boss |

### Rattle Rex

A horror-comedy platformer. You play a museum T-Rex skeleton that comes alive after closing time. Chomp skeleton critters to shake loose their bones (bones are calcium), fill the milk carton for Milk Rage, and get past Gary the night guard, the J4-N1T0R cleaning robot and the whale skeleton Moby-Dead.

- **Beginner:** 7 spare ribs, a slower whale, and on-screen tips when you need them.
- **Hard:** 4 spare ribs, extra staff on duty, a faster whale, no tips.

| Action | Keyboard | Touch |
|---|---|---|
| Walk | ← → or A D | Arrow buttons |
| Jump (hold for higher) | Space or W | JUMP |
| Chomp | J or X | CHOMP |
| Rattle roar (stuns staff, freezes critters) | K or Z | RATTLE |
| Drop off a ledge | ↓ or S | |
| Pause / mute | Esc / M | Top-right buttons |

A yellow ring with a key badge marks anything a chomp will land on.

## Run locally

Double-click `rattle-rex/index.html`, or serve the folder:

```sh
python3 -m http.server 8000
# then open http://localhost:8000/rattle-rex/
```

The game loads its fonts from Google Fonts. Everything else, including art and sound, is generated in code, so there are no asset files.

## Publish

With GitHub Pages turned on for the `main` branch, the root `index.html` lists the games and each game is served from its folder (for example `/rattle-rex/`).
