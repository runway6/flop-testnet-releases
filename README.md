# FlopNetwork Releases

本仓库用于分发 **FlopNetwork** 的 Windows 加密自动更新版本（无授权码无法解密业务代码）。

## 📥 一键下载（首次安装）

- **Windows 引导包永久直链**：👉 [**点击下载 FlopNetwork-Starter-Win.zip**](https://github.com/runway6/flop-testnet-releases/releases/latest/download/FlopNetwork-Starter-Win.zip)
- **查看最新发行说明**：https://github.com/runway6/flop-testnet-releases/releases/latest

## 🚀 3 步快速启动

1. 下载上方 `FlopNetwork-Starter-Win.zip` 并**完整解压**到本地文件夹；
2. 确保电脑已安装 Python 3.10+ 且网络可访问 GitHub（如使用 Clash 等系统代理会自动兼容）；
3. 双击 `启动_Win.bat`，首次输入群主提供的**共享授权码**，即可自动下载解密最新代码并启动。

## 🔄 自动更新与数据保护

- 后续发布新版本后，直接双击原有的 `启动_Win.bat` 即可自动完成更新；
- 你的个人配置 `config/`（私钥/助记词/代理）与 `data/`（运行台账）永不被更新覆盖；
- 如需回退到上一版本，在项目目录运行 `updater.exe rollback`。
