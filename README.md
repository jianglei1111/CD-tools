# CDcode 🚀

CDcode 是一组面向 Codex 的本地中转工具集合，用来把 QQ、微信、图片生成等入口接入到本地 Codex 工作流里。

它的目标很简单：让消息、文件、图片和任务可以更顺手地流进 Codex，让 Codex 更像一个随时待命的本地助手。✨

## 工具一览

| 工具 | 作用 | 适合场景 |
| --- | --- | --- |
| 🎨 `chedan-image2-skill` | Chedan image2 图片生成与编辑技能包 | 生成图片、编辑图片、制作设计素材 |
| 💬 `qq-codex` | QQ 到 Codex 的本地桥接器 | QQ 私聊、群聊消息接入 Codex |
| 🟢 `weixin-codex-bridge` | 微信到 Codex 的本地桥接器 | 微信消息、图片、文件接入 Codex |

## 这 3 个工具能做什么？

### 🎨 Chedan Image2 Skill

让 Codex 使用 Chedan image2 通道生成和编辑图片。适合海报、头像、产品图、设计草稿等视觉任务。

### 💬 QQ-Codex

通过 QQ 开放平台 Bot API，把 QQ 私聊或群聊消息转发给本地 Codex。适合把 Codex 接到 QQ 工作流里，支持文字、图片、文件和常用会话命令。

### 🟢 Weixin-Codex Bridge

通过微信 iLink Bot API，把微信消息、图片和文件转发给本地 Codex。适合在微信里直接调用本地 Codex，并保持联系人对应的连续会话。

## 快速开始

每个工具都已经放在独立目录里，并附带自己的安装说明：

- `chedan-image2-skill/README.md`
- `qq-codex/README.md`
- `weixin-codex-bridge/README.md`

选择需要的工具，进入对应目录，按 README 的安装方法操作即可。

## 项目结构

```text
CD-tools/
├─ chedan-image2-skill/
│  ├─ chedan-image2-skill.zip
│  └─ README.md
├─ qq-codex/
│  ├─ qq-codex-0.1.0.zip
│  └─ README.md
├─ weixin-codex-bridge/
│  ├─ weixin-codex-bridge-0.1.0.zip
│  └─ README.md
└─ README.md
```

## 一句话

CDcode 把不同入口接到 Codex，让 Codex 不只在终端里工作，也能出现在你的聊天、文件和图片任务里。⚡
