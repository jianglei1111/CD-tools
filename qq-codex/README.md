# QQ-Codex

## 简介

这是适用于 CDcode 中转站的 QQ 本地中转工具。它通过 QQ 开放平台 Bot API 连接 QQ，把 QQ 私聊或群聊消息转发给本地 Codex，并支持图片、文件和常用会话命令。

## 安装方法

1. 解压 `qq-codex-0.1.0.zip`。
2. 进入解压后的目录。
3. 准备 Node.js、npm、Codex CLI 和 QQ 开放平台 Bot 的 `appId`、`clientSecret`。
4. 设置 QQ Bot 凭据：

```powershell
$env:QQ_BOT_APP_ID="<appId>"
$env:QQ_BOT_CLIENT_SECRET="<clientSecret>"
```

5. 安装并启动：

```powershell
npm install
npm run bootstrap
npm run start
```

6. 启动后，在 QQ 私聊或群聊里发送 `/help` 开始使用。
