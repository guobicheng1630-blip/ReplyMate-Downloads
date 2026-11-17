# ReplyMate · Mac 截图与回复助手

## ⬇️ [下载安装包 · 1.28.2 测试版](https://github.com/guobicheng1630-blip/ReplyMate-Downloads/releases/download/v1.28.2/ReplyMate-macOS-arm64.zip)

**点击上方链接即可直接下载，无需登录 GitHub。下载文件名应为 `ReplyMate-macOS-arm64.zip`。**

适用于 **Apple 芯片 Mac（M1 或更新）· macOS 14 及以上**。暂不支持 Intel Mac 或 Windows。

> **不要下载 Source code (zip)、Source code (tar.gz)，也不要使用 Code → Download ZIP。**
> 这些不是可安装的软件。本仓库仅提供安装包与说明，源码保持私有。使用 ReplyMate **不需要 Xcode、不需要终端命令，也不需要自行编译**。

[查看版本说明与其他版本](https://github.com/guobicheng1630-blip/ReplyMate-Downloads/releases)

## 安装只需三步

1. 点击顶部「下载安装包」，下载 `ReplyMate-macOS-arm64.zip`。
2. 双击 ZIP 解压，得到 **ReplyMate.app**。
3. 将 **ReplyMate.app** 拖入访达的「应用程序」，再双击打开。

如果解压后没有看到 ReplyMate.app，说明下载的不是正确安装包，请回到顶部重新下载。

### 如果 macOS 阻止打开

当前是**未经过 Apple 公证的测试版**，首次打开可能被系统阻止；这不代表需要安装 Xcode或编译源码。请保留系统安全保护，不要关闭 Gatekeeper 或 SIP。遇到阻止提示时，请记录完整提示并参考 [Apple 的说明](https://support.apple.com/zh-cn/102445)；希望使用经过苹果公证的版本，可等待后续正式版。

## 首次使用

- 在设置中配置支持图片的 AI 服务、API Key 和模型；API 使用费用由你自己的服务账户承担。
- 截图时按系统提示授权屏幕录制。原聊天框填入功能需要辅助功能权限。
- 支持截图、多图收集、截图历史与文字搜索、聊天回复、翻译解释和继续追问。
- **填入聊天框不会自动发送。**
- 微信部分版本的截图可能黑色或透明，属于已知兼容性限制。

## 以后如何更新

在 **设置 → 通用 → 软件更新** 点击「更新并重启」，下载校验后确认安装，软件会自动重启，无需再次去 GitHub 下载替换。

- 保留设置、截图历史和钥匙串中的 API 密钥。
- 保持同一签名和「应用程序」安装位置；权限最终由 macOS 管理。
- 更新前请复制需要保留的未保存输入和生成结果。
- 1.27.0 用户需手动安装新版一次；1.28.1 用户请关闭设置弹窗，从菜单栏更新入口升级。
- 自动检查在启动时及每 6 小时进行，可在设置中关闭。

## 数据与隐私

下载包不包含开发者的密钥、聊天记录或截图。API 密钥保存在本机钥匙串，截图历史保存在本机。只有主动调用 AI 时才发送相应内容到你配置的服务。更新检查仅访问公开 GitHub 版本信息。

安装包校验文件：[SHA256SUMS.txt](https://github.com/guobicheng1630-blip/ReplyMate-Downloads/releases/download/v1.28.2/SHA256SUMS.txt)。
