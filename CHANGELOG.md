# GROW 官网更新记录

本文件记录项目阶段性变化。它不是代码提交历史的替代品，而是给人和 Codex 快速理解项目进度的简明记录。

## 记录格式

每条记录建议包含：

- 日期
- 类型
- 完成内容
- 影响范围
- 对应提交

类型参考：

- Setup：项目设置
- Docs：文档和项目记忆
- Feature：新功能
- Fix：问题修复
- Design：视觉或体验调整
- Deploy：部署相关

## 2026-05-17

### Docs：建立项目长期记忆文件

完成内容：

- 确认 AGENTS.md 作为项目背景、品牌规范和 Codex 协作规则文件
- 新增 ROADMAP.md，用于记录开发路线、模块进度和下一步任务
- 新增 DECISIONS.md，用于记录重要技术、设计和协作决策
- 新增 CHANGELOG.md，用于记录阶段性完成情况
- 在 AGENTS.md 中补充长期记忆文件使用规则

影响范围：

- 项目协作流程
- 两台 Mac 之间的上下文同步方式
- 新对话启动方式

对应提交：

- 待提交

### Setup：配置 GitHub 同步基础

完成内容：

- 本地项目已初始化为 Git 仓库
- 已连接 GitHub 远程仓库
- 已配置 SSH Key 访问
- AGENTS.md 已推送到 GitHub

影响范围：

- 本地项目
- GitHub 仓库
- 两台 Mac 的同步方式

对应提交：

- 99a0431 Add project context for Codex

## 当前项目状态

项目尚未开始实际代码开发。

当前已完成的是：

- 项目背景整理
- 品牌规范整理
- GitHub 同步配置
- 项目长期记忆体系建立

下一步建议：

```txt
请先阅读 AGENTS.md、ROADMAP.md、DECISIONS.md 和 CHANGELOG.md，然后帮我初始化 Next.js + Tailwind CSS 项目。
```
