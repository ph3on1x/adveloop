# adveloop has moved

This project now lives in **[ph3on1x/agent-plugins-skills](https://github.com/ph3on1x/agent-plugins-skills/tree/main/skills/adveloop)**, together with my other
agent skills and plugins. This repository is archived and no longer updated. The full git history and
release tags were carried over to the new repository.

## Install

Claude Code:

```text
/plugin marketplace add ph3on1x/agent-plugins-skills
/plugin install adveloop@ph3on1x
```

Codex, Cursor, Gemini CLI, Antigravity and other agents:

```bash
npx skills add ph3on1x/agent-plugins-skills --skill adveloop
```

## Already installed from this repository?

Nothing to do: this repository's marketplace now forwards to the new location, so `/plugin marketplace update adveloop` keeps `adveloop@adveloop` updated. To move to the new marketplace, run `claude plugin uninstall adveloop@adveloop`, then the Claude Code commands above.
