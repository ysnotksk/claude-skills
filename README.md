# Claude Code Skills

Custom [skills](https://docs.anthropic.com/en/docs/claude-code/skills) for [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview).

## Available Skills

| Skill | Command | Language | Description |
|-------|---------|----------|-------------|
| [researcher-en](./researcher-en/) | `/researcher-en` | English | Generate comprehensive researcher profiles with full publication lists, methodology details, and footnoted sources. Supports forward lookup (name → profile) and reverse lookup (concept → researchers). |
| [researcher-jp](./researcher-jp/) | `/researcher-jp` | Japanese | 研究者のプロフィール・全研究実績を体系的にまとめたドキュメントを生成。正引き（研究者名→プロフィール）と逆引き（概念名→研究者）に対応。 |

## Installation

Copy a skill directory into your Claude Code skills folder:

```bash
# Global (all projects)
cp -r researcher-en ~/.claude/skills/
cp -r researcher-jp ~/.claude/skills/

# Project-level
cp -r researcher-en .claude/skills/
```

Then start a new Claude Code session. The skill will be available as a slash command.

## Usage Examples

```
/researcher-en Daniel Kahneman
/researcher-en Who created flow theory?
/researcher-jp ダニエル・カーネマン
/researcher-jp フロー理論を作った人は？
```

## License

MIT
