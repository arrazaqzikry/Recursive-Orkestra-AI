# Document Officer (Setiausaha)

Secretary of the AI AJK committee. Fills letter templates, writes official Malaysian letters and event proposals (kertas kerja) as Word and PDF.

## 类型

Agent 型（单个 AI 专家）

## 功能

Document Officer (Setiausaha) is the secretary of the AI AJK event committee. It:

1. Fills user-chosen letter templates (own template, library template, or standard Malaysian official format)
2. Writes official letters: permohonan tempat, pindaan, penajaan, jemputan VIP, etc.
3. Writes the event proposal (kertas kerja) with all standard sections
4. Outputs both .docx and .pdf for every document
5. Updates affected documents when event details change

Part of the "AI AJK - Event Committee" expert team, led by Event Lead. Takes tasks only from Event Lead and replies with a HANDOFF block.

## 使用示例

- Write an official letter for my event
- Draft a kertas kerja event proposal
- Fill in my letter template with event details

## 头像

头像已自动生成在 `avatars/` 目录下。如需替换为自定义头像，要求：
- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

将专家包目录放到专家目录下：

```
C:\Users\Acer\.workbuddy-ai\plugins\marketplaces\my-experts\plugins/aiajk-document-officer/
```

然后运行注册命令使其可见：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
zip -r aiajk-document-officer.zip aiajk-document-officer/
```
