# GitHub Readme Activity Graph

Trimmed fork of [Ashutosh00710/github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) (MIT), self-hosted on Vercel.

Defaults: `rivera` theme (`0d1117` background, `58a6ff` line/area), area on, border hidden.

```md
![Activity graph](https://<your-deployment>.vercel.app/graph?username=JosepRivera)
```

## Parameters

| Param | Default | Notes |
|---|---|---|
| `username` | — | required |
| `theme` | `rivera` | any theme in [THEMES.md](THEMES.md) |
| `bg_color`, `color`, `title_color`, `line`, `point`, `area_color`, `border_color` | theme | hex without `#` |
| `area` | `true` | `false` to draw only the line |
| `hide_border` | `true` | `false` to show the border |
| `hide_title` / `custom_title` | `false` / name | |
| `radius` | `0` | 0–16 |
| `height` | `420` | 200–600 |
| `days` | `31` | 1–90, or `from`/`to` as `YYYY-MM-DD` |
| `grid` | `true` | |

## Deploy

Import the repo in Vercel and set the `TOKEN` env var to a GitHub token (classic, no scopes needed).
