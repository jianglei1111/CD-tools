# CDcode / CD-tools 🚀

CDcode 是一个聚合多种顶尖多模态模型的 API 中转站，提供稳定、高速、价格实惠的模型调用体验，并围绕 Codex 等使用场景构建了丰富的工具生态。

CD-tools 是 CDcode 的工具包仓库，用来集中存放生态工具所需的安装包、桥接器和技能包。✨

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

CDcode 负责中转，CD-tools 负责存放工具包。⚡
