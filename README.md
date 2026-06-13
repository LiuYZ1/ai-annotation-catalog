# AI 标注项目目录

> 所有标注仓库按此索引管理，统一命名规范、Topic 标签和分支策略。

## 命名规范

- 分支：`master` 保持原始代码不动
- 每个模型新建独立分支：`qwen-<任务名>` / `claude-<任务名>`
- Topics: `ai-annotation` `devops` `java` `level-1` `source-<原作者>`

## 仓库清单

| 编号 | 仓库 | 来源 | star | 代码量 | 领域 | qwen 分支 | claude 分支 | 状态 |
|------|------|------|------|--------|------|-----------|-------------|------|
| 01 | [alex-backend-1](https://github.com/LiuYZ1/alex-backend-1) | [Biexei](https://github.com/Biexei/alex-backend) | 82 | - | 接口测试 | [qwen-nested-dependency](https://github.com/LiuYZ1/alex-backend-1/tree/qwen-nested-dependency) | [claude-nested-dependency](https://github.com/LiuYZ1/alex-backend-1/tree/claude-nested-dependency) | 完成 |
| 02 | [dockerfile-maven](https://github.com/LiuYZ1/dockerfile-maven) | [spotify](https://github.com/spotify/dockerfile-maven) | 2738 | 257KB | Docker构建 | - | - | 待标注 |
| 03 | [docker-unittests](https://github.com/LiuYZ1/docker-unittests) | [dgroup](https://github.com/dgroup/docker-unittests) | 35 | 2.2MB | CI镜像测试 | - | - | 待标注 |
| 04 | [configuration-as-code-plugin](https://github.com/LiuYZ1/configuration-as-code-plugin) | [jenkinsci](https://github.com/jenkinsci/configuration-as-code-plugin) | 2789 | 6.4MB | Jenkins配置 | - | - | 待标注 |
| 05 | [docker-java](https://github.com/LiuYZ1/docker-java) | [docker-java](https://github.com/docker-java/docker-java) | 3186 | 6.2MB | Docker API | - | - | 待标注 |

## 标注统计

| 指标 | 数量 |
|------|------|
| 总项目数 | 5 |
| 已完成 | 1 |
| 待标注 | 4 |
| 涉及模型 | qwen3.7-max, claude-opus-4-8 |

## 快速筛选

在 [GitHub 仓库列表](https://github.com/LiuYZ1?tab=repositories) 搜索：
- `ai-annotation` — 所有标注项目
- `devops` — DevOps 领域
- `java` — Java 项目
- `level-1` — Level 1 标注
