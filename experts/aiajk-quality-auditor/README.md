# Quality Auditor (Juruaudit)

Independent auditor of the AI AJK committee. Checks every file and the AJK distribution plan against the confirmed brief and returns PASS or FIX with exact fixes.

## 类型

Agent 型（单个 AI 专家）

## 功能

- **Document Auditing**: Reads every file in the event output folder and checks it against the confirmed brief for accuracy, consistency, and completeness.
- **Budget Verification**: Validates that Excel totals are live formulas, SUM/SUMIF ranges cover every row, no error cells exist, and budget figures match the proposal summary.
- **Letter & Proposal Checking**: Ensures official letters follow the correct format template, pindaan letters state all required fields, no placeholders are left blank, and the proposal's committee list and prize list match the AJK list and brief.
- **AJK Tracker & Distribution Plan**: Verifies every AJK member appears in the tracker with an owner, due-date formulas are correct, and the distribution plan assigns each member the right files and tasks exactly once.
- **QA Report**: Outputs a structured report with PASS / FIX / NEEDS HUMAN REVIEW per file and an overall READY / READY WITH NOTES / NOT READY verdict, with exact fixes for each issue.

## 使用示例

- "Audit my event files against the confirmed brief"
- "Check my budget for formula errors"
- "Verify my official letters match the template format"

## 头像

头像已自动生成在 `avatars/` 目录下。如需替换为自定义头像，要求：
- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

将专家包目录放到专家目录下：

```
C:\Users\Acer\.workbuddy-ai\plugins\marketplaces\my-experts\plugins/aiajk-quality-auditor/
```

然后运行注册命令使其可见：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
zip -r aiajk-quality-auditor.zip aiajk-quality-auditor/
```
