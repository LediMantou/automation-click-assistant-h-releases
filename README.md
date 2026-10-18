# 自动化点击助手H 更新仓库

**状态：仅发布准备，尚未公开发布。**

本仓库仅用于自动化点击助手H，独立于 T 的发布仓库。当前没有 App、DMG、ZIP、正式 Release 或公开 appcast。

## 已准备的更新身份

- 产品：自动化点击助手H
- 版本起点：1.0.0 / build 1
- Bundle ID：`com.ledimantou.BrowserClickAssistant.H`
- 计划 Feed：`https://raw.githubusercontent.com/LediMantou/automation-click-assistant-h-releases/main/appcast.xml`
- Sparkle Ed25519 公钥：`OnlG1hf41+2FMS/dKYA+3+IGqzfDlKtZRu5YSZlJVGo=`
- Feed 与更新包必须分别签名，使用 HTTPS；不允许回退到 T 更新源。
- 签名私钥只保留在发布者本机的独立 Keychain 账户，不进入此仓库。

## 上线门禁

新候选需先完成用户真人启动、原设备授权和退出重开验收。只有用户另行批准正式上线后，才可创建 Release、上传安装包并部署已签名 appcast。当前计划 Feed 尚未部署，URL 不代表更新渠道已经上线。

本仓库不包含产品源码；产品源码继续在 `LediMantou/automation-click-assistant` 的 H 开发分支管理。
