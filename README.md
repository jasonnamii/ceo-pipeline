# ceo-pipeline

**CEO's blueprint to roadmap to action list — auto-cascade with team handoff briefs and category assignment.**

## Goal

Strategic vision without executable actions remains a dream. CEO-Pipeline transforms a high-level blueprint or roadmap into an action list automatically categorized by domain (planning, design, development) with team handoff briefs for each action. The "shower effect" ensures ideas flow from thinking to doing.

## When & How to Use

Use this skill when you have a CEO-level blueprint, strategy statement, or roadmap that needs to become actionable. Provide your vision and the skill cascades it into three tiers: auto-categorizes actions into planning, design, or development; creates team-specific handoff briefs; surfaces dependencies and sequencing. Input blueprint → categorized action list with team briefs.

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| Product strategy to sprint plan | `"CEO-pipeline: ship 3 new integrations in Q2"` | Blueprint→planning actions + design actions + dev actions; each with team brief |
| Organizational restructure | `"Pipeline: move to product-led GTM by Q3"` | Blueprint→planning (hire, incentives) + design (playbook) + dev (automation); handoff to each team |
| Market expansion | `"Expand to APAC — turn this into a 6-month plan"` | Strategy→planning (localization, hiring) + design (regional GTM) + dev (product adaptation) |

## Key Features

- Automatic action categorization: Planning, Design, Development, or hybrid
- AI-generated team handoff briefs for each action—context, success criteria, owner guidance
- Dependency tracking and sequencing recommendations
- Resource estimates and timeline mapping
- Works across all strategic initiatives: products, organizations, markets, crises

## Works With

- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — planning-skill structures the blueprint; ceo-pipeline executes it
- **[deliverable-engine](https://github.com/jasonnamii/deliverable-engine)** — deliverable-engine formats roadmaps and action lists for presentation
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — biz-skill diagnoses; ceo-pipeline executes the recommended strategy

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

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
