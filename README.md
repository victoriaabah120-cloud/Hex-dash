# Shrine Runner

A 2D side-scrolling endless runner that runs in the browser. You are the thief who took the relic back from the witch's shrine. She woke up. Run.

## Play

Open `index.html` in any modern browser, or use the hosted GitHub Pages version.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Jump | `Space` / `Up` / `W` | tap the screen |
| Slide | `Down` / `S` | swipe down |
| Skip intro | `Skip intro` button, `Space`, `Enter` or `Esc` | Skip intro button |
| Restart | `R` | Run again button |
| Mute | `M` | speaker button |

## The intro

Three scenes play before the run, with letterbox bars and captions:

1. The hooded thief walks slowly through the dark forest toward a glowing stone shrine.
2. He reaches the shrine, the relic floats up into his hand, and the light catches his face.
3. A shriek: the witch swoops in behind him on her broom. He turns and bolts, and the chase starts.

The Skip intro button jumps straight into the run at any point.

## How it plays

- The thief runs automatically and the world speeds up the longer you survive.
- Obstacles: fallen logs and thorn bushes to jump, low swooping bats to jump, ravens at head height to slide under.
- Glowing orbs are worth 10 points each. Every 10 orbs you collect pushes the witch back.
- Hitting an obstacle lets the witch close in. Take too many hits and she catches you: "Caught!" then a restart button.
- Score is metres travelled plus orbs x 10. Your best score is saved on the device.

## Art and tech

One self-contained HTML file. Canvas 2D rendering, all sprites drawn in code (no image files): a human-proportioned thief with hood, cloak, satchel and boots on an IK-driven run cycle, and a witch with a pointed hat, long robes, flowing hair and a bristled broom. Web Audio synthesises every sound effect. No build step and no dependencies. Works on desktop and mobile.
