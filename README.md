# 个人工作台 · 发布通道

> 本仓库只存放安装包与更新源，不含源码。**只保留最新一个版本**，旧版本不再提供下载。

## 最新版本

| 项 | 值 |
|---|---|
| 版本 | **v0.1.6** |
| build | 202611231121 |
| 发布日期 | 2026-11-23 |
| 安装包 | [`Workbench-0.1.6.dmg`](https://raw.githubusercontent.com/ccccccjf/work-ledger-releases/main/Workbench-0.1.6.dmg)（约 2 MB） |
| 更新源 | `https://raw.githubusercontent.com/ccccccjf/work-ledger-releases/main/appcast.xml` |

### 本次更新内容

- 会议录音真正改为 m4a（MP4 / AAC 容器），不再产出 webm：
  此前只在界面文案上改了格式，录音容器仍是 WebKit 默认的 webm
- 录音容器按系统能力择优：`audio/mp4` → 不支持时回落 `audio/webm`，保存提示会写明实际格式
- 保存录音时不再由原生层默认按 webm 处理，扩展名以页面给出的文件名为准
- 会议页提示改为「录音存为 m4a（AAC），本地留存」

---

## 安装

1. 下载上面的 `Workbench-0.1.6.dmg`
2. 打开 dmg，把「个人工作台」拖进「应用程序」
3. 首次打开若提示「无法验证开发者」：右键点应用 → 打开（应用未做 Apple 公证）

## 更新

已装旧版本的不用重新下载：

- 应用内：设置 → 版本与更新 → 检查更新
- 或菜单栏：个人工作台 → 检查更新…

应用会自行下载、验签、替换并重启。更新源已内置，无需配置。

---

历史更新记录见 [CHANGELOG.md](CHANGELOG.md)。
