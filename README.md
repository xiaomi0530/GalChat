# GalChat

让微信 / QQ 私聊，以 Galgame 的方式展开。

**作者：Shinochanwww** · Windows x64 · 闭源软件

[下载安装包](https://github.com/xiaomi0530/GalChat/releases/tag/v0.5.7) · [快速开始](docs/QUICKSTART.md) · [更新记录](CHANGELOG.md) · [反馈问题](https://github.com/xiaomi0530/GalChat/issues)

![GalChat 入门教程界面](images/galchat-tutorial.png)

## 能做什么

- 在微信和 QQ 之间选择，一次连接一位好友的私聊。
- 将双方消息分别呈现为角色台词，保留历史、手写回复和跳过回复。
- 使用自己的 DeepSeek API Key 生成回复选项，并根据聊天内容驱动表情、动作和好感度。
- 选择四位女性或四位男性角色；每位联系人的角色、背景、关系和好感度分别保存。
- 点击回复选项直接尝试发送；手写回复按 Enter 发送，Ctrl+Enter 换行。

## 下载与使用

1. 在 [0.5.7 发布页](https://github.com/xiaomi0530/GalChat/releases/tag/v0.5.7) 下载 `GalChat-Setup-0.5.7-x64.exe`。
2. 退出旧版 GalChat / 花间信，运行安装程序。已有数据继续沿用。
3. 打开软件，按入门教程创建联系人、连接私聊；需要 AI 时再保存自己的 DeepSeek Key。

安装使用不需要 Node.js 或 Python。新用户默认 QQ、晴栀、慢速文字、显示好感度。完整步骤见[快速开始](docs/QUICKSTART.md)。

## 当前版本范围

**0.5.7 是未签名的 Windows 测试版。** 已通过 368 项核心测试和 97 项界面测试，但这些测试不能代替真实客户端验收。QQ 真实收发仍待完整验收；微信部分环境可能无法提供聊天控件。本版不承诺所有版本、全部最小化状态或完整历史读取均可用，见[兼容性说明](docs/COMPATIBILITY.md)。

保存 DeepSeek Key 会自动开启云端分析及回复生成；可以在设置中关闭。生成不等于发送，发送仍由点选或 Enter 触发。聊天数据库保存在本机且未加密；启用 AI 后，会将当前会话的所选上下文发给 DeepSeek，见[隐私说明](docs/PRIVACY.md)。

## 仓库说明

此仓库仅提供软件介绍、使用说明、问题反馈和安装包下载，**不提供 GalChat 源码，也不是开源项目**。GitHub 自动生成的 “Source code” 压缩包只包含此发布仓库的文档和图片，不是应用源码，也不是安装包。

GalChat 的运行代码与资源随安装包分发；闭源不代表技术上无法提取或逆向查看。软件版权说明见 [COPYRIGHT.md](COPYRIGHT.md)，第三方组件保留各自许可证和版权声明。

GalChat 与腾讯、微信、QQ、DeepSeek 无官方隶属关系。反馈问题时请隐藏聊天正文、联系人信息和 API Key。
