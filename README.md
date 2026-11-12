# Shrine Runner

A 2D side-scrolling endless runner that runs in the browser. You are the thief who took the relic back from the witch's shrine. She woke up. Run.

## Play

Open `index.html` in any modern browser, or use the hosted GitHub Pages version.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Jump | `Space` / `Up` / `W` | tap the screen |
| Slide | `Down` / `S` | swipe down |
| Restart | `R` | Run again button |
| Mute | `M` | speaker button |

## How it plays

- The thief runs automatically and the world speeds up the longer you survive.
- Obstacles: fallen logs and thorn bushes to jump, low swooping bats to jump, ravens at head height to slide under.
- Glowing orbs are worth 10 points each. Every 10 orbs you collect pushes the witch back.
- Hitting an obstacle lets the witch close in. Take too many hits and she catches you: "Caught!" then a restart button.
- Score is metres travelled plus orbs x 10. Your best score is saved on the device.

## Tech

One self-contained HTML file. Canvas 2D rendering, procedurally drawn sprites (no image files), Web Audio for sound effects, no build step and no dependencies. Works on desktop and mobile.
