# Debuff Foundation

We make **[debuff](https://github.com/debuffjp/debuff)**, an open-source toolkit for small, polished 2D games that run in the browser. **More room for play:** less setup and plumbing, more time for mechanics, art and weird ideas.

**[debuff.jp](https://debuff.jp)** · **[why debuff](https://debuff.jp/docs/why)** · **[examples](https://debuff.jp/examples)** · **[try it](https://debuff.jp/docs/getting-started)**

## What debuff gives you

- **A small, fast runtime.** Batched WebGL2 with a Canvas 2D fallback holds about 200,000 sprites at 60 fps on our benchmark machine, and the starter game ships at about 13 kB brotli.
- **Dev tools that explain things.** Errors say whose bug it is and link the exact source line. Frame drops say whether your code caused them. Feel values become live sliders.
- **Agents as helpers, people in charge.** An MCP server lets coding agents play the game you have open, read its state and errors, and run deterministic screenshot tests. You see and can undo everything they do.
- **Web standards only.** ES modules, a canvas, Web Audio and Gamepad. No proprietary editor or project format.

```bash
npm create debuff@latest my-game
```

> **Status: 0.1, early development.** APIs will change, and feedback from real games shapes them.

## Repositories

| Repo | What's there |
| --- | --- |
| [**debuff**](https://github.com/debuffjp/debuff) | Runtime packages, CLI, scaffolder, MCP server, templates |
| [**docs**](https://github.com/debuffjp/docs) | The [debuff.jp](https://debuff.jp) site: guides, API reference, `llms.txt` |
| [**brand**](https://github.com/debuffjp/brand) | The foundation mark, the debuff wordmark, buff the mascot, sprite sheet and social card |

## Get involved

- Questions, bugs and ideas: [open an issue](https://github.com/debuffjp/debuff/issues).
- Read the [contributing guide](https://github.com/debuffjp/debuff/blob/main/CONTRIBUTING.md) and the [roadmap](https://github.com/debuffjp/debuff/blob/main/docs/roadmap.md), or build a [plugin](https://github.com/debuffjp/debuff/blob/main/docs/plugins.md).
- Everyone is welcome under our [code of conduct](https://github.com/debuffjp/debuff/blob/main/CODE_OF_CONDUCT.md).
