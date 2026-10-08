# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Added
- 待补充...

### Changed
- 待补充...

### Fixed
- 待补充...

---

## [1.0.0] - 2026-10-08

### Added
- **五大核心功能**
  - 📦 项目归档（Project Archive）— 项目完成后生成结构化归档文档
  - 🔍 知识库检索（Knowledge Retrieval）— 跨项目经验搜索
  - 🧹 记忆整理（Memory Tidy）— 去重、合并、分类优化
  - 📝 偏好复盘（Preference Review）— 从历史项目中提炼稳定偏好
  - 📊 状态概览（Status Dashboard）— 记忆统计与健康度评估
- **三大辅助功能**
  - ❓ 帮助信息（Help）— 使用说明与命令速查
  - 🏥 健康检查（Health Check）— 记忆系统完整性检测
  - ⚙️ 配置管理（Config Management）— 对话中调节闸门配置
- **六级闸门控制系统**（G1 Trigger → G6 Safety）
  - 触发闸门 / 意图闸门 / 质量闸门 / 流程闸门 / 写入闸门 / 安全闸门
  - 每道闸门可独立调节严格程度
  - 支持三种快速预设：严格模式 / 标准模式 / 宽松模式
- **三级灵活度原则**
  - 🔴 刚性规则（Must）— 安全底线，不可违反
  - 🟡 推荐流程（Should）— 建议遵循，合理可调整
  - 🟢 可选建议（May）— 仅供参考，自由发挥
- **跨项目知识库**（4 分类）
  - `tech-stack.md` — 技术栈经验
  - `pitfalls.md` — 踩坑记录
  - `best-practices.md` — 最佳实践
  - `patterns.md` — 架构模式与方案
- **安全策略**
  - 写入必确认
  - 删除必二次确认
  - 批量操作必备份
- **完整的文档体系**
  - README（中文使用说明）
  - 归档文档模板
  - 闸门配置文件

---

## 版本说明

### 版本号规则

本项目遵循 **语义化版本（Semantic Versioning）**：

```
MAJOR.MINOR.PATCH

MAJOR  — 不兼容的 API 变更（大版本重构）
MINOR  — 新增功能（向下兼容）
PATCH  — Bug 修复和小优化（向下兼容）
```

### 变更类型

| 类型 | 说明 |
|---|---|
| `Added` | 新增功能 |
| `Changed` | 现有功能的变更 |
| `Deprecated` | 即将废弃的功能 |
| `Removed` | 已移除的功能 |
| `Fixed` | Bug 修复 |
| `Security` | 安全相关修复 |
