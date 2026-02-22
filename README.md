# Claude Code Skills

Custom [skills](https://docs.anthropic.com/en/docs/claude-code/skills) for [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview).

## Available Skills

| Skill | Command | Description |
|-------|---------|-------------|
| [researcher](./researcher/) | `/researcher` | Generate comprehensive researcher profiles with full publication lists, methodology details, and footnoted sources. Supports forward lookup (name → profile) and reverse lookup (concept → researchers). |

## Installation

Copy a skill directory into your Claude Code skills folder:

```bash
# Global (all projects)
cp -r researcher ~/.claude/skills/

# Project-level
cp -r researcher .claude/skills/
```

Then start a new Claude Code session. The skill will be available as a slash command.

## Usage Examples

```
/researcher ダニエル・カーネマン
/researcher Daniel Kahneman
/researcher フロー理論を作った人は？
```

## License

MIT
