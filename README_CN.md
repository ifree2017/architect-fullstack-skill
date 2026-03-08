# Architect Fullstack Skill

一套面向架构师、Tech Lead 和全栈工程师的 AI 工程协作 Skill 系统。

`architect-fullstack-skill` 的目标，不是提供一条更长的 prompt，
而是提供一套更像真实工程系统的 AI Skill 结构。

它希望解决的问题是：

- AI 会回答，但不够像工程伙伴
- AI 能写代码，但缺少架构视角
- AI 能分析问题，但缺少落地和发布意识
- AI 能提出建议，但缺少 review 和风险控制能力

所以，这个仓库把 AI 能力按工程化方式拆成了多层：

- `core/`：共用核心人格与工程标准
- `adapters/`：面向 Claude / Cursor 的适配层
- `rules/`：专项规则层
- `workflow/`：工作流与评审清单
- `examples/`：任务模板示例
- `packs_rendered/`：可直接使用的成品 Skill

---

## 解决什么问题

这套 Skill 主要帮助 AI 更好地完成这些任务：

- 架构设计
- 后端工程实现
- API 设计
- 数据库设计与优化
- review 与重构
- 发布与回滚评估
- Web 前端协作
- 小程序协作
- App 客户端协作

换句话说，它的目标是让 AI 更像：

- 架构师
- 技术负责人
- 核心开发
- 评审者
- 发布负责人

---

## 仓库结构

- `core/`：沉淀通用核心能力
- `adapters/`：处理 Claude / Cursor 等工具差异
- `rules/`：沉淀工程专项规则
- `workflow/`：沉淀工作方法和执行流程
- `examples/`：沉淀高频任务模板
- `packs_rendered/`：提供开箱即用版本

---

## 如何开始

### 方式一：安装为 Claude/Cursor Skill（推荐）

```bash
# 克隆或复制仓库
git clone <仓库地址> architect-fullstack-skill
cd architect-fullstack-skill

# 运行安装脚本
chmod +x install.sh
./install.sh
```

选择安装位置：
- Claude: `~/.claude/skills/architect-fullstack-skill`
- Cursor: `~/.cursor/skills/architect-fullstack-skill`

安装后：
1. 重启 Claude/Cursor
2. 在 Settings → Skills 中加载 skill
3. 使用触发词激活：

| 触发词 | 说明 |
|--------|------|
| `@architect-fullstack` | 完整架构师技能 |
| `@go-backend` | Go 后端专项 |
| `@api-design` | API 设计专项 |
| `@web-frontend` | Web 前端专项 |
| `@miniprogram` | 小程序专项 |
| `@app-client` | App 协作专项 |
| `@review` | Code Review 专项 |
| `@release` | 发布评估专项 |

### 方式二：直接使用
如果你只是想快速上手，优先从这些文件开始：

- `packs_rendered/architect_fullstack_claude_skill.md`
- `packs_rendered/architect_fullstack_cursor_skill.md`

如果你只做专项任务，也可以直接使用：

- `packs_rendered/go_backend_engineering_skill.md`
- `packs_rendered/api_design_skill.md`
- `packs_rendered/web_frontend_skill.md`
- `packs_rendered/miniprogram_skill.md`
- `packs_rendered/app_client_collaboration_skill.md`
- `packs_rendered/engineering_review_skill.md`
- `packs_rendered/engineering_release_skill.md`

### 长期维护
如果你想持续演进这套 Skill，建议优先维护：

- `core/architect_fullstack_core.md`
- `adapters/claude_adapter.md`
- `adapters/cursor_adapter.md`
- `rules/`
- `workflow/`

---

## 适合谁

适合：

- 架构师
- Tech Lead
- 后端工程师
- 全栈工程师
- 高频使用 AI 工具参与真实项目的人

不太适合：

- 只想要一条极简 prompt 的用户
- 只关注某个单一框架的人
- 只想做简单代码补全、不关心工程协作的人

---

## 开源边界

这个公开版本只包含通用能力，不包含：

- 私有项目结构
- 企业内部规则
- 特定业务系统知识
- 项目私有坑位与历史经验

这样可以保证它更通用，也更适合公开发布。

---

## 一句话总结

`architect-fullstack-skill` 的目标不是让 AI 更会“回答”，
而是让 AI 更会“参与工程协作”。
