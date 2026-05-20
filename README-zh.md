# Square 小方块

[English](README.md) | [版本说明](RELEASE_NOTES-zh.md)

Square 小方块是一个轻量的 Obsidian 打卡插件。

如果你想把日常打卡、重复项目和目标记录继续放在普通 Markdown 笔记里，而不是另外搭一套系统，Square 会给你一个直接可点的小方块主界面：今天要做什么一眼能看到，点一下就能记录，后面还能用周视图、月视图和排行图表回看。

## 功能亮点

- 从内置模板直接开始：单次、多次、定目标、热力图、趋势图都已经备好。
- 一个快速记录弹窗里就能写记录、日期、次数、固定字段和附件。
- 周视图、月视图和排行视图都能在主界面或侧栏打开。
- 月视图可以提前安排未来日期要显示哪些项目。
- 每个项目仍然是一篇普通 Markdown 笔记，记录可以阅读、迁移，也方便手动检查。
- 项目可以随时归档，暂停后也能留着。
- 兼顾 Obsidian 桌面端和移动端。

## 安装

Square 小方块是专有软件。由于 Obsidian 官方插件商店的新规则不支持非开源插件上架，所以 Square 通过 GitHub Releases 分发。

推荐用 BRAT 安装和更新：

1. 先从 Obsidian 第三方插件里安装 `BRAT`。
2. 打开 BRAT 设置，选择 `Add Beta plugin`。
3. 填入 `https://github.com/jiaoyingxing/square`。
4. 让 BRAT 安装最新 release，然后在 Obsidian 第三方插件设置中启用 `Square`。

也可以手动安装：

1. 从最新 GitHub Release 下载 `main.js`、`manifest.json` 和 `styles.css`。
2. 放入你的 Obsidian 笔记库目录：`.obsidian/plugins/square/`。
3. 重启 Obsidian，或重新加载插件。
4. 在 Obsidian 第三方插件设置中启用 `Square`。

## 版本说明

当前公开版本是 `0.1.0`。

这一版先把最核心的日常闭环跑通：创建项目、选择模板、快速记录、查看总览，记录仍然留在普通 Markdown 笔记里。

完整版本说明见 [RELEASE_NOTES-zh.md](RELEASE_NOTES-zh.md)。

## 仓库文件

- `main.js`：编译后的插件运行文件
- `manifest.json`：Obsidian 插件清单
- `styles.css`：插件样式
- `versions.json`：Obsidian 兼容版本记录

## 授权

Square 小方块为专有软件，保留所有权利。
