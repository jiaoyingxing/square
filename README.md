<p align="center">
  <strong>Language:</strong> <strong>English</strong> · <a href="./README-zh.md"><strong>简体中文</strong></a>
</p>

# Square

> Turn daily actions in Obsidian into small blocks you can see and tap.

Many people keep goals, reviews, journals, and project notes in Obsidian, but still use another app when it is time to check in.

Square is built for that gap. You do not have to leave your vault, and you do not have to move habit records into another system. The things you want to continue appear as small blocks on a lightweight board. You open one, record what happened, and the result still goes back to ordinary Markdown notes.

Square is not mainly about reminders, pressure, points, or a habit community. It is closer to a light operating surface on top of Obsidian: a way to make your daily actions easier to see, easier to record, and easier to review without pulling them away from your notes.

## ✨ What It Solves

A task list is useful for planning, but it is not always the best shape for repeated daily records.

A typical habit app is quick to tap, but it often moves your history into another account, another database, and another interface.

Square sits between those two. It keeps the file-based, long-term control of Obsidian, while adding a more visual daily entry point. You do not have to open a specific note and find the right place to write. You also do not have to manage a heavy habit dashboard. Open Square, see the blocks, record once, and move on.

## 🧩 What It Really Is

Square is not “another habit app”. It is a visual layer for Markdown project notes.

Each project is still a note. The small block is just the daily entry point for that note. You interact with the block, but the history accumulates in the project note. That means check-ins are not trapped inside a closed app state. They can continue to live beside your journal, reviews, project materials, and knowledge base.

Templates are not meant to turn Square into a configuration maze. They help each project start with the right recording shape. Some projects only need completion. Some need counts. Some need target progress. Some make more sense as long-term trends. Square tries to make that choice early, so the daily action can stay light.

## 🟩 What Daily Use Feels Like

You can think of Square as a small today-board inside Obsidian.

Open Square in the morning, or whenever you need to record something, and you see a group of project blocks. Each block represents something you are continuing or observing: reading, exercise, water, writing, vocabulary, recovery, sleep, piano practice, or any small routine that deserves a trace.

Open a block and you get a quick record modal. For simple projects, it can be close to a single confirmation. When you need more detail, you can add text, adjust the date, change the count, fill fixed fields, or attach something. After saving, the record is written back to the matching Markdown project note.

When you want to look back, open the week, month, or ranking view. Charts are not the main workload. They are a second layer for review.

## 🌱 How It Differs From A Typical Habit App

Most habit apps put streaks at the center: reminders, make-up check-ins, consecutive days, leaderboards, badges, social pressure, and cloud sync.

Square centers something else: can your daily records stay naturally inside Obsidian?

That changes the product shape. The main board stays light instead of becoming a management backend. A record can be more than a checkmark: it can include counts, text, fixed fields, and attachments. Overview charts are for review, not for taking over the daily board. Archiving simply moves projects out of the active daily view; it does not become a separate management product.

If you need strong reminders, social check-ins, or a cloud habit community, Square is not that kind of product.

If what you want is “my check-ins should belong to my vault”, Square is much closer to that idea.

## 🧭 Who It Is For

Square is a better fit if your daily records, goals, or project reviews already live in Obsidian.

If a task list feels too cold, but a separate habit app feels too far away from your notes, Square offers a middle shape: more visual than a task list, but more file-friendly than a standalone habit tracker.

It is especially useful when you want to record not only whether something happened, but also how much happened, what you noticed, or what material belonged with that action.

## 🔐 License And Storage

Square is proprietary software.

The free state is intended for trying the core flow with a small number of projects. A license key unlocks broader project use.

License keys are stored through Obsidian's built-in secret storage and verified locally through signature validation. Square does not require a separate server-side account system for normal local use.

Project records are stored as Markdown notes in your Obsidian vault. Plugin settings stay in local Obsidian plugin data. Square currently contains no client-side telemetry.

Do not publish your `.obsidian/plugins/square/data.json`. It may contain local settings, license state, and legacy configuration data.

To get a license key, search for `焦应行` on Xiaohongshu.

## 📦 Installation

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

See the [GitHub Releases](https://github.com/jiaoyingxing/square/releases) page for published builds.

## License

Square is proprietary software. All rights reserved.
