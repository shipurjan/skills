# Skills

A collection of Claude Code skills. The list only contains skills I actually
use day to day, which is why it's small - no bloat from skills that just sit
there unused. Some skills may be slightly modified from their original
sources to fine-tune them to my workflow.

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
| [caveman](caveman/SKILL.md) | Ultra-compressed communication mode that cuts token usage ~75% while preserving technical accuracy. | [mattpocock/skills](https://github.com/mattpocock/skills/tree/e3b90b5238f38cdea5996e16861dcae28ef52eda/skills/productivity/caveman) |
| [grill-me](grill-me/SKILL.md) | Interview the user relentlessly about a plan or design until reaching shared understanding. | [mattpocock/skills](https://github.com/mattpocock/skills/tree/e3b90b5238f38cdea5996e16861dcae28ef52eda/skills/productivity/grill-me) |
| [grill-with-docs](grill-with-docs/SKILL.md) | Grilling session that challenges a plan against the existing domain model, sharpens terminology, and updates documentation (CONTEXT.md, ADRs) as decisions crystallise. | [mattpocock/skills](https://github.com/mattpocock/skills/tree/e3b90b5238f38cdea5996e16861dcae28ef52eda/skills/engineering/grill-with-docs) |
| [git-commit](git-commit/SKILL.md) | Conventional Commits message generation from diff analysis with intelligent staging. | [github/awesome-copilot](https://github.com/github/awesome-copilot/tree/e24be77e6f203409cf99ab7d5a67e1540cb386d3/skills/git-commit) |
| [improve](improve/SKILL.md) | Audits a codebase and writes self-contained implementation plans for cheaper agents to execute — the audit and spec happen on the capable model, execution is handed off. | [shadcn/improve](https://github.com/shadcn/improve/tree/03369ee6d7cafbfcecc4346539b05b3dc0a603bb/skills/improve) |
