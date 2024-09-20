# 本仓库已不再更新，已经整合到：https://github.com/UnrealMultiple/TShockPlugin，后续更新均会发布至此仓库
# This repository is no longer updated and has been integrated into: https://github.com/UnrealMultiple/TShockPlugin. All future updates will be published there.
# InvincibilityPlugin: Terraria 服务器的无敌插件

## 简介
`InvincibilityPlugin`是一个为Terraria服务器设计的插件，它允许管理员在一定时间内给予玩家无敌状态。这个插件由`肝帝熙恩`开发，旨在为服务器增添更多的乐趣和灵活性。

## 主要功能
- **限时god无敌**：通过命令行给予玩家一定时间的无敌状态，玩家在此期间绝对不会受到伤害。
- **限时无敌帧无敌**：通过命令行给予玩家一定时间的无敌状态，玩家在此期间不会受到大部分伤害。
- **自定义提示**：插件支持自定义开启和关闭无敌状态时的提示信息。
- **权限控制**：确保只有拥有特定权限的玩家才能使用无敌命令。

## 安装与使用
1. 下载`InvincibilityPlugin.dll`文件。
2. 将文件放置到你的Terraria服务器的`Plugins`目录下。
3. 启动服务器，插件将自动加载。
4. 使用`/tgod或限时god无敌 <秒数>`命令给予玩家无敌状态，例如：`/tgod 60`将给予玩家60秒的godmode无敌时间。
5.  使用`/tframe或限时无敌帧无敌 <秒数>`命令给予玩家无敌状态，例如：`/tframe 60`将给予玩家60秒的无敌帧无敌时间。

## 配置
插件的配置文件位于`TShock.SavePath`目录下的`限时无敌.json`。你可以通过编辑这个文件来自定义无敌状态的提示信息。

### 配置示例
```json
{
  "插件自带god无敌开启提示": true,
  "god无敌开启提示自定义文本": "",
  "god无敌关闭提示自定义文本": "你的无敌已关闭！",
  "插件自带无敌帧开启提示": true,
  "无敌帧开始提示文本": "",
  "无敌帧结束提示文本": ""
}
```

## 权限
确保你的玩家拥有`限时god无敌`权限才能使用无敌命令。
确保你的玩家拥有`限时无敌帧无敌`权限才能使用无敌命令。

## 支持与反馈
- 如果您在使用过程中遇到问题或有任何建议，欢迎在官方论坛或社区中提出issues或pr。
- github仓库：https://github.com/THEXN/Iimitedinvincible
