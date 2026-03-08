[English](README.md) | [中文说明](README_CN.md)

# Architect Fullstack Skill

A practical AI skill pack for architects, tech leads, and fullstack engineers.

This repository helps you make AI behave more like a real engineering partner instead of a generic chatbot.

It focuses on:
- architecture thinking
- Go backend engineering
- API design
- database design and optimization
- review and refactoring
- release and rollback awareness
- Web frontend
- mini program
- app client collaboration

---

## Why this exists

Most prompts are too generic.

They can answer questions, but they usually fail to behave like a real:
- architect
- core engineer
- reviewer
- release owner

This skill pack is designed to close that gap.

It gives you a reusable structure for making AI work with:
- clearer engineering judgment
- better architecture trade-off analysis
- stronger implementation guidance
- better review quality
- stronger release-risk awareness

---

## What makes it different

Instead of providing only one large prompt, this repository is organized as a layered system:

- `core/` for shared engineering mindset
- `adapters/` for Claude / Cursor specific behavior
- `rules/` for specialized engineering rules
- `workflow/` for execution process and review flow
- `examples/` for reusable task prompts
- `packs_rendered/` for ready-to-use final prompts

That means you can either:
- use it directly
- or maintain and evolve it like a real prompt engineering system

---

## Repository structure

```/dev/null/public_skill_tree.txt#L1-25
public_skill/
├── core/
│   └── architect_fullstack_core.md
├── adapters/
│   ├── claude_adapter.md
│   └── cursor_adapter.md
├── rules/
│   ├── go_backend_engineering_rules.md
│   ├── frontend_engineering_rules.md
│   ├── web_frontend_rules.md
│   ├── miniprogram_rules.md
│   ├── app_client_rules.md
│   ├── database_engineering_rules.md
│   ├── api_design_rules.md
│   └── deployment_release_rules.md
├── workflow/
│   ├── architecture_workflow.md
│   ├── review_checklist.md
│   └── task_prompt_templates.md
├── examples/
│   ├── web_task_examples.md
│   ├── miniprogram_task_examples.md
│   └── app_client_task_examples.md
├── packs_rendered/
│   ├── architect_fullstack_claude_skill.md
│   ├── architect_fullstack_cursor_skill.md
│   ├── go_backend_engineering_skill.md
│   ├── api_design_skill.md
│   ├── web_frontend_skill.md
│   ├── miniprogram_skill.md
│   ├── app_client_collaboration_skill.md
│   ├── engineering_review_skill.md
│   └── engineering_release_skill.md
```

---

## Quick start

### Option 1: Use ready-made skills directly

If you want the fastest path, start with files in `packs_rendered/`.

Recommended entry points:
- Claude: `packs_rendered/architect_fullstack_claude_skill.md`
- Cursor: `packs_rendered/architect_fullstack_cursor_skill.md`
- Backend engineering: `packs_rendered/go_backend_engineering_skill.md`
- API design: `packs_rendered/api_design_skill.md`
- Web frontend: `packs_rendered/web_frontend_skill.md`
- Mini program: `packs_rendered/miniprogram_skill.md`
- App collaboration: `packs_rendered/app_client_collaboration_skill.md`
- Review: `packs_rendered/engineering_review_skill.md`
- Release: `packs_rendered/engineering_release_skill.md`

### Option 2: Maintain the system yourself

If you want long-term maintainability, start from:
- `core/architect_fullstack_core.md`
- `adapters/claude_adapter.md`
- `adapters/cursor_adapter.md`
- `rules/`
- `workflow/`

---

## Recommended usage patterns

### For Claude
Use:
- `packs_rendered/architect_fullstack_claude_skill.md`

Best for:
- architecture design
- deep debugging
- trade-off analysis
- refactoring strategy
- high-risk review

### For Cursor
Use:
- `packs_rendered/architect_fullstack_cursor_skill.md`

Best for:
- implementation
- local refactoring
- editor-centric iteration
- current-module optimization

### For specialized tasks
Use the dedicated packs:
- Go backend: `go_backend_engineering_skill.md`
- API design: `api_design_skill.md`
- Web: `web_frontend_skill.md`
- Mini program: `miniprogram_skill.md`
- App client: `app_client_collaboration_skill.md`
- Review: `engineering_review_skill.md`
- Release: `engineering_release_skill.md`

---

## Who this is for

This repository is a strong fit if you are:
- an architect
- a tech lead
- a senior Go backend engineer
- a fullstack developer
- an AI power user who wants better engineering outputs

---

## Who this is not for

This repository is probably not a good fit if you want:
- a tiny one-line prompt
- beginner-level coding explanations only
- a framework-specific assistant only
- a project-specific internal rule set

This is a general public engineering skill pack, not a private company rule base.

---

## Public scope

This public release intentionally excludes:
- private project structure
- internal business rules
- company-specific engineering process
- project-specific pitfalls and private context

That keeps this repository reusable and safe for public release.

---

## Suggested release strategy

You can publish this repository in several ways:

### Open source repository
Best for:
- GitHub
- public collaboration
- issue / PR based evolution

### Prompt product / knowledge pack
Best for:
- Gumroad
- Notion
- blog download pack
- paid prompt bundle

### Internal team starter kit
Best for:
- adapting the public version into a company-internal prompt system

---

## Maintenance model

Recommended priority:

1. update `core/`
2. update `adapters/`
3. update `rules/` and `workflow/`
4. regenerate or revise `packs_rendered/`

In other words:
- maintain the source layers first
- treat `packs_rendered/` as the final consumable layer

---

## Version

Current version: `v1.0.0`

See also:
- `SKILL_MANIFEST.md`
- `CHANGELOG.md`
- `LICENSE`

---

## License

MIT
