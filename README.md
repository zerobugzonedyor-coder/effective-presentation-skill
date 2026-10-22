# effective-presentation

High-quality Agent / Pi skills for creating PPT and presentation decks that are **not boring** and drive **deep understanding + action**.

## Skills included

### 1. effective-presentation (通用版)
Research-backed principles from Nancy Duarte, PLOS Ten Simple Rules, Assertion-Evidence method.

### 2. mine-site-electricity-presentation (施工用电专题版)
针对**矿山工业场地房建项目施工用电规范解读与现场检查要点**的高度适配 skill。
- 严格聚焦“用电”主线
- 固定 4章12节结构
- 内置断言式标题库 + 检查表模板
- 强制 Ghost-deck 工作流

## Install in Pi

```bash
# 安装整个仓库（两个 skill 都会被发现）
pi install git:github.com/zerobugzonedyor-coder/effective-presentation-skill

# 或者只克隆后放到 skills 目录
# .pi/skills/ 或 ~/.pi/agent/skills/
```

安装后执行 `/reload`。

## Repository Structure

```
effective-presentation-skill/
├── SKILL.md                              # 通用 effective-presentation
├── references/                           # 通用参考资料
│   ├── ten-simple-rules.md
│   ├── action-titles.md
│   └── story-structures.md
└── mine-site-electricity-presentation/   # 施工用电专题 skill
    ├── SKILL.md
    └── references/
        ├── content-outline.md
        ├── action-titles-bank.md
        └── check-table-template.md
```

## Core Principles (both skills)

1. One idea per slide
2. Action titles (title = conclusion sentence)
3. Match density to context (live vs read-alone)
4. Minimize cognitive load
5. Story structure first, slides last

Measure of success: audience can restate the core message and knows the next action.

## License

MIT. Feel free to fork, improve, and share.
