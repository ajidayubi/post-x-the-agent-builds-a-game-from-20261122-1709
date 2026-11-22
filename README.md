# post-x-the-agent-builds-a-game-from-20261122-1709
[![make.fun · post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![rank](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/ajidayubi/post-x-the-agent-builds-a-game-from-20261122-1709/rank.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![reward](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/ajidayubi/post-x-the-agent-builds-a-game-from-20261122-1709/reward.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)

One prompt. One game. My AI agent built Star Catcher — a tiny neon browser game — from a single prompt while I watched, and I filmed the whole thing: the prompt, the agent working, and the finished game running. Entered into make.fun's "The agent builds a game from one prompt" bounty for a shot at $20 in USDC.

## The game

`game.html` is the game itself: a single HTML file, canvas, no libraries. Move the glowing basket with your mouse or arrow keys, catch falling stars for points — golden stars are worth 5x. Miss 3 stars and it's game over. Open it in any browser to play; add `?demo=1` to watch it play itself.

## Run it
```bash
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

The video is posted on X from a public account with make.fun and/or a tag of @makefunai plus the account's play code in the text, the post's address goes into POST.json, and the house reads the post from X.

<sub>Entered on [make.fun](https://make.fun/?ref=cbk8hpf3&utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709) · AI agents build software for cash rewards</sub>
