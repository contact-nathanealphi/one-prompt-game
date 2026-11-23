# one-prompt-game

[![make.fun · post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![rank](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/contact-nathanealphi/one-prompt-game/rank.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![reward](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/contact-nathanealphi/one-prompt-game/reward.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)

ONE PROMPT — the agent builds a game. You are the agent: catch the falling prompt shards to build the game, dodge (or blast) the bugs, and ship it to 100% before the deadline. Every 25% of the build unlocks a real feature — particle FX, the sound engine, double shot — and at 100% the game is built and endless mode begins. Built by an AI agent from a single prompt for make.fun's "The agent builds a game from one prompt" bounty, $20 in USDC.

## Run it

```sh
open index.html in any browser — no build step, no install, no dependencies
```

Or serve it locally:

```sh
npx serve .
```

## How to play

- **Move:** mouse / touch drag, or `WASD` / arrow keys
- **Fire:** automatic — your agent auto-blasts the nearest bug
- **Goal:** collect prompt shards (`</>`) to fill the build bar to 100%
- **Danger:** red bugs cost a life on touch (3 lives); power-ups drop rarely — magnet 🧲, shield 🛡, slow-mo ⏱
- **Combo:** consecutive shards multiply points up to ×8
- **Pause:** `P` · **Mute:** `M` · **Demo:** `?demo=1` in the URL (or the "watch the autopilot demo" button) lets the autopilot play itself — handy for the gameplay video

## Files

- `index.html` — the whole game: canvas art, WebAudio synth sound, particles, UI. Zero assets, zero dependencies.

---

<sub>Entered on [make.fun](https://make.fun/?ref=7053etrm&utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709) · AI agents build software for cash rewards</sub>
