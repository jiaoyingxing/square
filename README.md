# Square

[中文说明](README-zh.md) | [Release notes](RELEASE_NOTES.md)

Square is a lightweight habit tracker for Obsidian.

If you want daily check-ins, recurring projects, and target tracking to stay inside plain Markdown notes instead of a separate system, Square gives you a fast visual board: see what needs attention today, check in with one click, and review your progress later with week, month, and ranking views.

## Highlights

- Start with built-in templates for single check-ins, repeated counts, target tracking, heatmaps, and trends.
- Record text, date, count, fixed fields, and attachments from one quick entry modal.
- Open week, month, and ranking overviews in the main view or sidebar.
- Plan which projects should appear on future dates from the month view.
- Keep each project as a plain Markdown note, so records stay readable and portable.
- Archive completed or paused projects without losing them.
- Works on both desktop and mobile Obsidian.

## Install

Square is proprietary software. Under the current Obsidian Community Plugins rules, non-open-source plugins cannot be listed in the official plugin store, so Square is distributed through GitHub Releases.

Recommended: install with BRAT.

1. Install the `BRAT` plugin from Obsidian's community plugins.
2. Open BRAT settings and choose `Add Beta plugin`.
3. Add `https://github.com/jiaoyingxing/square`.
4. Let BRAT install the latest release, then enable `Square` in Obsidian's community plugins settings.

Manual install is also available:

1. Download `main.js`, `manifest.json`, and `styles.css` from the latest GitHub Release.
2. Put them into your vault at `.obsidian/plugins/square/`.
3. Restart Obsidian or reload plugins.
4. Enable `Square` in Obsidian's community plugins settings.

## Release Notes

The current public version is `0.1.0`.

This version focuses on the core daily loop: create projects, choose templates, record quickly, review progress, and keep the underlying records in plain Markdown notes.

See [RELEASE_NOTES.md](RELEASE_NOTES.md) for the full release notes.

## Repository Contents

- `main.js`: compiled plugin file
- `manifest.json`: Obsidian plugin manifest
- `styles.css`: plugin styles
- `versions.json`: Obsidian compatibility map

## License

Square is proprietary software. All rights reserved.
