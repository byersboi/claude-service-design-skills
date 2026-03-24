# Service Design Skills for Claude Code

A comprehensive set of Claude Code skills covering the full spectrum of service design and design thinking practice. Built for designers at all levels — juniors building their craft, mid-weight practitioners deepening their toolkit, and leads running complex design programmes.

## Skills Included

| Skill | Description |
|-------|-------------|
| `double-diamond` | The design process framework — discover, define, develop, deliver |
| `service-blueprint` | Map frontstage, backstage, and support processes |
| `journey-map` | Customer journey mapping — current and future state |
| `stakeholder-map` | Identify, categorise, and engage stakeholders |
| `facilitation` | Design and run effective workshops |
| `ideation` | How Might We, Crazy 8s, brainstorming, and concept development |
| `user-research` | Plan and conduct research, synthesise insights |
| `problem-framing` | Define the right problem before jumping to solutions |
| `prototyping` | Service prototyping — role play, desktop walkthrough, storyboards |
| `personas` | Create research-based personas and empathy maps |
| `co-design` | Participatory design — involve users in the design process |
| `service-metrics` | Measure service quality and experience outcomes |
| `scottish-approach` | Scottish Approach to Service Design — 7 principles, life events lens, maturity assessment |

## Installation

### Option 1: Install via Claude Code plugin directory

```bash
# Clone this repo
git clone https://github.com/YOUR_USERNAME/service-design-skills.git ~/.claude/plugins/service-design

# Or symlink for active development
ln -s /path/to/this/repo ~/.claude/plugins/service-design
```

### Option 2: Copy individual skills

Copy any skill folder from `skills/` into your `~/.claude/skills/` directory.

## Usage

Once installed, skills activate automatically when you ask Claude relevant questions:

- *"Help me create a service blueprint for our onboarding flow"*
- *"I need to map the customer journey for a hospital appointment"*
- *"How do I run an ideation workshop remotely?"*
- *"Write me a discussion guide for user interviews"*
- *"Help me frame this problem properly before we start designing"*

## Skill Levels

Each skill includes guidance calibrated for different experience levels:

- **Junior** — core concepts, step-by-step guidance, common pitfalls to avoid
- **Mid-weight** — technique depth, facilitation nuance, quality markers
- **Senior / Lead** — strategic application, stakeholder management, programme thinking

## Contributing

Contributions welcome. If you spot something missing or want to improve a skill:

1. Fork this repo
2. Improve or add a skill following the structure in `skills/`
3. Open a pull request

## Skill Structure

Each skill follows the Claude Code skill format:

```
skills/skill-name/
├── SKILL.md          — core instructions loaded when skill triggers
└── references/       — detailed guides loaded on demand
    └── *.md
```

## Licence

MIT
