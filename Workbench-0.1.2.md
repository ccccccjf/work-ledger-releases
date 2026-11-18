- 修复「检查更新」报 `You must specify the URL of the appcast as the SUFeedURL key`：
  Sparkle 的代理方法名写错了（应为 `feedURLString(for:)`），导致应用始终拿不到更新源
- 更新源同时写进 Info.plist 的 `SUFeedURL`，双保险
