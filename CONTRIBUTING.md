# Contributing

感谢你对 `Architect Fullstack Skill` 的关注。

这个仓库欢迎贡献，但建议先理解它的核心目标：

- 让 AI 更像“架构师 + 核心开发 + 工程负责人”工作
- 提供可维护的 `core + adapter + rules + workflow + examples + rendered packs` 结构
- 保持工程化、可演进、可复用，而不是堆积零散 prompt

---

## 贡献方向

欢迎以下类型的贡献：

### 1. 规则优化
例如：
- Go 后端规则增强
- API 设计规则增强
- 数据库规则增强
- Review / Release 规则增强
- Web / 小程序 / App 专项规则增强

### 2. 工作流优化
例如：
- 更清晰的架构工作流
- 更强的 review 清单
- 更好的任务模板

### 3. 成品版改进
例如：
- Claude / Cursor 适配更合理
- 专项 skill 的表达更准确
- 结构更清晰、可直接复制使用

### 4. 示例补充
例如：
- 更多任务模板
- 更多使用案例
- 更好的新手入口说明

---

## 不建议提交的内容

以下内容通常不建议直接合入：

- 强绑定个人项目的私有规则
- 企业内部流程、内部目录结构、内部命名规范
- 仅适用于单一业务系统的特殊 prompt
- 过于平台绑定、无法迁移的实现
- 大量重复已有内容、但没有结构价值的补充

这个仓库更偏“公共 Skill 基础设施”，而不是某个项目的私有规则库。

---

## 贡献原则

请尽量遵循以下原则：

- 保持结构清晰
- 优先增强已有层，而不是随意新增重复文件
- 能放 `core/` 就不要放进 `packs_rendered/`
- 工具差异优先放 `adapters/`
- 工程规则优先放 `rules/`
- 工作方法优先放 `workflow/`
- 高频使用案例优先放 `examples/`
- `packs_rendered/` 更像最终消费层，不应成为主维护源

---

## 推荐修改顺序

如果你要改动这个仓库，推荐优先级：

1. `core/`
2. `adapters/`
3. `rules/`
4. `workflow/`
5. `examples/`
6. `packs_rendered/`

也就是说：
- 先改源规则
- 再改最终成品版

---

## 提交建议

建议提交尽量小而清晰，例如：

- `docs: refine API design skill wording`
- `feat: add mini program task examples`
- `refactor: improve claude adapter structure`
- `docs: add release checklist guidance`

避免：
- 一次混入很多无关改动
- 同时重写多个层级而没有清晰理由

---

## Pull Request 建议说明

建议在 PR 中至少说明：

- 这次改动解决什么问题
- 影响哪些目录
- 为什么应该放在这个层级
- 是否同步更新了 `packs_rendered/`
- 是否影响现有使用方式

---

## 适合先提 Issue 的情况

建议在这些情况下先提 Issue 讨论：

- 想新增一个全新大类 skill
- 想改变目录结构
- 想改 `core/` 的基本定位
- 想加入强平台绑定规则
- 想加入大量行业专属内容

---

## 最后

如果一个改动让这套 Skill：
- 更清晰
- 更通用
- 更像真正的工程协作系统

那通常就是一个好改动。
