# Spec Workflow Skill 使用说明

作者：fqs

这是一个用于真实后端项目的需求澄清与 Spec 编制 Skill。

## 产物

每个需求固定生成：

```text
spec.md
design.md
tasks.md
evidence.md
```

## 核心规则

```text
代码确认当前实现
用户确认目标行为
Agent 负责写文档
按“需求→设计→任务→验证计划”分阶段确认；每阶段集中提出已知问题
Evidence 在开发前只写验证计划
```

## 推荐安装目录

可放入 Agent 支持的 Skills 目录，例如：

```text
.skills/spec-workflow/
```

最终结构：

```text
spec-workflow/
├── SKILL.md
└── references/
    ├── spec-template.md
    ├── design-template.md
    ├── tasks-template.md
    └── evidence-template.md
```

不同 Agent 的 Skill 加载目录可能不同，但 `SKILL.md` 内容本身不依赖特定模型。
