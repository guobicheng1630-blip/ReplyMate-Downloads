# ReplyMate · Mac 截图与回复助手

## ⬇️ [下载 DMG 安装包 · 1.28.2 测试版](https://github.com/guobicheng1630-blip/ReplyMate-Downloads/releases/download/v1.28.2/ReplyMate-macOS-arm64.dmg)

**点击上方链接即可直接下载，无需登录 GitHub。下载文件名应为 `ReplyMate-macOS-arm64.dmg`。**

适用于 **Apple 芯片 Mac（M1 或更新）· macOS 14 及以上**。暂不支持 Intel Mac 或 Windows。

> **不要下载 Source code (zip)、Source code (tar.gz)，也不要使用 Code → Download ZIP。**
> 这些不是可安装的软件。本仓库仅提供安装包与说明，源码保持私有。使用 ReplyMate **不需要 Xcode、不需要终端命令，也不需要自行编译**。

[查看版本说明与其他版本](https://github.com/guobicheng1630-blip/ReplyMate-Downloads/releases)

## 安装步骤（无需 Xcode）

1. 点击顶部链接下载 `ReplyMate-macOS-arm64.dmg`，双击打开。
2. 在白色安装窗口中，将左侧 **ReplyMate** 图标拖到右侧 **应用程序**。
3. 等待复制完成，从访达「应用程序」打开 ReplyMate，不要直接从安装磁盘运行。
4. 安装磁盘可以推出。窗口里的「安装说明」可随时打开阅读。

## 首次打开被 macOS 拦截怎么办？

当前测试版未经过 Apple 公证。仅在确认来自本仓库、愿意运行测试版时，由你本人按以下步骤操作；不希望创建例外，可以等待公证版。

**提示“无法验证开发者”或“无法验证是否包含恶意软件”：**

1. 先尝试打开「应用程序」里的 ReplyMate，关闭拦截提示。
2. 打开 **系统设置 → 隐私与安全性**，向下滚动到「安全性」。
3. 在 ReplyMate 对应提示旁点击 **仍要打开（Open Anyway）**。
4. 完成系统要求的身份验证，再点击「打开」。

入口通常在尝试打开后约一小时内提供。没有看到时再尝试打开一次；公司或学校管理的电脑可能限制此操作，需要联系管理员。这是针对该应用的单独例外，不需要关闭 Gatekeeper、SIP，也不要执行清除隔离的终端命令。

**提示“已损坏”、检测到恶意软件或“会损坏你的电脑”：**不要强行打开；重新从官方链接下载并反馈完整报错，不要当作普通开发者验证问题处理。

**提示不支持此 Mac：**检查是否为 Apple 芯片、macOS 是否为 14 或更新版本。当前不支持 Intel。

**要求 Xcode、开发工具许可或编译：**通常下载错了源码包。回到顶部下载 DMG，不要下载 Source code。

参考：[Apple 安全打开 App](https://support.apple.com/en-ie/102445)、[Apple 的“仍要打开”步骤](https://support.apple.com/en-gb/guide/mac-help/mh40617/mac)。

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

DMG 校验文件：[DMG-SHA256.txt](https://github.com/guobicheng1630-blip/ReplyMate-Downloads/releases/download/v1.28.2/DMG-SHA256.txt)。
