<div align="center">
  <a href="https://github.com/gonebot-dev">
    <img width="160" src="/assets/gonebot-logo.png" />
  </a>
  <h1>gonebot-plugin-repo(<a href="/README.md">English</a>)</h1>
  <p>📦 Gonebot 官方插件仓库</p>
</div>

## gonebot-plugin-repo

`grepo` 是 [gonebot](https://github.com/gonebot-dev/gonebot) 的一个插件仓库

它基于 gonebot 提供的运行时。通过调用这个模块中的简单方法，你可以轻松地从我们的 [官方插件仓库](https://github.com/gonebot-dev/gonebot-plugin-repo) 安装和更新 gonebot 插件！

## 用法

前往 [grepo](https://github.com/gonebot-dev/grepo) 获取更多信息。

## 正在寻找合适的插件？

尚未完成

## 贡献

为你的插件编写一个 `xxx.json` 文件，并将其放在 `plugins/x/xxx/xxx.json` 中，然后向 dev 分支提交一个 pull request。

例如，(plugins/t/tester/tester.json)[https://github.com/gonebot-dev/gonebot-plugin-repo/blob/main/plugins/t/tester/tester.json]

#### JSON 原则

正确的插件 json 文件看起来像这样：
```json
{
    "latest": "github.com/Kingcxp/gonebot-plugin-test",
    "v0.0.1": "github.com/Kingcxp/gonebot-plugin-test@1e5e55f"
}
```

在 json 文件中，必须有一个 `latest` 字段，并且它应该只包含插件包的路径。

而版本字段更加灵活，只要不会导致任何错误就行。