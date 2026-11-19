---
description: "Marketing Dashboards with Looker Studio — Clients and managers don't want five logins — they want one clear view of what's working. Looker Studio (free…"
---

# 04 · Marketing Dashboards with Looker Studio

Clients and managers don't want five logins — they want one clear view of what's working. **Looker Studio** (free from Google) turns GA4, Search Console, Google Ads and spreadsheets into live dashboards. This module builds one that drives decisions.

## 1. Plan before you build

1. Ask: *Who reads this and what decision do they make?* An owner wants leads, cost and revenue; an SEO specialist wants queries and positions.
2. Pick 5–8 **KPIs** tied to goals: leads, cost per lead, conversion rate, revenue/ROAS, organic clicks, email sign-ups.
3. Sketch the layout: top row of scorecards (with comparison to previous period), trend charts, channel breakdown, top campaigns/pages table.

## 2. Connect data sources

1. Go to **lookerstudio.google.com → Create → Report**.
2. Add data sources: **Google Analytics** (your GA4 property), **Search Console** (site or URL impression), **Google Ads**, **Google Sheets** (e.g. offline leads or Meta Ads exports).
3. For Meta Ads and other platforms, use a connector (paid partners) or a scheduled Google Sheets export.
4. Check field names: GA4 `Key events`, `Sessions`, `Session default channel group`, `Session campaign`.

## 3. Build the dashboard

1. **Scorecards** for each KPI with "Comparison date range: previous period" to show change.
2. **Time series** chart of leads and sessions by week.
3. **Bar chart** of key events by channel.
4. **Table** of campaigns with sessions, key events, cost and calculated cost per lead.
5. **Calculated fields**: e.g. `Cost per lead = Cost / Key events` (blend Google Ads cost with GA4 conversions, or calculate within the Ads source).
6. Add a **date range control** and **filters** (channel, device, campaign).
7. Use clear titles, short notes explaining definitions, and consistent colours.

## 4. Share and use it

1. Share with view access or schedule a PDF email (File → Schedule delivery) weekly or monthly.
2. Add a short commentary box each month: what happened, why, what you'll do next.
3. Review data quality: compare dashboard leads with your CRM/inbox, document known gaps.
4. Keep the dashboard focused — a page per audience is better than one cluttered page.

## Cheat sheet

| Component | Use |
|---|---|
| Scorecard + comparison | KPI and change vs previous period |
| Time series | Trends over weeks |
| Bar chart | Compare channels |
| Table | Campaign/page detail |
| Calculated field | CPL, ROAS, conversion rate |
| Controls | Date range, filters |
| Schedule delivery | Automatic emailed reports |

## How It Actually Works

Looker Studio doesn't store your data; it queries each connected source live (with caching) and applies calculations at report time. That's why blended data from different sources must share a join key (like date or campaign name) and why naming consistency — especially UTM campaign names — matters so much. The real value of a dashboard isn't the charts; it's agreeing on definitions once, so every weekly conversation starts from the same numbers.

## Exercise

Build a one-page Looker Studio dashboard for your site (use the free **Google Merchandise Store GA4 demo account** if you don't have your own data): six scorecards with comparisons, a weekly trend, channel breakdown, and a campaign table with a calculated conversion rate. Add a date control and write a three-sentence monthly commentary.
