## H 当前正式版本：1.1.0 / build 2

原设备卡密自助续期已正式发布。产品提交 `48981e1268feca264699f5f883390a52fa84f838`，正式 refs `release/h/1.1` / `h/v1.1.0`。
[Release](https://github.com/LediMantou/automation-click-assistant-h-releases/releases/tag/v1.1.0) · [DMG](https://github.com/LediMantou/automation-click-assistant-h-releases/releases/download/v1.1.0/automation-click-assistant-h-mac-1.1.0.dmg) · [独立签名 Feed](https://raw.githubusercontent.com/LediMantou/automation-click-assistant-h-releases/main/appcast.xml)。
原两策略、100 有效局、Bundle ID、Keychain 身份及独立配置/Profile/更新通道不变。
本轮仅发行元数据重封装/重签，未重新编译功能代码；正式 App 不与验收候选同字节。
真人续期候选已由乐迪确认；真实跨版本 Sparkle 安装仍 NOT_RUN。AWS、发卡、真实续期和 PP 本轮均未操作。
当前维护入口为 `文档/发布基线/H-1.1.0/`。下方 1.0.0 及更早记录完整保留为历史，不代表本次重复验收。

---

# 自动化点击助手H 1.0.0 / build 1

**正式版本已发布。** H 是独立产品，不是 T 的更新版本。

## 下载与更新

- [GitHub 正式 Release](https://github.com/LediMantou/automation-click-assistant-h-releases/releases/tag/v1.0.0)
- [自动化点击助手H-1.0.0.dmg](https://github.com/LediMantou/automation-click-assistant-h-releases/releases/download/v1.0.0/automation-click-assistant-h-mac-1.0.0.dmg)
- [H 独立 Sparkle Feed](https://raw.githubusercontent.com/LediMantou/automation-click-assistant-h-releases/main/appcast.xml)
- DMG：6241966 bytes；SHA256：`30c5979d47f597748fc8f0f2a87bfc18c74d4998db8eee93984dc9001289243a`。
- Bundle ID：`com.ledimantou.BrowserClickAssistant.H`；Universal arm64 + x86_64，macOS 13 及以上。

## 产品与授权

采用新版 SwiftUI 界面，仅闲模式、庄模式。每周期固定最多100个有效局；和局、未参与观察不计数，原安全保护可提前停止。八档倍投 n×2+n、动态筹码、PP selected、原生鼠标和全部安全停止机制保留。

需要六位启动密码与有效在线授权。T/H 共用现有 AWS 卡密授权系统，同一 Mac 可复用原设备身份和设备名额；必要时由本人完成 macOS 原生 Keychain 重新授权，不重新激活来替代原身份。正常卡密到期属于授权生命周期。

首次安装为独立空白配置，台子、Chrome Profile、日志和普通 Telegram 状态独立，不复制或覆盖 T。H 有独立签名更新通道，不会更新成 T。

## 安装与验证边界

将 DMG 内的“自动化点击助手H.app”拖入 Applications，由用户本人打开。普通 Ad Hoc，无 Apple Developer ID 或 Apple 公证；必要时按 [Apple 官方原生安全确认流程](https://support.apple.com/zh-cn/102445) 操作，不以清除 quarantine 或关闭 Gatekeeper 作为默认步骤。

正式包来自同一份真人启动/原设备授权验收母本；发布阶段未重编译或重签 App。100局边界已有定向自动化验证，不宣称真人跑满100局。H 是首发，没有更早 H 正式版，真实跨版本安装记录为 NOT_RUN。

## 源码记录

共同产品仓库 [automation-click-assistant](https://github.com/LediMantou/automation-click-assistant)；H 产品 commit `a1ec41f9f1aeab049c2f6457f1b6ccc7e90ebb09`，开发分支 `codex/h-1.0.0`、正式分支 `release/h/1.0`、产品 tag `h/v1.0.0`。本发布仓库的 Release/tag 是 `v1.0.0`，属于另一套版本记录。T 正式渠道保持不变。
