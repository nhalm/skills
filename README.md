# skills

Claude Code plugin marketplace with one plugin, `nhalm`.

| Skill | For |
|---|---|
| `canonlog` | [canonlog](https://github.com/nhalm/canonlog) canonical logging |
| `chikit` | [chikit](https://github.com/nhalm/chikit) Chi middleware |
| `golang-pro` | Go style, testing, and CLI conventions |
| `pgxkit` | [pgxkit](https://github.com/nhalm/pgxkit) pgx/v5 toolkit |
| `skimatik` | [skimatik](https://github.com/nhalm/skimatik) SQL code generator |

Skills are invoked as `nhalm:<skill>`.

## Install

```sh
claude plugin marketplace add nhalm/skills
claude plugin install nhalm@nhalm
```

Or in `~/.claude/settings.json`:

```json
{
  "extraKnownMarketplaces": [
    { "name": "nhalm", "url": "https://github.com/nhalm/skills", "autoUpdate": true }
  ],
  "enabledPlugins": { "nhalm@nhalm": true }
}
```

## Validate

```sh
claude plugin validate .
```
