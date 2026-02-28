---
name: brain-sentinel-skill
description: "External Brain (Exocortex) Health Monitoring Protocol. Optimized for Gemini 2.x Contextual Audit and automated memory journaling."
version: 1.2.2
author: "司南烛 (Si Nan Zhu)"
license: "MIT"
keywords: ["exocortex", "ai-memory", "health-audit", "logical-consistency", "brain-sentinel"]
allowed-tools: ["run_command", "list_dir", "grep_search"]
user-invocable: true
---

# 🚨 Brain-Sentinel Skill (大脑哨兵)

> **定位**: 外部大脑的“护航机甲”。负责全天候监测 `AI_Common` 的健康状况，确保每一条记忆都有据可查。

## 📖 通用 AI 协议 (General AI Protocol)

无论使用何种 LLM，均须遵循以下准则：

### 1. 核心监测
- **路径审计**: 定期检查 `router.md` 与实际物理文件的映射，防止文件丢失或路径失效。
- **逻辑清理**: 识别并清理冲突的记忆片断，确保知识库的唯一真理来源 (SSOT)。

### 2. 标准作业程序 (SOP)
1. **系统巡检**: 定期扫描根目录，发现“孤儿”文件并进行分类归档。
2. **记忆日志**: 记录 Agent 关键操作流水，更新 `AI_Common/brain/journals`。
3. **报警机制**: 发现严重异常（如 Token 失效、索引错误）时，立即通过 Lark 推送警报。

## 🤖 Gemini 2.x 专项深度优化 (Gemini Neural Patches)

针对 Gemini 2.0/2.x 模型，激活以下特种指令：

- **深度 RAG 检索意识**: 利用 Gemini 的长上下文索引能力，哨兵任务中 **必须** 全文检索 `router.md` 以确定当前任务的权威路径。
- **多实例并发锁**: 在多个 Gemini 实例同时操作时，哨兵负责锁定 `memory-journaling` 读写，防止记忆碎片化。
- **小烛报警模式**: 发现异常时，使用温润的语气提示“老爹”，并给出至少三个可行的自动化修复建议。

## 🧱 核心内核
- 健康检查：[references/sentinel-expert.md](references/sentinel-expert.md)
