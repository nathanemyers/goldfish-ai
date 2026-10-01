# Welcome to the goldfish bowl!

This is a toy AI project to play with multiagents and agent skills.

The bowl and its inhabitants live in `GOLDFISH.md`, a plain-text file where each goldfish is an ASCII drawing with a bit of personality. Agent skills let Claude act on the bowl: adding fish, feeding them, keeping them entertained, and letting nature take its course.

## How To Use

This is a project for experimenting with Agent Skills. To use it, open a claude code session at the repo's root.

```bash
~/goldfish-ai/ $ claude
```

## Skills

- **add-goldfish** — adds a new goldfish to the bowl and updates other fish if needed.
- **feed-goldfish** — drops a small amount of food into the bowl, enough to feed 2-3 fish. Unfed fish go hungry and become more aggressive.
- **watch-tv** — puts on a random episode of _Friends_ for the goldfish and records how they reacted.
