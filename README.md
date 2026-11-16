# Immersive Experience Studio

A multidisciplinary creative technology studio skill for planning, art-directing, designing, building, and critically refining distinctive landing pages and immersive digital brand experiences.

## Overview

This skill enables agents to act as a creative technology studio — creating digital experiences through original art direction, storytelling, interaction, motion, and rigorous engineering. The goal is not visual novelty for its own sake; it is a distinctive, memorable experience that communicates clearly and achieves the project's real objective.

## Core Principles

1. **Concept before components** — Understand the brand, audience, offer, conversion goal, content, constraints, and existing implementation before choosing a visual direction.
2. **Originality over imitation** — Research excellent work to understand craft and patterns. Never clone a reference or apply a generic award-site aesthetic.
3. **Story and clarity together** — Cinematic presentation must not obscure the offer, navigation, content, accessibility, or primary action.
4. **Technology serves the concept** — Use 3D, WebGL, shaders, scroll choreography, sound, and complex motion only when they materially improve the experience.
5. **Preserve what works** — Inspect the repository and retain working business logic, routes, integrations, content, and interactions.
6. **Rendered quality is the measure** — A successful build is not proof of a successful design. Inspect the actual result and iterate.
7. **No false guarantees** — Never promise awards or claim a design is award-winning.

## Mandatory Production Workflow

The skill enforces a three-stage gated workflow:

### Stage 1 — Creative Direction
- Inspect project, brief, brand materials, assets, and constraints
- Develop three genuinely different creative territories
- Deliver a Creative Direction Proposal for approval

### Stage 2 — Experience Architecture
- Translate approved concept into page/site structure and visitor journey
- Define information architecture, section sequence, content hierarchy, navigation, CTAs
- Deliver an Experience Blueprint for approval

### Stage 3 — Creative Engineering
- Implement approved direction in maintainable, production-quality code
- Preserve existing functionality and real content
- Run build, lint, type checks, tests, and browser interaction checks
- Inspect rendered screenshots and iterate until no major defects remain

## Installation

### For Any Agent Supporting Markdown Skills

Copy the `immersive-experience-studio` directory to your agent's skills directory:

```
skills/
└── immersive-experience-studio/
    ├── SKILL.md
    ├── references/
    │   ├── accessibility.md
    │   ├── art-direction.md
    │   ├── motion-design.md
    │   └── visual-quality.md
    ├── templates/
    │   ├── creative-brief.md
    │   └── experience-blueprint.md
    └── workflows/
        ├── creative-direction.md
        ├── creative-engineering.md
        └── experience-architecture.md
```

**Common locations:**
- Hermes: `~/.hermes/skills/`
- Codex: `~/.codex/skills/`
- OpenCode: `~/.opencode/skill/`
- Claude Code: `~/.claude/skills/` or `~/.agents/skills/`
- Custom: wherever your agent loads skills from

### For Git Submodule (Recommended)

```bash
cd your-project
git submodule add https://github.com/zius/immersive-experience-studio.git .skills/immersive-experience-studio
# Then point your agent to .skills/immersive-experience-studio
```

## Usage

Once installed, the skill will be automatically available to your agent. Invoke it by describing a task that matches its description:

> "Plan, art-direct, design, build, and critically refine distinctive landing pages and immersive digital brand experiences."

The agent will then follow the three-stage workflow, presenting deliverables at each gate for your approval.

### Example Prompts

```
"Create a premium landing page for our AI-powered code review tool. We need to communicate technical credibility while feeling distinctive."

"Redesign our brand website — it currently feels like a generic template. We want something that reflects our positioning as a precision engineering consultancy."

"Build an immersive campaign experience for our product launch. The concept should tell a story while making the product understandable."
```

## Skill Structure

```
immersive-experience-studio/
├── SKILL.md                      # Main skill definition
├── references/
│   ├── accessibility.md          # Accessibility requirements
│   ├── art-direction.md          # Composition, typography, color, imagery
│   ├── motion-design.md          # Purposeful motion principles
│   └── visual-quality.md         # Acceptance checklist
├── templates/
│   ├── creative-brief.md         # Project intake template
│   └── experience-blueprint.md   # Stage 2 deliverable template
└── workflows/
    ├── creative-direction.md     # Stage 1 workflow
    ├── experience-architecture.md # Stage 2 workflow
    └── creative-engineering.md   # Stage 3 workflow
```

## Quality Bar

Before calling work complete, the skill verifies:

- The concept is specific to this brand and not interchangeable with a template
- The first viewport establishes identity and communicates the offer
- The page has a coherent narrative and clear information hierarchy
- Typography, composition, imagery, color, and spacing feel art-directed
- Motion supports meaning and does not obstruct content or navigation
- Primary actions are visible and functional
- The experience works on small screens and with reduced motion
- Content is accurate; no invented metrics, testimonials, clients, or capabilities
- Existing functionality has not been accidentally broken
- The rendered result has been inspected, not merely compiled

## Requirements

- An agent that supports skill loading (markdown-based skills with reference/template/workflow structure)
- For implementation: a web project repository (React, Vue, Next.js, Astro, etc.)
- Browser/screenshot tools for rendered QA (recommended)

## License

MIT — Free to use, modify, and distribute.