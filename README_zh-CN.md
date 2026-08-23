<!--suppress ALL -->
<p align="center">
    <a href="README.md">English</a> | <b>简体中文</b>
</p>
<p align="center">
    <img src="images/banner.png" alt="HuskHomesMenu" />
    <a href="https://github.com/Obydux/HuskHomesMenu/actions/workflows/java_ci.yml">
        <img src="https://img.shields.io/github/actions/workflow/status/Obydux/HuskHomesMenu/java_ci.yml?branch=master&logo=github"/>
    </a>
    <a href="https://discord.gg/sQ6VmWDzN3">
        <img src="https://img.shields.io/discord/1383468620566237234.svg?label=&logo=discord&logoColor=fff&color=7389D8&labelColor=6A7EC2" />
    </a>
    <br/>
    <b>
        <a href="https://william278.net/docs/huskhomes/gui-add-on">文档</a>
    </b> — 
    <b>
        <a href="https://github.com/WiIIiam278/HuskHomes/">Homes</a>
    </b> — 
    <b>
        <a href="https://github.com/Obydux/HuskHomesMenu/issues">问题反馈</a>
    </b>
</p>
<br>

**HuskHomesMenu** 是一个面向 [HuskHomes](https://github.com/WiIIiam278/HuskHomes) 的 GUI 附加插件，适用于 1.20.6+ 的 Paper 服务器。它提供了箱子风格的图形用户界面（GUI），用于浏览家/地标列表以及编辑家。

当你输入 `/homelist`、`/phomelist` 或 `/warplist` 时，它会取代 HuskHomes 自带的聊天菜单系统，并包含基于铁砧的重命名与描述编辑功能，方便轻松编辑。

![菜单截图](images/menu-screenshot.png)

如果你更喜欢使用菜单浏览，或者想为通过 Geyser 连接的基岩版玩家提供更好的支持，那么这个附加插件非常适合你。

## 安装
1. 在你的服务器上安装 HuskHomes
2. 下载 HuskHomesMenu 并将其放入服务器的 `~/plugins/` 文件夹

## 使用
只需使用你熟悉的列表命令即可呼出家或地标列表。然后你可以：
- **左键点击**：传送到某个家/地标
- **右键点击**：进行编辑
- **潜行 + 左键点击**：将列表中家的图标改为主手上物品的类型

使用翻页按钮切换页面。

## 切换语言
插件默认使用英文。如需使用中文，请修改服务器 `plugins/HuskHomesMenu/config.yml` 中的配置：

```yaml
language: zh-cn
```

保存后重启服务器即可。插件会自动根据该配置生成对应的 `messages-zh-cn.yml` 语言文件。
