# 🧭 TOProadmap

A [Claude](https://claude.ai) skill that turns **"I want to learn or do X"** into a detailed, realistic, stage-by-stage roadmap.

## What you get

Every roadmap follows the same structure:

1. **Snapshot**: goal, assumptions, duration, final outcome
2. **The big picture**: 4 to 6 stages with time estimates
3. **Stage-by-stage plan**: objective, what to learn, resources, hands-on project, milestone check, common mistakes
4. **First 7 days**: a concrete start for today
5. **Tracking**: how to measure progress and recover when behind
6. **After the roadmap**: what comes next

See [examples/example-roadmap.md](examples/example-roadmap.md) for a sample.

## Install

### Claude app
1. Download [`dist/toproadmap.skill`](dist/toproadmap.skill).
2. Open **Settings → Capabilities → Skills** and choose **Upload skill**.
3. Turn it on.

> Skills need code execution and file creation enabled. Menu names may change over time.

### Claude Code
```bash
git clone https://github.com/dalil2005/toproadmap ~/.claude/skills/toproadmap
```
For a single project, clone into `.claude/skills/toproadmap` inside it. Restart Claude Code afterwards.

## Use it

Just ask. No command needed:

- "I want to learn Python from zero. I have 6 hours a week."
- "Give me a roadmap to become a UX designer in 8 months."
- "How do I start running and finish a 10K?"
- "TOProadmap: launch an online store with a small budget."

## Customize

`SKILL.md` is plain Markdown. Edit the structure, tone, or rules to fit how you like your plans.

## Website

The landing page lives in [`docs/`](docs/). To host it free: **Settings → Pages → Deploy from a branch → `main` / `/docs`**.

## Repo layout

```
SKILL.md        the skill itself
dist/           ready-to-upload toproadmap.skill
docs/           landing page (GitHub Pages)
examples/       sample output
```

## License

[MIT](LICENSE)
