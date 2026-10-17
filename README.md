# ProcessKeepAlive (PKA) — 问题反馈 / Feedback

> 这是 **ProcessKeepAlive（PKA）Xposed / LSPosed 保活模块**的专用反馈仓库。
> 源码保存在私有主仓库，不对外公开，但**问题反馈渠道完全公开**——欢迎在此提交 Bug 报告或功能建议。

## 下载模块 / Download

LSPosed 仓库搜 `ProcessKeepAlive`，或前往官方收录库：

**[https://github.com/Xposed-Modules-Repo/io.github.guys222.processkeepalive](https://github.com/Xposed-Modules-Repo/io.github.guys222.processkeepalive)**

## 怎么反馈 / How to report

| 类型 | 渠道 |
| --- | --- |
| Bug 报告、兼容性问题 | [Issues](https://github.com/Guys222/ProcessKeepAlive-Issues/issues) |
| 使用提问、玩法讨论 | [Discussions](https://github.com/Guys222/ProcessKeepAlive-Issues/discussions) |

### 提交 Issue 前请尽量附上 / Please include

1. **模块版本**（模块管理页可见，如 `3.4.4 / 4025`）
2. **ROM 与 Android 版本**（如 ColorOS 15 / Android 15；是否使用分身、双开、应用多开）
3. **LSPosed 版本与作用域**（模块对 System Framework + 目标应用是否勾选）
4. **问题现象**：期望行为 vs 实际行为，能否稳定复现
5. **日志**：优先导出模块内的诊断包（设置页 → 导出诊断信息），或贴 LSPosed 日志中与 `ProcessKeepAlive` / `PKA` 相关的片段

> 隐私提醒：诊断包只包含本模块运行所需信息，不含通讯录、短信等个人数据，但建议发送前先过一眼内容。

### Issues 模板 / Issue template

```
【现象】

【期望行为】

【环境】
- 模块版本：
- ROM / Android：
- LSPosed 版本：
- 是否分身 / 双开：

【复现步骤】

【日志 / 诊断包】
```

## 说明 / Notes

- 本仓库**不包含源码**，源码为私有维护；这里只用于跟踪问题与需求。
- Issues 的标签（`bug` / `enhancement` / `question`）由维护方整理，你只需把现象写清楚。
- 提交前请搜索是否已有相同 Issue，避免重复。

---

*This repository contains no source code. The main repository is private; this repo exists solely as a public place to report bugs and request features for the PKA module.*
