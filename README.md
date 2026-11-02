# AI8.MY Desktop

AI8.MY Windows 桌面客户端的官方安装包与更新仓库。

**[下载最新 Windows x64 安装包](https://github.com/afsdfdf/ai8app-releases/releases/latest)** · [AI8.MY 官网](https://ai8.my)

## 安装与使用

1. 在 Releases 下载 `AI8.MY-版本-windows-x64-setup.exe` 并安装。
2. 打开 AI8.MY，使用官网登录并选择自己的 API Key。
3. 从主导航进入客户端配置、创作工作台或对话编程。

应用附带 Codex Rust 编程引擎，可选择项目、模型、查看命令输出及文件差异，并恢复编程历史。实际模型能力与费用以账户权限和 AI8.MY 服务为准。

音乐和视频功能当前维护，已有素材保留。每个版本的验证范围与已知限制见 Release 说明。

## 更新

0.2.0 起，应用启动后及每 6 小时检查更新。可在设置中手动检查、下载和查看版本说明。安装前须保存工作并确认，运行中的编程或创作任务会阻止安装。

更新包使用独立公钥验证签名，并将签名绑定到版本号；更新清单位于 `releases/latest/download/latest.json`。该签名用于客户端验证更新包，不是 Windows Authenticode 发布者证书。目前 Windows 可能显示未知发布者提示。

0.1.0 旧预览版没有更新模块，需要手动安装 0.2.0 或更高版本。

## 反馈

请在 Issues 提供版本号、Windows 版本、复现步骤和已脱敏的错误信息。不要发送密码、API Key、登录凭据、真实项目数据库或私密项目内容。

本仓库只分发安装包、签名与校验清单。源码在独立私有仓库维护，安装包附带相关来源及第三方许可声明。
