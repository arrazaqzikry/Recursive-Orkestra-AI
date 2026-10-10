# Budget Officer (Bendahari)

Treasurer of the AI AJK committee. Builds a formula-driven Excel budget with a Prizes sheet and rebalances it when spending exceeds income.

## 类型

Agent 型（单个 AI 专家）

## 功能

Budget Officer is a member of the "AI AJK - Event Committee" expert team, led by Event Lead. It builds a clear, formula-driven event budget in Excel (Malaysian Ringgit) including:

- **Income sheet**: Budget sources with confirmed/expected status and SUM total; sponsored prizes listed as in-kind sponsorship.
- **Prizes sheet**: Prize, quantity, unit value, total (formula), funding type (Budget / Sponsored), with totals per funding type.
- **Expenses sheet**: Categories (Food and beverage, Venue and equipment, Publicity and printing, Prizes and souvenirs, Transport, Logistics, Contingency) with live formula totals; contingency is 10% of all other expense rows.
- **Allocation sheet**: SUMIF per category with percentage of total expenses.
- **Summary sheet**: Participants, total income, total expenses, balance, per-head cost, prizes funded by budget vs sponsored, and WITHIN BUDGET / OVER BUDGET status.
- **Reallocation sheet**: When expenses exceed income, rebalances by reducing quantities or unit costs (never user-listed prizes) and logs every change.
- **budget_summary.md**: Exact figures the proposal must quote.

Also handles updates (Task B): when Event Lead reports a change, updates affected cells, keeps every formula, refreshes budget_summary.md, and lists what changed.

## 使用示例

- Build an event budget with prizes and live formulas
- Rebalance the budget when spending exceeds income
- Generate a budget summary for the proposal

## 头像

头像已自动生成在 `avatars/` 目录下。如需替换为自定义头像，要求：
- 格式：PNG（推荐）或 JPG
- 尺寸：512×512 px
- 大小：单张不超过 500KB

## 安装

将专家包目录放到专家目录下：

```
C:\Users\Acer\.workbuddy-ai\plugins\marketplaces\my-experts\plugins/aiajk-budget-officer/
```

然后运行注册命令使其可见：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
zip -r aiajk-budget-officer.zip aiajk-budget-officer/
```
