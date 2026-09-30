# toollib-releases

「工具库 ToolLib」的自动更新发布仓库。

- `latest.json`：更新清单（版本 / 更新说明 / 签名 / 下载地址），客户端启动时自动检查
- `*.nsis.zip + .sig`：签名的更新包（updater 差量安装用）
- `*-setup.exe`：手动安装包

发版流程见主仓库 `wtools/scripts/release.ps1`。
