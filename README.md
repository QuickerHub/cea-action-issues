# cea-action-issues

CEA Quicker 生态的**公开 Issue 跟踪仓**。源码在私有仓库维护；此处仅收集需求、Bug 与讨论，便于溯源与协作。

## 使用方式

| 场景 | 做法 |
|------|------|
| 提需求 / 报 Bug | [New Issue](../../issues/new/choose) |
| Commit 引用 | `fix(scope): 描述 QuickerHub/cea-action-issues#N` |
| PR 自动关闭 | PR 描述写 `Fixes QuickerHub/cea-action-issues#N` |
| 同组织私有仓 | 私有 `quicker-workspace` 的 PR 也可关闭本仓 Issue |

## 标签（area）

| Label | 范围 |
|-------|------|
| `area:actions` | Quicker 动作、子程序（`.quicker/`） |
| `area:packages` | WPF/DLL 依赖包（`packages/`） |
| `area:clip` | 剪贴板（BetterClip / IntelliTools） |
| `area:qkrpc` | qkrpc / QuickerRpc 插件 |
| `area:userscripts` | 油猴脚本 |
| `area:tooling` | qkbuild、qkagent 等构建/发布工具 |
| `area:meta` | 跨领域、流程、文档 |

类型：`type:bug` · `type:feat` · `type:chore` · `type:idea`

## 私有源码

本仓**不含**应用源码。开发在私有 [quicker-workspace](https://github.com/QuickerHub/quicker-workspace) 进行（需授权访问）。

## 安全

公开 Issue 中请勿粘贴密钥、账号、客户数据或未脱敏的私有路径。实现细节放在私有仓 commit/PR，Issue 只写可公开复现的步骤与期望行为。

详细约定见 [CONTRIBUTING.md](CONTRIBUTING.md)。
