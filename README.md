# 快享盒 Android 更新

本仓库只提供快享盒 Android 客户端的 APK、版本说明和机器可读更新清单。应用源码保留于私有仓库。

## 下载

在 [最新版本](https://github.com/code-mm/android-app-kxh-releases/releases/latest) 下载 APK 后安装。支持 Android 6.0（API 23）及以上。

## 更新方式

v1.1.1 起，每次打开客户端都会异步检查本仓库的正式版本。有新版本时显示说明，选择“下载安装”后下载并校验包名、版本、大小、SHA-256 和签名，再交由 Android 系统确认安装。也可在发现页选择“检查更新”。

旧 v1.0.0 尚无更新检查功能，需要先手动覆盖安装一次 v1.1.1；后续版本即可通过应用内提示更新。覆盖安装会保留应用数据。首次安装更新时，Android 可能要求允许快享盒安装此来源的应用。

无网络或 GitHub 暂不可用时，局域网共享功能仍可正常使用。

## 安装包身份

- 包名：`com.ms.kuaixianghe.android`
- 签名证书 SHA-256：`1fe7d30d196f843ede98cdeef734f600cffb0fb0fe8d38e3b541aae47b7e8197`
- 每个版本的 `update.json` 提供准确版本码、APK 文件名、字节数和 SHA-256。

请只安装本仓库正式 Release 中的 APK。测试包、签名私钥、凭据及源码均不在本仓库发布。
