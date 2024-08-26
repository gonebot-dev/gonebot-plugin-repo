<div align="center">
  <a href="https://github.com/gonebot-dev">
    <img width="160" src="/assets/gonebot-logo.png" />
  </a>
  <h1>gonebot-plugin-repo(<a href="/README_zh.md">中文</a>)</h1>
  <p>📦 An official gonebot plugin repository</p>
</div>

## gonebot-plugin-repo

`grepo` is a plugin repository for [gonebot](https://github.com/gonebot-dev/gonebot)

## Usage

You should refer to [grepo](https://github.com/gonebot-dev/grepo) for more information.

## Looking for suitable plugin?

TBD

## Contribute

Write a xxx.json of new package in `plugins/x/xxx/xxx.json` and push a pull-requst to the dev branch.

For example, (plugins/t/tester/tester.json)[https://github.com/gonebot-dev/gonebot-plugin-repo/blob/main/plugins/t/tester/tester.json]

#### JSON Principle

The correct json file for a plugin looks like this:
```json
{
    "latest": "github.com/Kingcxp/gonebot-plugin-test",
    "v0.0.1": "github.com/Kingcxp/gonebot-plugin-test@1e5e55f"
}
```

In the json file, the must be a `latest` field, and it should contain and only contain path to the plugin package. 

Then version fields are more flexible, as long as they don't lead to any errors.