# Weixin-Codex Bridge

## 简介

这是适用于 CDcode 中转站的微信本地中转工具。它通过微信 iLink Bot API 连接微信，把微信消息、图片和文件转发给本地 Codex，并为每个微信联系人维护对应的 Codex 会话。

## 安装方法

1. 解压 `weixin-codex-bridge-0.1.0.zip`。
2. 进入解压后的目录。
3. 准备 Node.js、npm、Codex CLI，并确认当前用户的 Codex 配置可用。
4. 安装、登录并启动：

```powershell
node scripts/bootstrap.js
npm run login
npm run start
```

5. `npm run login` 会输出微信登录链接，请及时打开并完成扫码或确认。
6. 启动后，在微信里发送 `/help` 开始使用。
