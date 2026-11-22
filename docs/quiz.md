---
title: "Final Quiz"
description: "Test what you have learned across all four levels of Digital Marketing \u0026 SEO Mastery Path with a 19-question final quiz."
---

# Final Quiz

19 questions drawn from all four levels of this course. You need **70% (14 out of 19)** to pass —
you can retake it as many times as you like. Your best result is saved in this browser.

<div id="mp-quiz-root"></div>

<script type="application/json" id="mp-quiz-data">
[
  {
    "question": "What are CTR, CPC, CPA and ROAS for these results?\n```python\nspend,impr,clicks,conv,rev=800,40000,1000,40,4000\nprint(round(100*clicks/impr,2), spend/clicks, spend/conv, rev/spend)\n```\n",
    "options": [
      "2.5 0.8 0.05 5.0",
      "25.0 0.8 20.0 5.0",
      "2.5 0.8 20.0 5.0",
      "2.5 8.0 20.0 5.0"
    ],
    "correctIndex": 2,
    "explanation": "CTR = clicks/impressions; CPC = spend/clicks; CPA = spend/conversions; ROAS = revenue/spend. (Illustrative numbers; real campaign results vary.) Verified by running it."
  },
  {
    "question": "A funnel has 20,000 visitors, 1,000 leads, 200 opportunities and 50 customers. Which step has the lowest conversion rate?\n```python\nst=[('visit->lead',1000/20000),('lead->opp',200/1000),('opp->customer',50/200)]\nprint(min(st,key=lambda x:x[1])[0], [round(100*r,1) for _,r in st])\n```\n",
    "options": [
      "visit->lead [5.0, 20.0, 25.0]",
      "opp->customer [5.0, 20.0, 25.0]",
      "visit->lead [0.05, 0.2, 0.25]",
      "lead->opp [5.0, 20.0, 25.0]"
    ],
    "correctIndex": 0,
    "explanation": "Compare each rate with the stage before it. (Illustrative numbers; real campaign results vary.) Verified by running it."
  },
  {
    "question": "Revenue per 100 visitors at 2% conversion and 60 average order value, then after raising conversion to 2.5%?\n```python\nprint(100*0.02*60, 100*0.025*60)\n```\n",
    "options": [
      "12.0 15.0",
      "120.0 150.0",
      "120.0 120.0",
      "1200.0 1500.0"
    ],
    "correctIndex": 1,
    "explanation": "Small conversion gains compound across all traffic. (Illustrative numbers; real campaign results vary.) Verified by running it."
  },
  {
    "question": "Customer lifetime value with 40% margin, 3 orders per year of 50 for 4 years versus a CAC of 90: LTV and LTV:CAC?\n```python\nltv=0.40*50*3*4\nprint(ltv, round(ltv/90,2))\n```\n",
    "options": [
      "240.0 0.38",
      "600.0 6.67",
      "240.0 2.67",
      "60.0 0.67"
    ],
    "correctIndex": 2,
    "explanation": "LTV uses margin, not revenue; a ratio around 3 is a common target. (Illustrative numbers; real campaign results vary.) Verified by running it."
  },
  {
    "question": "Which journey credit does a linear model give a customer who touched search, email and social before buying 90?\n```python\nprint({c:90/3 for c in ['search','email','social']})\n```\n",
    "options": [
      "{'search': 45.0, 'social': 45.0}",
      "{'social': 90}",
      "{'search': 90}",
      "{'search': 30.0, 'email': 30.0, 'social': 30.0}"
    ],
    "correctIndex": 3,
    "explanation": "Last-click would credit only the final touch. (Illustrative numbers; real campaign results vary.) Verified by running it."
  },
  {
    "question": "A campaign has a high CTR but few conversions. What should you look at first?",
    "options": [
      "Bid",
      "The landing page and message match after the click",
      "Budget",
      "Ad colour"
    ],
    "correctIndex": 1,
    "explanation": "Traffic is arriving; the page or offer is failing."
  },
  {
    "question": "Why use UTM parameters?",
    "options": [
      "Security",
      "Speed",
      "Ranking",
      "So analytics can attribute visits and conversions to source, medium and campaign"
    ],
    "correctIndex": 3,
    "explanation": "Agree a naming convention."
  },
  {
    "question": "A 2x ROAS campaign is called a success. What question is missing?",
    "options": [
      "How many clicks",
      "What colour",
      "What font",
      "Is the gross margin high enough for that revenue to be profitable after costs?"
    ],
    "correctIndex": 3,
    "explanation": "ROAS needs margin context."
  },
  {
    "question": "What does last-click attribution undervalue?",
    "options": [
      "Email",
      "Earlier touches that created awareness or consideration",
      "Direct",
      "The final touch"
    ],
    "correctIndex": 1,
    "explanation": "Compare models and test incrementality."
  },
  {
    "question": "When is an A/B test result safe to act on?",
    "options": [
      "When the boss agrees",
      "As soon as B leads",
      "After a day",
      "When it ran for the planned sample size and duration, with a significant and meaningful difference"
    ],
    "correctIndex": 3,
    "explanation": "Peeking inflates false positives."
  },
  {
    "question": "Why is a statistically significant lift not always worth shipping?",
    "options": [
      "Always ship",
      "It might be too small to matter for the business or cost more than it earns",
      "Never",
      "Significance is false"
    ],
    "correctIndex": 1,
    "explanation": "Consider effect size."
  },
  {
    "question": "What does keyword intent tell you?",
    "options": [
      "Rank",
      "Cost",
      "Volume",
      "What the searcher wants to achieve, which should shape the content or offer"
    ],
    "correctIndex": 3,
    "explanation": "Match content to intent."
  },
  {
    "question": "How should you handle consent for marketing tracking?",
    "options": [
      "Collect clear, informed, revocable consent and honour it in your tags (CMP)",
      "Hide",
      "Ignore",
      "Pre-tick"
    ],
    "correctIndex": 0,
    "explanation": "Privacy law and trust."
  },
  {
    "question": "Which email metric has become less reliable and why?",
    "options": [
      "Open rate, because mail privacy features load images automatically",
      "Unsubscribe",
      "Bounce",
      "Click rate"
    ],
    "correctIndex": 0,
    "explanation": "Prefer clicks and conversions."
  },
  {
    "question": "What is the lowest-risk way to grow an owned audience?",
    "options": [
      "Spam",
      "Buy lists",
      "Scrape",
      "Offer genuine value for a signup and collect permission (email, SMS)"
    ],
    "correctIndex": 3,
    "explanation": "Owned channels are resilient."
  },
  {
    "question": "What does incrementality testing measure?",
    "options": [
      "Clicks",
      "Impressions",
      "Reach",
      "The causal lift in outcomes from marketing versus a control that did not see it"
    ],
    "correctIndex": 3,
    "explanation": "It avoids over-crediting."
  },
  {
    "question": "What is a sound way to split a small test budget?",
    "options": [
      "All in",
      "One idea",
      "Test a few distinct ideas, cut losers early and scale winners",
      "Spread thin"
    ],
    "correctIndex": 2,
    "explanation": "Learn quickly."
  },
  {
    "question": "What does an annual marketing plan need beyond a channel list?",
    "options": [
      "Fonts",
      "Slogans",
      "Goals, budget, calendar, measurement plan and a review cadence",
      "Logos"
    ],
    "correctIndex": 2,
    "explanation": "Plans are for decisions."
  },
  {
    "question": "What shows marketing results to leadership best?",
    "options": [
      "Screenshots",
      "Impressions",
      "Outcomes against goals with insights and recommended actions",
      "Activity lists"
    ],
    "correctIndex": 2,
    "explanation": "Tie to business results."
  }
]
</script>

