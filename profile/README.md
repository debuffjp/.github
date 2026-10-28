# Debuff Foundation

We make **[debuff](https://github.com/debuffjp/debuff)**, an open-source toolkit for small, polished 2D games that run in the browser. **More room for play:** less setup and plumbing, more time for mechanics, art and weird ideas.

**[debuff.jp](https://debuff.jp)** · **[why debuff](https://debuff.jp/docs/why)** · **[play the examples](https://debuff.jp/examples)** · **[try it](https://debuff.jp/docs/getting-started)** · **[Discord](https://discord.gg/jshbDHSpCY)**

```bash
npm create debuff@latest my-game
```

## What debuff gives you

- **A small, fast runtime.** Rendering is [spryte](https://github.com/debuffjp/spryte), which draws moving sprites 2–4× faster than the most popular 2D web renderer, at a ninth of its size in [2dbench](https://github.com/debuffjp/2dbench), an open, pixel-checked benchmark, from about 10 kB of JavaScript.
- **Crisp pixel art out of the box.** Integer scaling, pixel snapping and **debuff sans**, our own pixel font, as the default for text.
- **Tests that play the real game.** Logic tests run the actual game in Node in milliseconds, scenarios check it in a browser (including flashes and contrast), and a fuzzer plays it with random hands until something breaks. Every finding replays exactly.
- **Dev tools that explain things.** Errors say whose bug it is and link the exact source line. Rewind and scrub a live session. Frame drops say why. Feel values become live sliders.
- **Agents as helpers, people in charge.** An MCP server and plugins for Claude Code and Codex let agents play the game you have open, read its state and errors, and run the tests. You see and can undo everything they do.
- **Web standards only.** ES modules, a canvas, Web Audio and Gamepad. No proprietary editor or project format.

> **Status: 0.9, early development.** APIs will change, and feedback from real games shapes them.

## Tools for any web game

These work outside debuff too, with Phaser, PixiJS, three.js and plain canvas games:

- **[spryte](https://github.com/debuffjp/spryte)**: the renderer inside debuff as a standalone MIT package. Immediate mode, batched WebGL2 with a Canvas 2D fallback, about 10 kB.
- **[2dbench](https://github.com/debuffjp/2dbench)**: an open, fair benchmark for 2D web renderers. Same scenes and simulation for every library, a pixel-parity gate, full environment with every result. [Run it on your device](https://debuffjp.github.io/2dbench/mobile.html).
- **[myaku](https://github.com/debuffjp/debuff/tree/main/packages/myaku)**: a frame profiler that finds the hitches players feel and says why in plain words.
- **[keiko](https://github.com/debuffjp/debuff/tree/main/tooling/keiko)**: fast, deterministic logic tests that run your real game in Node, no browser.

## Repositories

| Repo | What's there |
| --- | --- |
| [**debuff**](https://github.com/debuffjp/debuff) | Runtime packages, CLI, scaffolder, MCP server, keiko, myaku, templates |
| [**spryte**](https://github.com/debuffjp/spryte) | The renderer: WebGL2 sprites, shapes, text, render targets and shaders, with a Canvas 2D fallback |
| [**2dbench**](https://github.com/debuffjp/2dbench) | Open benchmark for 2D web renderers, with community results from many devices |
| [**overbuffed**](https://github.com/debuffjp/overbuffed) | A swarm survival game starring buff, built in the open to find what debuff should do better. [Play it](https://debuff.jp/play/overbuffed/) |
| [**tenten**](https://github.com/debuffjp/tenten) | Headless pixel art for coding agents: an MCP server that draws sprites and animations, saves `.tt` and `.aseprite`, and exports sheets debuff loads |
| [**debuff-sans**](https://github.com/debuffjp/debuff-sans) | Our pixel font as TTF, BDF and a sprite sheet, free under the SIL Open Font License |
| [**brand**](https://github.com/debuffjp/brand) | The foundation mark, the debuff wordmark, buff the mascot, sprite sheet and social card |

## Get involved

- Come say hi, share what you're making, or ask anything on [Discord](https://discord.gg/jshbDHSpCY).
- Everything we make is free and MIT licensed. [Sponsor us on GitHub](https://github.com/sponsors/debuffjp) to keep it that way.
- Bugs and ideas: [open an issue](https://github.com/debuffjp/debuff/issues).
- Read the [contributing guide](https://github.com/debuffjp/debuff/blob/main/CONTRIBUTING.md) and the [roadmap](https://github.com/debuffjp/debuff/blob/main/docs/roadmap.md), or build a [plugin](https://github.com/debuffjp/debuff/blob/main/docs/plugins.md).
- Everyone is welcome under our [code of conduct](https://github.com/debuffjp/debuff/blob/main/CODE_OF_CONDUCT.md).
