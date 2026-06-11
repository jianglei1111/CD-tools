# Chedan Image2 Skill

## 简介

这是适用于 CDcode 中转站的图片生成与编辑技能包。安装后，Codex 可以通过 Chedan image2 通道生成图片、编辑图片和处理视觉素材。

## 安装方法

1. 解压 `chedan-image2-skill.zip`。
2. 将解压得到的 `chedan-image2` 文件夹复制到 Codex 的 skills 目录。
3. 确认本机 Python 可用，并安装依赖：

```powershell
python -m pip install httpx
```

4. 使用前需要在 `https://www.chedankj.com` 创建 `image` 分组的密钥，并在当前终端设置：

```powershell
$env:IMAGE2_API_KEY="sk-..."
```
