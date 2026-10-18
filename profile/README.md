# Debuff Foundation

We make **[debuff](https://github.com/debuffjp/debuff)**, an open-source toolkit for small, polished 2D games that run in the browser. **More room for play:** less setup and plumbing, more time for mechanics, art and weird ideas.

**[debuff.jp](https://debuff.jp)** · **[why debuff](https://debuff.jp/docs/why)** · **[play the examples](https://debuff.jp/examples)** · **[try it](https://debuff.jp/docs/getting-started)** · **[Discord](https://discord.gg/jshbDHSpCY)**

```bash
npm create debuff@latest my-game
```

## What debuff gives you

- **A small, fast runtime.** Batched WebGL2 with a Canvas 2D fallback holds about 200,000 sprites at 60 fps on our benchmark machine, and the starter game ships at about 15 kB brotli.
- **Crisp pixel art out of the box.** Integer scaling, pixel snapping and **debuff sans**, our own pixel font, as the default for text.
- **Tests that play the real game.** Logic tests run the actual game in Node in milliseconds, scenarios check it in a browser (including flashes and contrast), and a fuzzer plays it with random hands until something breaks. Every finding replays exactly.
- **Dev tools that explain things.** Errors say whose bug it is and link the exact source line. Rewind and scrub a live session. Frame drops say why. Feel values become live sliders.
- **Agents as helpers, people in charge.** An MCP server and plugins for Claude Code and Codex let agents play the game you have open, read its state and errors, and run the tests. You see and can undo everything they do.
- **Web standards only.** ES modules, a canvas, Web Audio and Gamepad. No proprietary editor or project format.

> **Status: 0.6, early development.** APIs will change, and feedback from real games shapes them.

## Tools for any web game

Two of our tools work outside debuff too, with Phaser, PixiJS, three.js and plain canvas games:

- **[myaku](https://github.com/debuffjp/debuff/tree/main/packages/myaku)**: a frame profiler that finds the hitches players feel and says why in plain words.
- **[keiko](https://github.com/debuffjp/debuff/tree/main/tooling/keiko)**: fast, deterministic logic tests that run your real game in Node, no browser.

## Repositories

| Repo | What's there |
| --- | --- |
| [**debuff**](https://github.com/debuffjp/debuff) | Runtime packages, CLI, scaffolder, MCP server, keiko, myaku, templates |
| [**docs**](https://github.com/debuffjp/docs) | The [debuff.jp](https://debuff.jp) site: guides, API reference, playable examples, `llms.txt` |
| [**overbuffed**](https://github.com/debuffjp/overbuffed) | A swarm survival game starring buff, built in the open to find what debuff should do better. [Play it](https://debuff.jp/play/overbuffed/) |
| [**debuff-sans**](https://github.com/debuffjp/debuff-sans) | Our pixel font as TTF, BDF and a sprite sheet, free under the SIL Open Font License |
| [**brand**](https://github.com/debuffjp/brand) | The foundation mark, the debuff wordmark, buff the mascot, sprite sheet and social card |

## Get involved

- Come say hi, share what you're making, or ask anything on [Discord](https://discord.gg/jshbDHSpCY).
- Bugs and ideas: [open an issue](https://github.com/debuffjp/debuff/issues).
- Read the [contributing guide](https://github.com/debuffjp/debuff/blob/main/CONTRIBUTING.md) and the [roadmap](https://github.com/debuffjp/debuff/blob/main/docs/roadmap.md), or build a [plugin](https://github.com/debuffjp/debuff/blob/main/docs/plugins.md).
- Everyone is welcome under our [code of conduct](https://github.com/debuffjp/debuff/blob/main/CODE_OF_CONDUCT.md).
