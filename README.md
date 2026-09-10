# Plans & Important Dates for Super Productivity

A full-page [Super Productivity](https://github.com/johannesjo/super-productivity) plugin that keeps long-term goals and important dates in one planning view.

中文说明见下方。

## Features

- Create long-term goals and important dates from one Add menu
- Track goal area, status, progress, stages, target date, and linked projects
- Group dates into Today, Upcoming, Past, and Archived
- Link dates to a Super Productivity project, goal, or course
- Archive, restore, complete, edit, and delete planning items
- English and Chinese translations that follow the SP language
- Synced plugin storage for planning data and display settings

## Installation

1. Download `sp-plans-important-dates.zip` from GitHub Releases.
2. Open Super Productivity → Settings → Plugins.
3. Import the ZIP file and restart Super Productivity if requested.
4. Open **Plans & Important Dates** from the plugin entry.

Requires Super Productivity **18.21.2 or later**.

## Data and permissions

The plugin reads project names for optional linking, saves only its own plugin data, opens a full-page view, and shows confirmation messages. It does not modify or delete Super Productivity tasks or projects.

## 中文说明

该插件把长期目标和重要日期放在同一个页面中，可以记录目标进度、阶段、关联项目，以及考试、报名、截止日期等重要节点。界面会跟随 Super Productivity 的中英文语言设置。

## Development and packaging

This is a dependency-free iframe plugin. Package the following files with `manifest.json` at the ZIP root:

```text
manifest.json
index.html
icon.svg
i18n/
```

```powershell
Compress-Archive -Path manifest.json,index.html,icon.svg,i18n -DestinationPath sp-plans-important-dates.zip
```

## License

[MIT](LICENSE)
