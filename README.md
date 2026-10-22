# effective-presentation

High-quality Agent / Pi skill for creating PPT and presentation decks that are **not boring** and drive **deep understanding + action**.

Based on:
- Nancy Duarte (*Slide:ology*, *Resonate*, density spectrum)
- PLOS Computational Biology *Ten simple rules for effective presentation slides*
- Assertion-Evidence research (Penn State / Michael Alley)
- Guy Kawasaki 10/20/30 rule and related best practices

## Install in Pi

```bash
# From git (recommended)
pi install git:github.com/zerobugzonedyor-coder/effective-presentation-skill

# Or clone and place in project skills
# .pi/skills/effective-presentation/ or ~/.pi/agent/skills/effective-presentation/
```

After install, reload Pi (`/reload`) or restart. Then invoke with natural language (e.g. "use the effective presentation skill") or explicit skill commands depending on your Pi setup.

## Structure

```
effective-presentation-skill/
├── SKILL.md                  # Main instructions (frontmatter + principles + workflow)
└── references/
    ├── ten-simple-rules.md   # PLOS + Duarte density spectrum
    ├── action-titles.md      # Assertion-Evidence + ghost-deck test
    └── story-structures.md   # SCQA, Hero’s Journey, checklists
```

## Core Principles

1. One idea per slide
2. Action titles (title = conclusion sentence)
3. Match density to context (live vs read-alone)
4. Minimize cognitive load
5. Story structure first, slides last

Measure of success: audience can restate the core message and knows the next action.

## License

MIT. Feel free to fork, improve, and share.
