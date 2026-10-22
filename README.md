# effective-presentation

High-quality Agent / Pi skills for creating PPT and presentation decks that are **not boring** and drive **deep understanding + action**.

## Skills included

### 1. effective-presentation (通用版)
Research-backed principles from Nancy Duarte, PLOS Ten Simple Rules, Assertion-Evidence method.

### 2. mine-site-electricity-presentation (施工用电专题版 · 已强化证据链)
针对**矿山工业场地房建项目施工用电规范解读与现场检查要点**的高度适配 skill。

**核心升级（针对安全关键领域）：**
- 五条硬性规则：证据必须、禁止编造条款、信息四分类、检查可复现、输出前审查
- 单一事实来源（technical-requirements.md）：每条结论有 ID、核验状态、适用条件
- 规范适用性判定表
- 检查表升级为可复现场检查模板
- 所有技术结论默认标注「待核验」，防止未核实内容被包装成确定结论

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
        ├── technical-requirements.md     # 单一事实来源（P0）
        ├── applicability-matrix.md       # 规范适用性判定
        ├── content-outline.md
        ├── action-titles-bank.md
        └── check-table-template.md
```

## Core Principles

**通用呈现原则**
1. One idea per slide
2. Action titles (title = conclusion sentence)
3. Match density to context
4. Minimize cognitive load
5. Story structure first, slides last

**施工用电额外硬规则**
1. 技术结论必须有证据，未核验必须标注
2. 不得编造规范条款号
3. 区分：规范明确要求 / 适用性判断 / 风险提示 / 管理建议
4. 检查必须可复现
5. 输出前必须专业审查

Measure of success: audience can restate the core message, knows the next action, and is not misled by unverified claims.

## License

MIT. Feel free to fork, improve, and share.
