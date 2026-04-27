# Zed Lateralus

[Zed editor](https://zed.dev) extension providing syntax highlighting, code folding, and language configuration for the [Lateralus](https://github.com/bad-antics/lateralus-lang) systems language (`.ltl`).

## Install

From the Zed command palette: `zed: extensions` → search **Lateralus** → install.

Or develop locally:

```bash
git clone https://github.com/bad-antics/zed-lateralus
zed --dev-extension /path/to/zed-lateralus
```

## What you get

- 🎨 Syntax highlighting via [`tree-sitter-lateralus`](https://github.com/bad-antics/tree-sitter-lateralus)
- 🧱 Code folding for functions, structs, enums, impl blocks, match arms
- 🪄 Bracket matching, autoclose, and proper comment behaviour (`//`, `/* */`)

## Companion projects

- [`tree-sitter-lateralus`](https://github.com/bad-antics/tree-sitter-lateralus) — the underlying grammar
- [VS Code extension](https://marketplace.visualstudio.com/items?itemName=lateralus.lateralus-lang)
- [`lateralus-lang`](https://github.com/bad-antics/lateralus-lang) — reference compiler

## License

MIT © bad-antics
