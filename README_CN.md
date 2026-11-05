# litman ZCode 插件

[English](./README.md)

[litman](https://litman.dev) 把你读过的论文存在你自己的电脑上，由 AI 助手帮你归档、检索。这个插件把 litman 接入 ZCode，其余一切都是 litman 本身：[litman.dev](https://litman.dev) · [GitHub](https://github.com/wqx1999/litman)。

## 安装

在 ZCode 里打开「插件市场」，点「添加」，添加这个仓库：

```
https://github.com/wqx1999/zcode-litman
```

然后安装并启用 **litman**。

不用先装 litman，插件可以帮你装。

## 使用

在任意会话里说一句，例如「帮我装 litman」；也可以在输入框打 `/litman`，在「技能」里选 `$litman-setup`。agent 会先检查有没有 litman，装之前先问你，然后运行官方安装命令，并把 litman 的 skill 接入 ZCode。装好后开一个新会话，ZCode 才会加载这些 skill。

插件会在你的电脑上做什么：见 [plugins/litman](./plugins/litman/README_CN.md)。

## 许可证

MIT。litman 本身使用 [AGPL-3.0](https://github.com/wqx1999/litman/blob/main/LICENSE)。
问题和 bug：[litman issues](https://github.com/wqx1999/litman/issues)。
