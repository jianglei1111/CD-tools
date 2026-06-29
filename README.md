# CD-tools

CD-tools 是 CDcode 相关工具的主入口仓库，用来集中展示可直接使用的桌面工具、Codex skill、脚本客户端和安装包下载入口。

这个仓库本身更像一个工具主页和索引页：每个工具都有自己的开源仓库，源码、安装包、使用说明和版本更新都放在对应子仓库里维护。

## 工具清单

| 工具 | 适合谁用 | 主要能力 | 下载入口 | 源码仓库 |
| --- | --- | --- | --- | --- |
| `codex-to-phone` | 想在手机上继续操作本机 Codex 的用户 | 将本机 Codex 会话连接到微信和 QQ Bot；手机发来的文字、图片、文件可转入指定 Codex 会话 | [Windows 安装包](https://github.com/jianglei1111/codex-to-phone/raw/main/downloads/codex-to-phone-0.1.0-setup.exe) | [jianglei1111/codex-to-phone](https://github.com/jianglei1111/codex-to-phone) |
| `CD-image2` | 需要调用 image2 生图、修图或批量生成图片的用户 | 提供桌面 GUI、Codex skill 和命令行脚本三种入口，支持文生图、图生图/图片编辑、批量队列和本地结果保存 | [最新 Release](https://github.com/jianglei1111/CD-image2/releases/latest) | [jianglei1111/CD-image2](https://github.com/jianglei1111/CD-image2) |

## codex-to-phone

`codex-to-phone` 是一个把本机 Codex 会话连接到微信和 QQ 的桌面工具。它的核心目标很直接：人在手机上发消息，活继续在电脑上的 Codex 会话里干。

它适合这些场景：

- 出门后想继续给某个 Codex 会话追加需求。
- 想把手机里的图片、文件或文字需求转给本机 Codex。
- 希望用微信或 QQ Bot 作为自己的移动端入口。
- 需要按项目目录选择并绑定不同的 Codex 历史会话。

当前子仓库提供 Windows x64 安装包。使用前需要电脑上已经安装并登录 Codex，且电脑保持运行。

入口：

- [项目主页](https://github.com/jianglei1111/codex-to-phone)
- [Windows 安装包](https://github.com/jianglei1111/codex-to-phone/raw/main/downloads/codex-to-phone-0.1.0-setup.exe)

## CD-image2

`CD-image2` 把 image2 生图流程整理成三种入口：

- 桌面 GUI：适合手动生图、修图、调参数和管理批量任务。
- Codex skill：适合让 Codex 在对话中直接调用 image2 生成或编辑图片。
- 命令行脚本：适合自动化流程、批处理和二次集成。

它支持文生图、图生图/图片编辑、批量队列、并发生成、本地结果保存，并固定访问 `https://sp.chedankj.com/v1`。使用时需要准备 image 分组的 API Key。

入口：

- [项目主页](https://github.com/jianglei1111/CD-image2)
- [最新 Release](https://github.com/jianglei1111/CD-image2/releases/latest)
- [Codex skill 源码](https://github.com/jianglei1111/CD-image2/tree/main/cd-image2)

## 仓库定位

主仓库负责：

- 展示工具列表。
- 说明每个工具能解决什么问题。
- 提供下载和源码入口。
- 作为 CDcode 工具生态的统一主页。

子仓库负责：

- 维护源码。
- 发布安装包、压缩包或 skill 包。
- 编写具体安装和使用说明。
- 记录版本更新和校验信息。

## 下载建议

优先从每个工具自己的 Release 页面或仓库下载目录获取安装包。下载 `.exe`、`.dmg`、`.pkg`、`.zip` 后，如果系统有安全提醒，请确认来源是上面的官方仓库链接。

如果你要二次开发、排查问题或重新打包，请进入对应工具的源码仓库查看完整说明。
