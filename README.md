# 个人工作台 · 发布通道（GitHub）

> 本仓库只存放安装包与更新源，不含源码。**只保留最新一个版本**，旧版本不再提供下载。

## 最新版本

| 项 | 值 |
|---|---|
| 版本 | **v0.1.13** |
| build | 202611262220 |
| 发布日期 | 2026-11-26 |
| 安装包 | [`Workbench-0.1.13.dmg`](https://raw.githubusercontent.com/ccccccjf/work-ledger-releases/main/Workbench-0.1.13.dmg)（约 2 MB） |
| 更新源 | `https://raw.githubusercontent.com/ccccccjf/work-ledger-releases/main/appcast.xml` |

### 本次更新内容

- 更新源改为双通道：Gitee（国内可达，优先）与 GitHub raw（备用），检查时依次尝试，
  哪个先通就用哪个，下载也走同一源，避免「查得到、装不上」
- 发布脚本 `publish.sh` 一次把安装包与 appcast 推到两个仓库，两边都只保留最新版本
- 修复 Gitee 的 raw 会 302 跳转的问题（应用侧自动跟随，无需额外处理）

---

## 安装

1. 下载上面的 `Workbench-0.1.13.dmg`
2. 打开 dmg，把「个人工作台」拖进「应用程序」
3. 首次打开若提示「无法验证开发者」：右键点应用 → 打开（应用未做 Apple 公证）

## 更新

已装旧版本的不用重新下载：

- 应用内：设置 → 版本与更新 → 检查更新
- 或点左下角的更新按钮

应用会依次尝试 Gitee 与 GitHub 两个源，哪个先通就用哪个下载并校验安装。
