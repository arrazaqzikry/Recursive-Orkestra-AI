# Event Committee Team (活动委员会团队)

A multi-agent expert team for end-to-end event committee management, coordinating six specialized officers: Event Execution Director, Budget Officer, Outreach Officer, Task Coordinator, Quality Auditor, and Committee Secretary.

## Type

Team (multi-role collaborative team)

## Members

| Member | Name | Role |
|--------|------|------|
| event-committee-lead-team-lead | Ke / 柯统筹 | Coordination Director (Lead) |
| ec-event-director | Lei / 雷事成 | Event Execution Director |
| ec-budget-officer | Qian / 钱守衡 | Budget Officer |
| ec-outreach-officer | Lian / 连达远 | Outreach Officer |
| ec-task-coordinator | Du / 杜进安 | Task Coordinator |
| ec-quality-auditor | Yan / 严审明 | Quality Auditor |
| ec-secretary | Shu / 舒文记 | Committee Secretary |

## Features

- Full event planning: concept, schedule, logistics, risk management
- Budget preparation and tracking with quotation comparison
- Outreach email drafting for sponsors, vendors, and VIPs
- Task breakdown, assignment, and progress monitoring
- Quality auditing of all deliverables with corrective actions
- Meeting management: agendas, minutes, decision logs, correspondence
- Consolidated reporting with a single source of truth

## Usage Examples

- "Help me plan a university event with full coordination from budget to execution"
- "Analyze our committee's task progress - what's overdue?"
- "Audit the event proposal for budget and workflow gaps"

## Avatars

Avatars are generated in the `avatars/` directory. To replace with custom avatars:
- Format: PNG (recommended) or JPG
- Size: 512x512 px
- File size: max 500KB per image

## Installation

The expert package is located at:

```
C:\Users\arrazaq zikry\.workbuddy-ai\plugins\marketplaces\my-experts\plugins/event-committee-lead/
```

Run the registration command to make it visible:

```bash
python3 scripts/register_expert.py <expert-dir>
```

## Packaging for Sharing

```bash
zip -r event-committee-lead.zip event-committee-lead/
```