## Coding challenges

Try these on your own computer, then compare your output. Nothing you write is sent anywhere.

### A campaign performance report with a reallocated budget

Parse UTM tags from landing URLs, compute CTR, CPC, conversion rate, CPA and ROAS per campaign, label each (scale, keep, fix or pause), compute blended ROAS and propose a rebalanced budget in proportion to ROAS with a +/-50% cap per campaign. The data are made-up illustrative numbers; real budgets also depend on margin, learning phases and incrementality.

**Starter code**

```python
from urllib.parse import urlparse, parse_qs

# illustrative campaign data: (landing URL with UTMs, spend, impressions, clicks, conversions, revenue)
rows = [
    ("https://shop.example/a?utm_source=google&utm_medium=cpc&utm_campaign=brand", 400, 20000, 1400, 70, 5600),
    ("https://shop.example/a?utm_source=google&utm_medium=cpc&utm_campaign=generic", 900, 90000, 1800, 45, 3150),
    ("https://shop.example/b?utm_source=meta&utm_medium=paid_social&utm_campaign=lookalike", 600, 150000, 1500, 36, 3240),
    ("https://shop.example/c?utm_source=newsletter&utm_medium=email&utm_campaign=spring", 50, 8000, 640, 48, 4320),
    ("https://shop.example/d?utm_source=influencer&utm_medium=social&utm_campaign=creator1", 300, 60000, 500, 6, 480),
]

# TODO: campaign(url) -> (utm_source, utm_medium, utm_campaign) using urlparse and parse_qs
# TODO: metrics(spend, impr, clicks, conv, revenue) -> ctr %, cpc, cvr % (conversions per click), cpa, roas
# TODO: print a table sorted by ROAS (high first) with the action: "scale" if ROAS >= 4, "keep" if >= 2, otherwise "fix or pause"
# TODO: blended ROAS and total spend
# TODO: propose a new budget with the same total, in proportion to ROAS, but never moving a campaign more than -50%/+50% from its current spend
#       (cap, then rescale so the total matches; round to whole numbers), and the spend by medium
```

