---
description: "SEO at Scale & International SEO — Large sites — marketplaces, publishers, SaaS, multi-city services — face SEO problems small sites never see: millions…"
---

# 03 · SEO at Scale & International SEO

Large sites — marketplaces, publishers, SaaS, multi-city services — face SEO problems small sites never see: millions of URLs, duplicate content, crawl budget and multiple languages or countries. This module covers SEO for sites at scale.

## 1. Programmatic and templated pages

1. Many large sites generate pages from data: city × service ("Plumbers in Indore"), product listings, comparison pages.
2. Each page must offer **unique value**: real listings, prices, reviews, local data, availability. Thin templated pages with only the city name swapped risk being treated as scaled spam.
3. Set quality thresholds: don't index pages with fewer than N real results; noindex or consolidate empty combinations.
4. Monitor index coverage and traffic by template, not page by page.

## 2. Crawl budget and architecture

1. Control **faceted navigation** (filters like colour, size, price): canonicalise, noindex or block parameter combinations that create near-infinite URLs.
2. Strong internal linking from category hubs; avoid orphan pages.
3. XML sitemaps split by type and kept clean; use `lastmod` accurately.
4. **Log file analysis** shows which URLs Googlebot actually crawls — find wasted crawling on junk URLs.
5. Keep server response fast; errors and slow responses reduce crawling.

## 3. International and multilingual SEO

1. Choose a URL structure: **ccTLDs** (example.in, example.ae — strong country signal, more cost), **subdirectories** (example.com/in/, /ae/ — easiest to build authority), or subdomains.
2. Implement **hreflang** to tell Google which version serves which language/region: `<link rel="alternate" hreflang="en-in" href="https://example.com/in/" />`, plus `hi-in`, `en-ae` and an `x-default`. Every page must reference all alternates, including itself, reciprocally.
3. Translate and **localise**: currency, units, local examples, local keyword research (people in India may search "mobile cover", in the UK "phone case").
4. Indian languages: Hindi, Tamil, Telugu and other language pages can capture large, less competitive demand — use native speakers, not raw machine translation.
5. Don't auto-redirect users by IP without letting them switch; Google mostly crawls from US IPs.

## 4. Governance at scale

1. SEO requirements in the product development process (URLs, canonicals, rendering, schema) — fixing after launch costs more.
2. Automated monitoring: alerts for robots.txt changes, sudden noindex, traffic drops by template, Core Web Vitals regressions.
3. Migration playbooks: URL mapping, 301 redirects, benchmark before/after, staged rollout.

## Cheat sheet

| Problem | Solution |
|---|---|
| Thin templated pages | Unique data, quality thresholds, noindex empties |
| Faceted URL explosion | Canonicals, noindex, parameter control |
| Wasted crawling | Log analysis, clean sitemaps |
| Multiple countries | ccTLD / subfolder + hreflang |
| Multiple languages | Native localisation, local keywords |
| Big changes | Migration playbook + monitoring |

## How It Actually Works

At scale, SEO becomes a systems problem: Google must decide which of your millions of URLs deserve crawling, indexing and ranking, and it does so based on signals aggregated across templates and the whole site. A few low-quality templates can drag down perception of the site, while clean architecture concentrates crawling and link equity on valuable pages. Hreflang doesn't make a page rank; it helps Google swap the right language or regional version into results once the site already ranks.

## Exercise

For a multi-city service business, design the URL structure, page template (unique data blocks), indexing rules for low-inventory cities and an internal linking plan. Then write hreflang tags for an English-India, Hindi-India and English-UAE version of one page with an x-default.
