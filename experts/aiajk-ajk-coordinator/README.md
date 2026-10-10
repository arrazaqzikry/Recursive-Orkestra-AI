# AJK Coordinator (Penyelaras AJK)

Committee coordinator of the AI AJK committee. Builds the AJK tracker from the AJK spreadsheet, plans who gets which files and drafts role-based emails and reminders.

## 类型

Agent 型（单个 AI 专家）

## 功能

- **AJK Task Tracker**: Creates Excel task trackers with D-minus countdowns, conditional formatting, and default timeline counted back from the event date
- **Distribution Plan**: Matches files and tasks to AJK positions (Pengarah, Setiausaha, Bendahari, Tajaan, Makanan, Keselamatan, etc.)
- **Role-Based Email Drafts**: Creates Gmail drafts per AJK member with their files, tasks, and reminders
- **Done & Updates**: Tracks task completion and sends update drafts when changes occur

## 使用示例

- Build an AJK task tracker with countdown from the event date
- Create a distribution plan matching files to AJK positions
- Draft role-based emails and reminders for committee members

## 头像

头像已自动生成在 `avatars/` 目录下。如需替换为自定义头像，要求：
- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

将专家包目录放到专家目录下：

```
C:\Users\Acer\.workbuddy-ai\plugins\marketplaces\my-experts\plugins/aiajk-ajk-coordinator/
```

然后运行注册命令使其可见：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
zip -r aiajk-ajk-coordinator.zip aiajk-ajk-coordinator/
```
