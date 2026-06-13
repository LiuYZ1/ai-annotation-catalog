# AI 标注项目目录

> 所有标注仓库按此索引管理，统一命名规范、Topic 标签和分支策略。

## 命名规范

```
ai-anno-<项目名>-<序号>
```

- 分支：`master` 保持原始代码不动
- 每个模型新建独立分支：`qwen-<任务名>` / `claude-<任务名>`

## 仓库清单

| 编号 | 仓库 | 来源 | qwen 分支 | claude 分支 | 状态 | 日期 |
|------|------|------|-----------|-------------|------|------|
| 01 | [alex-backend-1](https://github.com/LiuYZ1/alex-backend-1) | [Biexei/alex-backend](https://github.com/Biexei/alex-backend) | [qwen-nested-dependency](https://github.com/LiuYZ1/alex-backend-1/tree/qwen-nested-dependency) | [claude-nested-dependency](https://github.com/LiuYZ1/alex-backend-1/tree/claude-nested-dependency) | 完成 | 2026-06-12 |

## 标注统计

| 指标 | 数量 |
|------|------|
| 总项目数 | 1 |
| 已完成 | 1 |
| 进行中 | 0 |
| 涉及模型 | qwen3.7-max, claude-opus-4-6 |

## 快速筛选

在 [GitHub 仓库列表](https://github.com/LiuYZ1?tab=repositories) 搜索：
- `ai-annotation` — 所有标注项目
- `level-1` — Level 1 标注
- `model-qwen` — qwen 模型评测
- `model-claude` — claude 模型评测
- `source-biexei` — 来源为 Biexei 的项目
