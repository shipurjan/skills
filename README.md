# Skills

A collection of Claude Code skills. The list only contains skills I actually
use day to day, which is why it's small - no bloat from skills that just sit
there unused.

## Installation

Install the skills into your Claude Code setup with:

```sh
npx skills add shipurjan/skills
```

## Claude Code settings

When setting up a new Claude Code instance, fetch the bundled settings file
and save it to `~/.claude/settings.local.json`:

```sh
curl -fsSL https://raw.githubusercontent.com/shipurjan/skills/refs/heads/master/claude_settings.json \
  -o ~/.claude/settings.local.json
```

## Skills

| Skill | Description | Source |
| --- | --- | --- |
| [caveman](caveman/SKILL.md) | Ultra-compressed communication mode that cuts token usage ~75% while preserving technical accuracy. | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/caveman) |
| [grill-me](grill-me/SKILL.md) | Interview the user relentlessly about a plan or design until reaching shared understanding. | [mattpocock/skills](https://github.com/mattpocock/skills/tree/main/grill-me) |
| [git-commit](git-commit/SKILL.md) | Conventional Commits message generation from diff analysis with intelligent staging. | [github/awesome-copilot](https://github.com/github/awesome-copilot/tree/main/skills/git-commit) |
