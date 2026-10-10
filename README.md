# WorkBuddy Event Committee AI Agents

A team of AI agents built in [WorkBuddy AI](https://www.workbuddy.ai) for end-to-end event committee management — from planning and budgeting to outreach, documentation, and quality auditing.

Built for **DORMATHON 2026 Track 2**.

## Agents

| Agent | Role | Description |
|-------|------|-------------|
| **aiajk-event-lead** | Event Lead (Pengarah Program) | Director of the AI AJK committee. Collects event details, searches Google Drive, runs the seven-expert team, and emails AJK members after approval. |
| **aiajk-budget-officer** | Budget Officer (Bendahari) | Builds formula-driven Excel budgets with a Prizes sheet and rebalances when spending exceeds income. |
| **aiajk-outreach-officer** | Outreach Officer (Biro Perhubungan dan Tajaan) | Finds sponsor, prize-sponsor, and caterer contacts with sources. Prepares external emails as Gmail drafts. |
| **aiajk-ajk-coordinator** | AJK Coordinator (Penyelaras AJK) | Builds AJK task trackers with countdowns, distributes files by position, drafts role-based emails and reminders. |
| **aiajk-quality-auditor** | Quality Auditor (Juruaudit) | Independent auditor. Checks every file and distribution plan against the confirmed brief. Returns PASS or FIX with exact fixes. |
| **aiajk-document-officer** | Document Officer (Setiausaha) | Secretary. Fills letter templates, writes official Malaysian letters and event proposals (kertas kerja) as Word and PDF. |
| **event-committee-lead** | Event Committee Team (Team) | Full team expert with 7 members: lead + event director, budget officer, outreach officer, task coordinator, quality auditor, and secretary. |

## Repository Structure

```
experts/
  aiajk-event-lead/
    .codebuddy-plugin/plugin.json   # Expert metadata
    agents/aiajk-event-lead.md       # Agent prompt definition
    avatars/                         # Expert avatar image
    manifest.yaml                    # Plugin manifest
    README.md                        # Expert README
  aiajk-budget-officer/
    ...
  aiajk-outreach-officer/
    ...
  aiajk-ajk-coordinator/
    ...
  aiajk-quality-auditor/
    ...
  aiajk-document-officer/
    ...
  event-committee-lead/
    agents/                          # 7 agent definitions (team lead + 6 members)
    .codebuddy-plugin/plugin.json   # Team expert metadata
    ...
```

## How to Use

These agents are designed for the [WorkBuddy AI](https://www.workbuddy.ai) platform. To install:

1. Clone this repository
2. Copy the desired expert folder(s) into your WorkBuddy experts directory:
   ```
   ~/.workbuddy-ai/plugins/marketplaces/my-experts/plugins/
   ```
3. Restart WorkBuddy AI or refresh your expert list
4. Start a conversation with the expert from the Experts panel

## License

MIT