**Expected output**

```text
campaign    ctr%   cpc  cvr%    cpa  roas  action
spring      8.00  0.08   7.5   1.04 86.40  scale
brand       7.00  0.29   5.0   5.71 14.00  scale
lookalike   1.00  0.40   2.4  16.67  5.40  scale
generic     2.00  0.50   2.5  20.00  3.50  keep
creator1    0.83  0.60   1.2  50.00  1.60  fix or pause
blended ROAS 7.46 on spend 2250
proposed budget: {'brand': 508, 'creator1': 268, 'generic': 804, 'lookalike': 536, 'spring': 134} total 2250
spend by medium: {'cpc': 1300, 'email': 50, 'paid_social': 600, 'social': 300}
```

<details><summary>Show solution and explanation</summary>

<pre><code>from urllib.parse import urlparse, parse_qs

# illustrative campaign data: (landing URL with UTMs, spend, impressions, clicks, conversions, revenue)
rows = [
    (&quot;https://shop.example/a?utm_source=google&amp;utm_medium=cpc&amp;utm_campaign=brand&quot;, 400, 20000, 1400, 70, 5600),
    (&quot;https://shop.example/a?utm_source=google&amp;utm_medium=cpc&amp;utm_campaign=generic&quot;, 900, 90000, 1800, 45, 3150),
    (&quot;https://shop.example/b?utm_source=meta&amp;utm_medium=paid_social&amp;utm_campaign=lookalike&quot;, 600, 150000, 1500, 36, 3240),
    (&quot;https://shop.example/c?utm_source=newsletter&amp;utm_medium=email&amp;utm_campaign=spring&quot;, 50, 8000, 640, 48, 4320),
    (&quot;https://shop.example/d?utm_source=influencer&amp;utm_medium=social&amp;utm_campaign=creator1&quot;, 300, 60000, 500, 6, 480),
]

def campaign(url):
    q = parse_qs(urlparse(url).query)
    return q[&quot;utm_source&quot;][0], q[&quot;utm_medium&quot;][0], q[&quot;utm_campaign&quot;][0]

def metrics(spend, impr, clicks, conv, revenue):
    return {
        &quot;ctr&quot;: 100 * clicks / impr,
        &quot;cpc&quot;: spend / clicks,
        &quot;cvr&quot;: 100 * conv / clicks,
        &quot;cpa&quot;: spend / conv,
        &quot;roas&quot;: revenue / spend,
    }

report = []
for url, *vals in rows:
    src, med, camp = campaign(url)
    m = metrics(*vals)
    report.append((camp, src, med, vals[0], m))

print(f&quot;{&#x27;campaign&#x27;:10} {&#x27;ctr%&#x27;:&gt;5} {&#x27;cpc&#x27;:&gt;5} {&#x27;cvr%&#x27;:&gt;5} {&#x27;cpa&#x27;:&gt;6} {&#x27;roas&#x27;:&gt;5}  action&quot;)
for camp, src, med, spend, m in sorted(report, key=lambda r: -r[4][&quot;roas&quot;]):
    action = &quot;scale&quot; if m[&quot;roas&quot;] &gt;= 4 else &quot;keep&quot; if m[&quot;roas&quot;] &gt;= 2 else &quot;fix or pause&quot;
    print(f&quot;{camp:10} {m[&#x27;ctr&#x27;]:5.2f} {m[&#x27;cpc&#x27;]:5.2f} {m[&#x27;cvr&#x27;]:5.1f} {m[&#x27;cpa&#x27;]:6.2f} {m[&#x27;roas&#x27;]:5.2f}  {action}&quot;)

total_spend = sum(r[3] for r in report)
total_rev = sum(v[-1] for _, *v in rows)
print(f&quot;blended ROAS {total_rev / total_spend:.2f} on spend {total_spend}&quot;)

# reallocate the same total budget in proportion to ROAS, capping any campaign at +/-50% of its current spend
roas = {r[0]: r[4][&quot;roas&quot;] for r in report}
spend = {r[0]: r[3] for r in report}
weights = {c: roas[c] for c in roas}
raw = {c: total_spend * weights[c] / sum(weights.values()) for c in roas}
capped = {c: min(max(raw[c], spend[c] * 0.5), spend[c] * 1.5) for c in roas}
scale = total_spend / sum(capped.values())
final = {c: round(v * scale) for c, v in capped.items()}
print(&quot;proposed budget:&quot;, dict(sorted(final.items())), &quot;total&quot;, sum(final.values()))
channels = {}
for camp, src, med, sp, m in report:
    channels[med] = channels.get(med, 0) + sp
print(&quot;spend by medium:&quot;, dict(sorted(channels.items())))
</code></pre>

<p>Dividing by the right base matters (conversion rate per click, CPA per conversion). Proportional-to-ROAS reallocation with caps limits how far one noisy week can swing spend, and the final rescale keeps the total equal. Verified by running the Python solution.</p>
</details>

### A/B test significance, sample size and attribution models

Run a two-proportion z-test on two experiments, compute the visitors needed to detect a given lift and credit one customer journey under first-click, last-click, linear, position-based and time-decay attribution. Numbers are illustrative; real experiments also need a pre-registered duration and guardrail metrics.

**Starter code**

```python
from math import sqrt, ceil

# TODO: z_test(conv_a, n_a, conv_b, n_b) -> (rate_a, rate_b, z) using the pooled proportion
# TODO: sample_size(base, lift, z_alpha=1.96, z_beta=0.84) -> visitors per variant for a two-sided 5% test with 80% power (round up)
# TODO: print each test's rates, relative lift, z and verdict (|z| > 1.96 is significant) and the two sample sizes
# TODO: attribute(path, model, value=100.0) for the models first, last, linear, position (40/20/40 with the middle shared) and time_decay
#       (each earlier touch worth half the next one); credits summed per channel, rounded to 1 decimal
journey = ["search", "email", "social", "search", "email"]
```

**Expected output**

```text
headline test: 4.0% vs 5.0% (lift +25%), z=2.41, significant
button colour: 4.5% vs 4.8% (lift +6%), z=0.53, not significant
visitors per variant to detect +10% on a 3% base: 53151
visitors per variant to detect +25% on a 3% base: 9090
first      {'email': 0.0, 'search': 100.0, 'social': 0.0}
last       {'email': 100.0, 'search': 0.0, 'social': 0.0}
linear     {'email': 40.0, 'search': 40.0, 'social': 20.0}
position   {'email': 46.7, 'search': 46.7, 'social': 6.7}
time_decay {'email': 58.1, 'search': 29.0, 'social': 12.9}
```

<details><summary>Show solution and explanation</summary>

<pre><code>from math import sqrt, ceil

def z_test(conv_a, n_a, conv_b, n_b):
    pa, pb = conv_a / n_a, conv_b / n_b
    p = (conv_a + conv_b) / (n_a + n_b)
    se = sqrt(p * (1 - p) * (1 / n_a + 1 / n_b))
    return pa, pb, (pb - pa) / se

def sample_size(base, lift, z_alpha=1.96, z_beta=0.84):
    &quot;&quot;&quot;visitors per variant to detect a relative lift (two-sided 5% alpha, 80% power)&quot;&quot;&quot;
    p1, p2 = base, base * (1 + lift)
    pbar = (p1 + p2) / 2
    return ceil(((z_alpha * sqrt(2 * pbar * (1 - pbar)) + z_beta * sqrt(p1 * (1 - p1) + p2 * (1 - p2))) ** 2) / (p2 - p1) ** 2)

for name, (ca, na, cb, nb) in {&quot;headline test&quot;: (200, 5000, 250, 5000), &quot;button colour&quot;: (180, 4000, 190, 4000)}.items():
    pa, pb, z = z_test(ca, na, cb, nb)
    verdict = &quot;significant&quot; if abs(z) &gt; 1.96 else &quot;not significant&quot;
    print(f&quot;{name}: {100 * pa:.1f}% vs {100 * pb:.1f}% (lift {100 * (pb - pa) / pa:+.0f}%), z={z:.2f}, {verdict}&quot;)
print(&quot;visitors per variant to detect +10% on a 3% base:&quot;, sample_size(0.03, 0.10))
print(&quot;visitors per variant to detect +25% on a 3% base:&quot;, sample_size(0.03, 0.25))

# attribution: one journey, 100 of revenue
journey = [&quot;search&quot;, &quot;email&quot;, &quot;social&quot;, &quot;search&quot;, &quot;email&quot;]
def attribute(path, model, value=100.0):
    n = len(path)
    if model == &quot;first&quot;:
        w = [1] + [0] * (n - 1)
    elif model == &quot;last&quot;:
        w = [0] * (n - 1) + [1]
    elif model == &quot;linear&quot;:
        w = [1 / n] * n
    elif model == &quot;position&quot;:
        w = [0.4] + [0.2 / (n - 2)] * (n - 2) + [0.4] if n &gt; 2 else [0.5] * n
    elif model == &quot;time_decay&quot;:
        raw = [0.5 ** (n - 1 - i) for i in range(n)]
        w = [r / sum(raw) for r in raw]
    credit = {}
    for ch, wi in zip(path, w):
        credit[ch] = credit.get(ch, 0) + wi * value
    return {k: round(v, 1) for k, v in sorted(credit.items())}
for m in [&quot;first&quot;, &quot;last&quot;, &quot;linear&quot;, &quot;position&quot;, &quot;time_decay&quot;]:
    print(f&quot;{m:10}&quot;, attribute(journey, m))
</code></pre>

<p>The headline test clears the 1.96 threshold, the button test does not, and detecting a small lift needs far more traffic than a large one. Each attribution model tells a different story about the same journey, which is why you compare them and test incrementality. Verified by running the Python solution.</p>
</details>
