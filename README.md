<p align="center">
  <strong>Language:</strong> <strong>English</strong> · <a href="./README-zh.md"><strong>简体中文</strong></a>
</p>

# Square

Square is a lightweight visual habit tracker for Obsidian.

It is built for small daily things you want to actually see, tap, and keep inside your vault: habits, repeated actions, count-based goals, long-term targets, and simple routines.

Instead of turning check-ins into a separate database or a heavy dashboard, Square gives you a small-block board inside Obsidian. Open it, see what is on today, record quickly, and review your progress later.

Your project records still live in plain Markdown notes, so they stay readable, portable, and close to the rest of your knowledge base.

## Why Square

Many habit tools are good at reminding you, but they often pull your records into another system.

Square takes a smaller path:

- keep the daily action visible
- make recording fast enough to use every day
- keep the underlying records in Markdown
- use charts only when you want to look back

The goal is not to manage your life from a giant control panel. It is to make small repeated actions easier to continue.

## What It Feels Like

### A board made of small blocks

Each project appears as a block on the main board. You can check in from the board, open the project note, archive paused items, and keep today's view focused.

### A quick record modal

A check-in can include record text, date, count, fixed fields, and attachments. For simple projects, the flow can stay almost as quick as tapping a block.

### Built-in project templates

Square includes templates for common check-in styles, including single check-ins, repeated counts, target tracking, heatmaps, and trend-style projects. You can start without maintaining a separate template folder.

### Overview when you need it

Week, month, and ranking views help you look back at recent progress. The overview can also be opened in the sidebar when you want a compact reference view.

### Future planning from the month view

For future dates, you can arrange which projects should appear on that day. If a future day has a plan, that day can show only the planned project subset instead of every active project.

## Main Things You Can Do

- Create and edit Square projects from plugin settings.
- Use built-in templates to start faster.
- Check in from a visual small-block board.
- Record text, dates, counts, fixed fields, and attachments.
- Keep project data in Markdown notes.
- Review week, month, and ranking overviews.
- Plan future-day project visibility from the month view.
- Archive projects that are paused or no longer active.
- Use Square on both desktop and mobile Obsidian.

## License And Versions

Square is proprietary software.

The free state is intended for trying the core flow with a small number of projects. A license key unlocks broader project use.

License keys are stored through Obsidian's built-in secret storage and verified locally through signature validation. Square does not require a separate server-side account system for normal local use.

To get a license key, search for `焦应行` on Xiaohongshu.

## Privacy And Storage

- Project records are stored as Markdown notes in your Obsidian vault.
- Plugin settings stay in local Obsidian plugin data.
- The license key is stored through Obsidian SecretStorage.
- Square currently contains no client-side telemetry.
- Attachments are saved in your vault according to the plugin flow and your vault structure.

Do not publish your `.obsidian/plugins/square/data.json`. It may contain local settings, license state, and legacy configuration data.

## Installation

Square is distributed through GitHub Releases.

Because the current Obsidian Community Plugins rules require listed plugins to be open source, Square is not listed in the official plugin store in this release.

### Recommended: Install With BRAT

1. Install `BRAT` from Obsidian's community plugins.
2. Open BRAT settings and choose `Add Beta plugin`.
3. Add this repository URL:

```text
https://github.com/jiaoyingxing/square
```

4. Let BRAT install the latest release.
5. Enable `Square` in Obsidian's community plugins settings.

BRAT is the recommended path because it can help you update from GitHub Releases without manually replacing files each time.

### Manual Install

1. Download `main.js`, `manifest.json`, and `styles.css` from the latest GitHub Release.
2. Create this folder in your vault:

```text
.obsidian/plugins/square/
```

3. Put the three downloaded files into that folder.
4. Restart Obsidian, or reload community plugins.
5. Enable `Square` in Obsidian settings.

Do not use GitHub's auto-generated source archive as the install package. Use the release assets instead.

## Current Public Build

The current public version is `0.1.0`.

This first public build focuses on the main daily loop: create projects, choose templates, check in quickly, review progress, and keep records in Markdown notes.

See the [GitHub Releases](https://github.com/jiaoyingxing/square/releases) page for published builds.

## License

Square is proprietary software. All rights reserved.
