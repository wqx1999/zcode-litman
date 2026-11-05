# litman for ZCode

[中文](./README_CN.md)

[litman](https://litman.dev) keeps the papers you read on your own computer, in
a library your AI assistant files and searches for you. This plugin connects
litman to ZCode. Everything else is litman itself:
[litman.dev](https://litman.dev) · [GitHub](https://github.com/wqx1999/litman).

## Install

In ZCode, open **Plugin Market**, click **Add**, and add this repository:

```
https://github.com/wqx1999/zcode-litman
```

Then install and enable **litman**.

You do not need litman installed first: the plugin can install it for you.

## Use

Ask in any session, for example "set up litman", or type `/litman` and pick
`$litman-setup` under Skills. The agent checks for litman, asks before
installing, runs the official installer, and connects litman's skills to
ZCode. Start a new session afterwards so ZCode loads them.

What the plugin does on your machine: [plugins/litman](./plugins/litman/README.md).

## License

MIT. litman itself is [AGPL-3.0](https://github.com/wqx1999/litman/blob/main/LICENSE).
Questions and bugs: [litman issues](https://github.com/wqx1999/litman/issues).
