---
description: "A/B Testing & Experimentation — An A/B test shows two versions of something to comparable groups at the same time and measures which performs better. Done…"
---

# 05 · A/B Testing & Experimentation

An **A/B test** shows two versions of something to comparable groups at the same time and measures which performs better. Done properly, it replaces opinion with evidence. This module covers designing valid tests and reading the results honestly.

## 1. What and where to test

1. **Landing pages** — headline, offer, form length, social proof placement.
2. **Ads** — headlines, creative, angles (price vs quality vs speed).
3. **Emails** — subject lines, send times, CTA.
4. **Pricing and offers** — free delivery vs discount (carefully, with clear rules).
5. Test changes big enough to matter; tiny tweaks need huge traffic to detect.

## 2. Design a valid test

1. One **primary metric** decided in advance (e.g. form submission rate), plus guardrail metrics (lead quality, bounce rate).
2. A clear **hypothesis** (Level 2, Module 9 template).
3. **Random split** of traffic between control (A) and variant (B) at the same time — never compare this month to last month and call it a test.
4. **Sample size**: use a calculator (search "A/B test sample size calculator"). Example: with a 5% baseline conversion and wanting to detect a 20% relative lift (to 6%), you need roughly 8,000 visitors per variant at standard settings.
5. Fix the **duration** in advance — at least one full week (ideally two) to cover weekday/weekend patterns.

## 3. Run it with tools

1. Landing page builders and CMS plugins (e.g. Unbounce, Instapage, WordPress plugins), or experimentation platforms like VWO, Optimizely or AB Tasty.
2. Email tools have built-in subject-line tests.
3. **Google Ads Experiments** (split a campaign to test bidding or landing pages) and **Meta A/B tests** (Experiments in Ads Manager) split audiences properly.
4. Make sure tracking is identical for both variants.

## 4. Read results correctly

1. Don't **peek** and stop when one variant looks ahead — early swings are often noise. Wait for the planned sample size.
2. Look at the **confidence/statistical significance** your tool reports (commonly 95%) and the **confidence interval** of the lift.
3. Check segments only to generate new hypotheses; slicing until something "wins" creates false positives.
4. Verify guardrails: did more leads come at the cost of quality?
5. Document: hypothesis, dates, sample, result, decision, learning. Roll out winners; treat "no difference" as a valid, useful result.

## Cheat sheet

| Principle | Rule |
|---|---|
| One primary metric | Decided before launch |
| Concurrent random split | A and B at the same time |
| Sample size | Calculate in advance |
| Duration | ≥ 1–2 full weeks |
| No peeking | Stop at planned sample |
| Significance | ~95% and check interval |
| Log | Record every test and learning |

## How It Actually Works

Conversion rates naturally fluctuate, so a difference between two versions might just be chance. Statistical tests estimate how likely it is to see a difference this large if the versions were actually equal; significance at 95% means that would happen by chance only about 5% of the time — but only if you follow the plan. Peeking and stopping early, or testing many variants and segments, multiplies the chances of a false win. Randomising at the same time removes seasonality and campaign effects that make before/after comparisons unreliable.

## Exercise

Design two A/B tests for your business (one landing page, one email or ad): hypothesis, primary and guardrail metrics, variants, sample size from a calculator, duration and decision rule. If you have traffic, run the email subject-line test and record the result.
