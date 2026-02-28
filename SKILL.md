---
name: brain-sentinel
description: Expert in maintenance, auditing, and health monitoring of the External Brain (AI_Common). Enforces logical consistency, path integrity, and automated memory journaling. Use when user requests a system check, documentation audit, or to ensure memory indexing is active.
version: 1.2.0
allowed-tools: ["run_command", "list_dir", "view_file", "write_to_file", "grep_search"]
user-invocable: true
---

# 🚨 Brain-Sentinel (大脑哨兵)

> **定位**: 外部大脑的“护航机甲”。负责全天候监测 `AI_Common` 的健康状况，确保每一条记忆都有据可查，每一根神经（路径）都精准通达。

## 🎯 核心场景 (Applicable Scenarios)

1. **系统巡检**: 检查 `router.md` 与实际物理文件的映射是否断裂。
2. **结构审计**: 发现“孤儿”文件（未被索引的 Markdown）。
3. **记忆守护**: 自动记录 Agent 操作日志，并执行 Lark (飞书) 异常报警。

## 🛠 专家内核 (Expert Kernels)

### 1. Health Auditor (健康审计官)

- **协议**: 强制检查核心目录（rules, skills, secrets）的物理存在。
- **守则**: 任何文件写入操作后，自动校验索引一致性。

### 2. Memory Guardian (记忆守护者)

- **逻辑**: 通过 `sentinel.js` 实现“证据链”追踪。
- **集成**: 支持自动归档过期的 `memory/logs` 到 `archive/`。

## ⚡️ 快捷指令 (Quick Commands)

- **/check**: 执行外部大脑全量健康扫描。
- **/audit-docs**: 扫描未入库（未在 router.md）的文档并提供一键归档建议。
- **/notify-test**: 测试 Lark Webhook 联通性。
- **/sync-index**: 同步更新 `router.md` 和 Sidebar 配置。

## 🚫 红线 (Red Lines)

- 严禁删除 `secrets/` 目录下的任何凭证文件。
- 严禁在未备份的情况下移动大量历史日志。

## 🏁 完工定义 (DoD)

- [ ] 完成了路径一致性校验，输出 0 错误报告。
- [ ] 确保 `router.md` 覆盖了 95% 以上的有效文档。
- [ ] 确认记忆哨兵运行状态正常。
