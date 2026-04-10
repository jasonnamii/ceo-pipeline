# CEO Pipeline

**Blueprint → Roadmap → Action List cascade.**

The CEO defines a blueprint, Claude generates a roadmap with milestones, then cascades into categorized action items (planning / design / development) with team briefs.

### Example Prompts

```
"Here's my product blueprint: [...]" → roadmap→action items by domain→team briefs
"Build a roadmap" → milestone-based with dependencies
"Generate action list" → cascade into planning/design/dev tasks
```

## Installation

```bash
git clone https://github.com/jasonnamii/ceo-pipeline.git ~/.claude/skills/ceo-pipeline
```

## Update

```bash
cd ~/.claude/skills/ceo-pipeline && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25 custom skills. See the full catalog: [https://github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
