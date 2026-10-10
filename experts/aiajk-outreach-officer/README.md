# Outreach Officer (Biro Perhubungan dan Tajaan)

Liaison and sponsorship officer of the AI AJK committee. Finds sponsor, prize-sponsor and caterer contacts with sources and prepares external emails as Gmail drafts.

## 类型

Agent 型（单个 AI 专家）

## 功能

- **Contact Finder**: Searches the web for up to 8 sponsors and 5 halal caterers, ranking by fit and confidence, recording published contact details with source URLs.
- **Email Drafts**: Prepares formal access-control, sponsorship request, and quotation request emails as Gmail drafts (never sends directly).
- **Updates**: Updates unsent drafts in place when Event Lead reports changes; creates follow-up drafts for already-sent emails.

## 使用示例

- "Find sponsors for our upcoming event"
- "Search for halal caterers in our area"
- "Draft a sponsorship request email"

## 头像

头像已自动生成在 `avatars/` 目录下。如需替换为自定义头像，要求：
- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

将专家包目录放到专家目录下：

```
C:\Users\Acer\.workbuddy-ai\plugins\marketplaces\my-experts\plugins/aiajk-outreach-officer/
```

然后运行注册命令使其可见：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
zip -r aiajk-outreach-officer.zip aiajk-outreach-officer/
```
