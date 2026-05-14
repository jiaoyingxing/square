# Square

Square is a lightweight habit tracker for Obsidian.

It turns daily habits and recurring tasks into a visual square board. Each project is still stored as a normal Markdown note, so your records stay readable, portable, and easy to inspect.

This public repository only hosts installable plugin artifacts. The source code, development notes, tests, and internal tooling are maintained separately.

## Features

- Visual square board for quick daily check-ins
- One Markdown note per project
- Built-in templates for single check-ins, repeated counts, target tracking, heatmaps, and trends
- Quick entry modal for record text, date, count, fixed fields, and attachments
- Overview charts with week, month, and ranking views
- Future planning from the month view
- Archive support for completed or paused projects
- Works on both desktop and mobile Obsidian

## Install

1. Download `main.js`, `manifest.json`, and `styles.css` from this repository.
2. Put them into your vault at `.obsidian/plugins/square/`.
3. Restart Obsidian or reload plugins.
4. Enable `Square` in Obsidian's community plugins settings.

## Version 0.1.0

This first public artifact build includes the core Square workflow:

- Create and edit projects from the plugin settings
- Choose built-in templates without maintaining template files in your vault
- Track single or repeated daily check-ins
- Set target-based projects with progress charts
- Add structured fixed fields without replacing normal record text
- Open overview charts in the main view or sidebar
- Keep project records in Markdown files

## Repository Contents

- `main.js`: compiled plugin runtime
- `manifest.json`: Obsidian plugin manifest
- `styles.css`: plugin styles
- `versions.json`: Obsidian compatibility map

## License

Square is proprietary software. All rights reserved.

---

# Square 小方块

Square 小方块是一个轻量的 Obsidian 打卡插件。

它把日常习惯、重复任务和目标记录变成一个可视化的小方块主界面。每个项目仍然对应一篇普通 Markdown 笔记，所以记录可以阅读、迁移，也方便手动检查。

这个公开仓库只放可安装的插件构筑物。源码、开发文档、测试和内部脚本在单独的私有工作区维护。

## 功能

- 用小方块快速完成每日打卡
- 每个项目对应一篇 Markdown 笔记
- 内置单次、多次、定目标、热力图、趋势图等模板
- 快速记录弹框支持记录内容、日期、次数、固定字段和附件
- 总览图表包含周视图、月视图和排行视图
- 可在月视图安排未来某天显示哪些项目
- 支持归档暂停或完成的项目
- 兼顾 Obsidian 桌面端和移动端

## 安装

1. 下载本仓库里的 `main.js`、`manifest.json` 和 `styles.css`。
2. 放入你的 Obsidian 笔记库目录：`.obsidian/plugins/square/`。
3. 重启 Obsidian，或重新加载插件。
4. 在 Obsidian 第三方插件设置中启用 `Square`。

## 0.1.0 版本内容

这个公开构筑物版本包含 Square 的核心工作流：

- 在插件设置中创建和编辑项目
- 使用内置模板，不再需要维护模板文件夹
- 支持单次打卡和多次计数
- 支持定目标项目和进度图表
- 支持固定字段，但不替代正常记录内容
- 可在主界面或侧栏查看总览图表
- 项目记录继续保存在 Markdown 文件里

## 仓库文件

- `main.js`：编译后的插件运行文件
- `manifest.json`：Obsidian 插件清单
- `styles.css`：插件样式
- `versions.json`：Obsidian 兼容版本记录

## 授权

Square 小方块为专有软件，保留所有权利。
