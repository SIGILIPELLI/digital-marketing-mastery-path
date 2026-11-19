---
description: "Attribution & Marketing Mix Modelling — Customers see many touchpoints before buying — a Reel, a Google search, an email. Attribution decides how much…"
---

# 02 · Attribution & Marketing Mix Modelling

Customers see many touchpoints before buying — a Reel, a Google search, an email. **Attribution** decides how much credit each gets. Getting it wrong means cutting the channels that create demand and over-funding the ones that just catch it. This module covers attribution models, incrementality and marketing mix modelling.

## 1. Attribution models

1. **Last click** — all credit to the final touch. Simple; over-credits branded search and retargeting.
2. **First click** — all credit to the first touch; over-credits awareness.
3. **Linear / time decay / position-based** — rule-based splits.
4. **Data-driven attribution (DDA)** — GA4 and Google Ads' default; uses machine learning on your conversion paths to estimate each touchpoint's contribution.
5. Compare models in GA4 (**Advertising → Attribution → Model comparison**) to see which channels gain or lose credit.

## 2. The limits of attribution

1. It only sees **trackable** touches; word of mouth, offline ads, podcasts and many social views are invisible.
2. Consent choices, ad blockers and cross-device journeys break paths.
3. Platforms report their own view (Meta, Google) and often both claim the same sale.
4. Attribution measures **correlation along paths**, not whether the ad *caused* the sale.

## 3. Incrementality testing

1. The question: *how many sales happened because of this ad that wouldn't have happened otherwise?*
2. **Geo experiments** — run ads in some cities and not in comparable ones, compare sales lift.
3. **Holdout / conversion lift tests** — Meta and Google offer lift studies that randomly withhold ads from a control group.
4. **On/off tests** — pause a channel (e.g. branded search) for a period and measure the change in total conversions.
5. Use results to calibrate how much you trust each platform's reported numbers.

## 4. Marketing mix modelling (MMM)

1. MMM uses statistical models on weekly spend, sales and external factors (seasonality, price, festivals, competitors) to estimate each channel's contribution and diminishing returns.
2. Works without user-level tracking — privacy-friendly and includes offline channels.
3. Needs 2+ years of weekly data or strong priors; open-source tools include Google's **Meridian** and Meta's **Robyn**.
4. Use MMM for budget allocation, incrementality tests for validation, and attribution for day-to-day optimisation — together they triangulate the truth.

## Cheat sheet

| Method | Best for | Weakness |
|---|---|---|
| Last click | Simple reporting | Over-credits bottom funnel |
| Data-driven | Daily optimisation | Only trackable touches |
| Geo / lift tests | True incrementality | Needs scale, time |
| MMM | Budget allocation, offline | Needs data, modelling skill |
| Triangulation | Strategic decisions | More effort |

## How It Actually Works

Attribution assigns credit for conversions that happened; incrementality asks what would have happened without the marketing. Branded search and retargeting often look brilliant in attribution because they reach people already about to buy — their incremental impact can be much smaller. MMM steps back from individual users and estimates channel effects from how total outcomes move with spend over time, accounting for saturation and lag. Mature teams combine all three because each corrects the blind spots of the others.

## Exercise

In GA4 (or the Google demo account), compare data-driven and last-click attribution for paid and organic channels and note the three biggest shifts. Then design a geo incrementality test for one channel: test and control regions, duration, metric and how you'd decide.
