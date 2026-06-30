# CD-tools 🧰✨

这里是 CDcode 工具生态的小主页。

欢迎访问这些入口了解 CDcode 和工具更新：

- 🌐 官网：[www.chedankj.com](https://www.chedankj.com)
- ✍️ 博客：[blog.chedankj.com](https://blog.chedankj.com)
- 🐙 GitHub：[jianglei1111/CD-tools](https://github.com/jianglei1111/CD-tools)

这个仓库只做工具索引，不直接维护安装包下载链接。每个工具都有自己的源码仓库，安装包、更新日志和发布版本都以对应源码仓库的 Releases 为准，避免这里的链接和实际版本不同步。

## 工具小目录 🚀

### 📱 codex-to-phone

手机继续遥控本机 Codex 的桌面桥接工具。适合在微信或 QQ 上继续给电脑里的 Codex 会话发需求、传图片、传文件。

- 🧑‍💻 源码仓库：[jianglei1111/codex-to-phone](https://github.com/jianglei1111/codex-to-phone)
- 📦 下载方式：进入源码仓库后查看 Releases 发布版本

### 🎨 CD-image2

围绕 image2 的生图、修图和批量图片生成工具箱。既有桌面 GUI，也有 Codex skill 和命令行脚本。

- 🧑‍💻 源码仓库：[jianglei1111/CD-image2](https://github.com/jianglei1111/CD-image2)
- 📦 下载方式：进入源码仓库后查看 Releases 发布版本

## 📱 codex-to-phone

![codex-to-phone 界面预览](https://raw.githubusercontent.com/jianglei1111/codex-to-phone/main/docs/images/codex-to-phone-dashboard.png)

`codex-to-phone` 的核心想法很简单：电脑上的 Codex 继续干活，手机上的你继续发指令。

它可以把微信或 QQ Bot 收到的文字、图片、文件转到本机指定的 Codex 会话里。你可以按项目目录找到历史会话，再把某个微信账号或 QQ Bot 绑定到这个会话。

适合这些场景：

- 🚶 出门后继续推进电脑上的 Codex 任务。
- 🖼️ 把手机里的图片或文件直接丢给 Codex。
- 💬 用微信 / QQ 当作移动端入口。
- 📂 按项目目录绑定不同的 Codex 历史会话。

源码仓库：

- [jianglei1111/codex-to-phone](https://github.com/jianglei1111/codex-to-phone)

## 🎨 CD-image2

![CD-image2 GUI 预览](https://raw.githubusercontent.com/jianglei1111/CD-image2/main/assets/chedan-image2-gui.png)

`CD-image2` 把 image2 的生成和编辑流程整理成了三种入口：

- 🖥️ 桌面 GUI：适合日常手动生图、修图、调参数和管理批量任务。
- 🧩 Codex skill：适合让 Codex 在对话里直接调用 image2。
- ⚙️ 命令行脚本：适合自动化流程、批处理和二次集成。

它支持文生图、图生图、图片编辑、批量队列、并发生成和本地结果保存。接口固定访问 `https://sp.chedankj.com/v1`，使用前需要准备 image 分组的 API Key。

源码仓库：

- [jianglei1111/CD-image2](https://github.com/jianglei1111/CD-image2)

## 这个仓库怎么用 🧭

- 想了解工具：看这个 README 的简要介绍。
- 想看源码：进入对应工具的源码仓库。
- 想下载安装包：进入对应源码仓库后查看 Releases 发布版本。
- 想排查问题：优先看对应源码仓库的 README 和 Issues。
- 想新增工具：给这个主页加一个入口，再把源码和安装包放到独立仓库维护。

## 下载小提醒 🔐

安装 `.exe`、`.dmg`、`.pkg`、`.zip` 这类文件时，请以对应源码仓库的 Releases 页面为准。Windows 或 macOS 出现安全提醒时，先确认下载来源，再继续安装。
