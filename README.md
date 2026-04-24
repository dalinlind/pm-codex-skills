# PM Codex Skills

面向产品经理工作的 Codex Skills 集合，适用于将产品想法、业务需求和评审材料转化为可交付的产品文档、原型、测试用例和数据分析方案。

这套 Skills 的目标是把零散需求快速转化为真实产品交付物，包括 PRD、HTML 原型、需求评审意见、测试用例、指标体系和数据看板方案。

## Skills

| Skill | 使用场景 | 主要输出 |
| --- | --- | --- |
| `pm-prd-writer` | 把想法、会议纪要、客户反馈、竞品功能整理成 PRD | 背景、目标、流程、功能清单、字段规则、权限、异常、验收标准 |
| `pm-prototype-builder` | 根据 PRD 或页面需求生成企业级高保真原型 | 单文件 HTML、业务样例数据、基础交互、空态/异常态 |
| `pm-reviewer` | 从多角色角度评审 PRD、原型或方案 | 风险清单、分角色评审意见、修改建议、待确认问题 |
| `pm-testcase-writer` | 根据 PRD 生成测试用例和验收标准 | 功能用例、权限用例、边界用例、AI 用例、回归清单 |
| `pm-data-analyst` | 设计指标体系、埋点方案、漏斗和看板 | 指标口径、维度拆解、埋点事件、看板结构、行动建议 |

## Directory Structure

```text
.
├── AGENTS.md
└── .agents/
    └── skills/
        ├── pm-prd-writer/
        │   └── SKILL.md
        ├── pm-prototype-builder/
        │   └── SKILL.md
        ├── pm-reviewer/
        │   └── SKILL.md
        ├── pm-testcase-writer/
        │   └── SKILL.md
        └── pm-data-analyst/
            └── SKILL.md
```

## How to Use

用 Codex App 打开这个项目目录，之后可以在任务里直接点名调用 Skill。

### 写 PRD

```text
使用 pm-prd-writer skill，把下面需求写成 PRD：

【粘贴需求】
```

### 生成原型

```text
使用 pm-prototype-builder skill，根据下面 PRD 生成一个单文件 HTML 高保真原型：

【粘贴 PRD】
```

### 评审需求

```text
使用 pm-reviewer skill，从研发、测试、设计、运营、销售、客户成功角度审查下面这份 PRD：

【粘贴 PRD】
```

### 生成测试用例

```text
使用 pm-testcase-writer skill，根据下面 PRD 生成测试用例和上线验收标准：

【粘贴 PRD】
```

### 设计数据分析方案

```text
使用 pm-data-analyst skill，为下面业务问题设计指标体系、埋点方案和数据看板：

【描述业务问题】
```

## Recommended Workflow

```text
pm-prd-writer
→ pm-reviewer
→ pm-prototype-builder
→ pm-testcase-writer
→ pm-data-analyst
```

## Notes

- `AGENTS.md` 是项目级总规则。
- 每个 Skill 目录下的 `SKILL.md` 是具体能力说明。
- 输出默认使用中文。
- 原型默认生成单文件 HTML。
- UI 风格默认企业级、极简、现代、浅色科技感。

## License

MIT
