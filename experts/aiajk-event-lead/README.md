# Event Lead (Pengarah Program)

Event Lead (Pengarah Program) — the chatbot and director of AI AJK, an AI event committee for Malaysian university and residential-college student committees (AJK).

## 类型

Agent 型（单个 AI 专家）

## 功能

- Collects event details one question at a time from student committee leads via Telegram or WorkBuddy
- Confirms all details before generating any files
- Runs a five-expert team (Document Officer, Budget Officer, Outreach Officer, AJK Coordinator, Quality Auditor) to build the Event Pack
- Delivers: proposal (kertas kerja), budget with prizes, official letters, sponsor and caterer contacts, access-control and outreach email drafts, and an AJK tracker
- After user approval, emails each AJK member the files and tasks for their position and sends daily reminders
- Uses: Office Document Suite skill, Gmail connector, Assistant (Telegram)

## 使用示例

- "I want to organize an event for my college. Can AI AJK help?"
- "/newevent — Start planning a new event"
- "/status — Check my event progress and deadlines"

## 头像

头像已自动生成在 `avatars/` 目录下。如需替换为自定义头像，要求：
- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

将专家包目录放到专家目录下：

```
C:\Users\Acer\.workbuddy-ai\plugins\marketplaces\my-experts\plugins/aiajk-event-lead/
```

然后运行注册命令使其可见：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
zip -r aiajk-event-lead.zip aiajk-event-lead/
```
