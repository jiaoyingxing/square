<p align="center">
  <strong>Language:</strong> <strong>English</strong> · <a href="./README-zh.md"><strong>简体中文</strong></a>
</p>

# Square

Square is a visual check-in layer for Obsidian.

You tap small blocks every day. The actual records still stay in Markdown.

If your goals, habits, routines, and reviews already live in Obsidian, but daily check-ins still happen in another app, Square brings that loop back into your vault: what to do today, what you just recorded, and how things have been going recently.

It is not a reminder app, a habit community, or a new database. It is a lightweight operating layer: projects become small blocks, check-ins are written back to project notes, and charts are there when you want to review.

## What Square Is

Square organizes check-ins in Obsidian through a few clear layers:

- Main board: open Square and see the projects that need attention today.
- Quick record modal: record text, date, count, fixed fields, and attachments.
- Markdown project notes: each project has its own note, so history stays readable, portable, and easy to inspect.
- Built-in templates: start from common check-in patterns such as single check-ins, repeated counts, target tracking, heatmaps, and trend-style records.
- Overview charts: use week, month, and ranking views when you want to look back.

So the core idea is not “another habit app”. Square adds a more visual and more direct check-in layer to Obsidian.

## How You Use It

1. Create a project in plugin settings, such as reading, exercise, water, writing, or vocabulary.
2. Choose a template that matches the project: single completion, repeated counts, target progress, or trend records.
3. Return to the Square board. The project appears as a small block.
4. When it is time to record, open the block and add text, date, count, or fixed fields.
5. The check-in is saved to the matching Markdown project note.
6. When you want to review, open the week, month, or ranking view.
7. If a future date should show only selected projects, arrange that from the month view.

The daily path can stay short: open Square, see the blocks, record, leave.

## How It Is Different From A Typical Habit App

Most habit apps are built around reminders, streaks, social pressure, points, or cloud accounts. Square is aimed at a different use case.

Square focuses on four things:

- Your records stay in your vault: check-ins are saved in Obsidian Markdown notes instead of being locked inside another app.
- The daily action stays light: the main board shows the blocks you need today, not a heavy management backend.
- Projects can record more than a checkmark: some need completion, some need counts, some need targets, and some make more sense as trends.
- Review does not get in the way of recording: charts are for looking back, while the main board stays focused on today.

If you need strong reminders, social check-ins, cross-platform cloud sync, or a full habit community, Square is not that kind of product.

If you want check-ins to stay inside Obsidian and feel more visual than a normal task list, Square is much closer to that need.

## Main Things You Can Do

- Create and edit Square projects.
- Start from built-in templates for common check-in styles.
- Record quickly from the small-block board.
- Add text, dates, counts, fixed fields, and attachments.
- Store each project as a Markdown note.
- Review progress with week, month, and ranking views.
- Arrange future-day project visibility from the month view.
- Archive projects that are paused or finished.
- Use Square on both desktop and mobile Obsidian.

## Who It Is For

Square is a better fit if you:

- already keep daily notes or project records in Obsidian
- want a check-in surface that feels more direct than a task list
- do not want another separate database just for habits
- want records to remain readable Markdown over time
- need to record not only whether something happened, but also how much or what happened

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
