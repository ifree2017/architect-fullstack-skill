# Architect Fullstack Skill

## Description

一个让 AI 以"架构师 + 全栈工程伙伴 + 发布风险控制者"方式工作的 Skill 包。

适用于：
- 架构师
- Tech Lead
- 全栈开发者
- 高阶 AI Coding 用户

核心能力：
- 架构设计
- Go 后端工程实现
- API 设计
- 数据库设计与优化
- Review 与重构
- 发布与回滚评估
- Web 前端
- 小程序
- App 客户端协作

## Usage

### Quick Start

直接使用 `packs_rendered/` 下的成品 prompt：

- **Claude**: `packs_rendered/architect_fullstack_claude_skill.md`
- **Cursor**: `packs_rendered/architect_fullstack_cursor_skill.md`
- **Go 后端**: `packs_rendered/go_backend_engineering_skill.md`
- **API 设计**: `packs_rendered/api_design_skill.md`
- **Web 前端**: `packs_rendered/web_frontend_skill.md`
- **小程序**: `packs_rendered/miniprogram_skill.md`
- **App 协作**: `packs_rendered/app_client_collaboration_skill.md`
- **Code Review**: `packs_rendered/engineering_review_skill.md`
- **发布评估**: `packs_rendered/engineering_release_skill.md`

### Installation

#### 方式一：一键安装脚本
```bash
cd public_skill
chmod +x install.sh
./install.sh
```

#### 方式二：手动安装
1. 克隆或复制此目录到：
   - Claude: `~/.claude/skills/architect-fullstack-skill`
   - Cursor: `.cursor/skills/architect-fullstack-skill`

2. 在 Claude/Cursor Settings → Skills 中加载此目录

3. 使用时直接复制对应 `packs_rendered/` 文件内容到你的 AI 工具

## Trigger Words

使用以下触发词激活 skill：

- `@architect-fullstack` - 激活完整架构师技能
- `@go-backend` - Go 后端专项
- `@api-design` - API 设计专项
- `@web-frontend` - Web 前端专项
- `@miniprogram` - 小程序专项
- `@app-client` - App 协作专项
- `@review` - Code Review 专项
- `@release` - 发布评估专项

## Files

```
public_skill/
├── core/                    # 核心工程思维
├── adapters/                # Claude/Cursor 适配层
├── rules/                   # 工程规则
├── workflow/                # 工作流
├── examples/                # 任务示例
└── packs_rendered/          # 成品 prompt（直接使用）
```

## Tool Support

- Claude
- Cursor
- 通用 System Prompt 场景

## Version

v1.0.0
