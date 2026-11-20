# TOProadmap

**Turn any ambition into a clear, actionable plan.**

TOProadmap is a Claude skill that transforms a learning goal, personal ambition, or practical objective into a structured, realistic, stage-by-stage roadmap.

Instead of vague advice or overwhelming lists of resources, it creates a clear path from where you are today to where you want to be.

<p align="center">
  <a href="https://dalil2005.github.io/TOProadmap/"><strong>Live Website</strong></a>
  &nbsp; · &nbsp;
  <a href="https://github.com/dalil2005/toproadmap"><strong>Source Code</strong></a>
  &nbsp; · &nbsp;
  <a href="LICENSE"><strong>MIT License</strong></a>
</p>

---

## What It Produces

Every roadmap is built around six essential components:

| Component | What it covers |
|---|---|
| **01 — Snapshot** | Your goal, starting assumptions, estimated duration, and expected outcome. |
| **02 — The Big Picture** | A complete overview divided into 4–6 progressive stages, each with a time estimate. |
| **03 — Stage-by-Stage Plan** | Learning objectives, essential topics, curated resources, practical projects, milestones, and common mistakes. |
| **04 — First 7 Days** | A practical first-week action plan so you can start immediately. |
| **05 — Progress Tracking** | Ways to measure progress, stay consistent, and get back on track when things fall behind. |
| **06 — What's Next** | Clear directions for continuing beyond the roadmap. |

**A roadmap should do more than tell you what to learn. It should show you what to do next.**

For a complete example, see [`examples/example-roadmap.md`](examples/example-roadmap.md).

---

## Installation

### Claude

1. Download [`dist/toproadmap.skill`](dist/toproadmap.skill) from this repository.
2. Open **Settings → Capabilities → Skills** in Claude.
3. Select **Upload skill** and choose the downloaded file.
4. Enable TOProadmap.

> Requirements: Code execution and file creation must be enabled. Settings and menu names may change between Claude versions.

### Claude Code

Clone the repository directly into your personal skills directory:

```bash
git clone https://github.com/dalil2005/toproadmap.git ~/.claude/skills/toproadmap
```

To install it for a single project instead, clone it into:

```text
.claude/skills/toproadmap
```

Restart Claude Code after installation.

---

## Getting Started

No special commands or complicated configuration required. Simply describe what you want to achieve.

For example:

**Learning a new skill**
```text
I want to learn Python from zero.
I can dedicate 6 hours per week.
```

**Building a career**
```text
Create a roadmap to become a UX designer
within 8 months.
```

**Personal development**
```text
I want to start running and eventually
complete my first 10K.
```

**Launching a project**
```text
TOProadmap: Help me launch an online store
with a small budget.
```

TOProadmap takes your objective and turns it into a structured plan you can actually follow.

---

## Customization

The skill is built around a simple, editable Markdown file.

Open `SKILL.md` to customize its instructions, roadmap structure, writing style, or planning rules.

Make it more concise, more detailed, more technical, or adapt it to your preferred way of learning and working.

---

## Project Structure

```text
toproadmap/
│
├── SKILL.md                  # Core skill instructions
│
├── dist/
│   └── toproadmap.skill      # Ready-to-install skill package
│
├── docs/                     # GitHub Pages landing page
│
├── examples/
│   └── example-roadmap.md    # Example generated roadmap
│
└── LICENSE                   # MIT License
```

---

## Website

The project landing page is available here:

**[dalil2005.github.io/TOProadmap](https://dalil2005.github.io/TOProadmap/)**

To deploy your own version using GitHub Pages:

1. Open your repository's **Settings**.
2. Navigate to **Pages**.
3. Select **Deploy from a branch**.
4. Choose `main` as the branch and `/docs` as the folder.
5. Save your settings.

---

## License

Distributed under the [MIT License](LICENSE).

Copyright (c) 2026 Kaddour Cherif Zakaria Dalil.

You are free to use, modify, distribute, and build upon this project under the terms of the license.

---

<p align="center">
  <strong>TOProadmap</strong>
  <br />
  <sub>Less guessing. More direction. Real progress.</sub>
  <br /><br />
  Created by <a href="https://github.com/dalil2005">Kaddour Cherif Zakaria Dalil</a>
</p>