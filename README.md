# 劳拉音乐工作平台

公开安装包与更新补丁下载仓库，源码保存在私有仓库。

## v1.1.5 下载

- [Windows x64 安装包](https://github.com/saypass/yinliu-music-studio-updates/releases/download/v1.1.5/yinliu-music-studio-setup-1.1.5.exe)
- [macOS Apple Silicon DMG](https://github.com/saypass/yinliu-music-studio-updates/releases/download/v1.1.5/yinliu-music-studio-1.1.5.dmg)
- [卸载脚本工具包](https://github.com/saypass/yinliu-music-studio-updates/releases/download/v1.1.5/Laura-Music-Workspace-Uninstall-1.1.5.zip)
- [版本说明及完整文件](https://github.com/saypass/yinliu-music-studio-updates/releases/tag/v1.1.5)

安装包不附带 DeepSeek、可爱云、Suno、明月浩空的服务凭据。登录 Raalaa 后会使用线上托管服务；也可以在关闭账户模式后填写自己的 Key。首次安装时，创作清单和素材目录为空。

旧用户直接覆盖安装会保留本地已保存的 Key、登录信息、存储位置和作品，请勿先删除用户数据。Windows 版启动后会检查更新，发现新版后可点击“下载更新”；网络无法连接 GitHub 时可使用上面的链接手动下载。未签名 macOS 版建议下载 DMG 手动覆盖安装。

v1.1.5 将四项模型与音乐服务统一接入 Raalaa 线上代理，修复本地 DeepSeek Key 失效时单曲自动准备停在歌词和提示词阶段的问题。桌面端只显示服务配置状态，不会取得线上 Key。
