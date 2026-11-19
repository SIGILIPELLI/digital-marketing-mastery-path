---
description: "Technical SEO — Great content can't rank if search engines can't crawl, index and load it properly. Technical SEO is the plumbing: site speed, mobile…"
---

# 01 · Technical SEO

Great content can't rank if search engines can't crawl, index and load it properly. Technical SEO is the plumbing: site speed, mobile experience, indexing rules, site structure and errors. This module gives you a repeatable technical audit.

## 1. Crawling and indexing controls

1. **robots.txt** (at `yoursite.com/robots.txt`) tells crawlers which paths not to crawl. Never block CSS/JS or important pages by mistake; a stray `Disallow: /` hides the whole site.
2. **Meta robots `noindex`** keeps a page out of the index (use for thank-you pages, internal search results, admin pages). Note: a page blocked in robots.txt can't be read, so Google won't see its noindex tag.
3. **XML sitemap** lists the pages you want indexed; submit it in Search Console and keep it free of redirected or noindexed URLs.
4. **Canonical tags** (`<link rel="canonical" href="...">`) tell Google which URL is the main version when similar pages exist (e.g. product pages with sort/filter parameters).
5. Check **Search Console → Pages** for reasons like "Crawled – currently not indexed", "Duplicate without user-selected canonical", or "Blocked by robots.txt".

## 2. Speed and Core Web Vitals

1. Google's **Core Web Vitals** measure real-user experience: **LCP** (Largest Contentful Paint — main content loads; good ≤ 2.5 s), **INP** (Interaction to Next Paint — responsiveness; good ≤ 200 ms) and **CLS** (Cumulative Layout Shift — visual stability; good ≤ 0.1).
2. See field data in **Search Console → Core Web Vitals** and per page at **pagespeed.web.dev**.
3. Common fixes: compress and resize images (WebP/AVIF), lazy-load below-the-fold images, reduce heavy plugins and third-party scripts, use caching and a CDN, set image width/height to stop layout shifts, choose fast hosting.

## 3. Site structure and URLs

1. Keep important pages within **three clicks** of the home page.
2. Use logical folders: `/services/office-catering/`, `/blog/office-snack-ideas/`.
3. Add **breadcrumbs** (with BreadcrumbList schema) on deeper pages.
4. Use **301 redirects** when you change a URL so links and rankings transfer; avoid redirect chains.
5. Fix **404 errors** for pages that have links pointing to them (redirect to the closest relevant page).
6. Ensure the site uses **HTTPS** everywhere and one preferred version (with or without www).

## 4. A simple technical audit

1. Crawl the site with **Screaming Frog SEO Spider** (free up to 500 URLs) to list status codes, missing titles, duplicate titles, broken links and redirect chains.
2. Check mobile rendering with Search Console's URL inspection (view the crawled page screenshot).
3. Review Core Web Vitals and PageSpeed for the five most important templates (home, service, product, article, contact).
4. Prioritise fixes by impact: indexing blockers first, then speed on key templates, then structure and minor errors.

## Cheat sheet

| Issue | Tool | Fix |
|---|---|---|
| Not indexed | Search Console → Pages | Remove noindex/robots block, add internal links |
| Duplicates | Canonical tags | Point variants to the main URL |
| Slow LCP | PageSpeed Insights | Compress hero image, cache, CDN |
| Layout shift | PageSpeed (CLS) | Set image dimensions, reserve ad space |
| Broken links | Screaming Frog | 301 redirect or update links |
| Changed URL | Server/CMS | 301 redirect, update sitemap |

## How It Actually Works

Google allocates each site a crawl budget roughly proportional to its size, health and popularity, then renders pages in a headless browser to see content loaded by JavaScript. Errors, endless parameter URLs and slow servers waste that budget and delay discovery of new pages. Core Web Vitals come from the **Chrome User Experience Report** — real visits by Chrome users — so lab tests only predict them; improvements show up in Search Console after enough real traffic over the following weeks.

## Exercise

Run a technical audit on a site you control (or a friend's small business site): crawl with Screaming Frog, check Search Console's Pages and Core Web Vitals reports, and test three page templates in PageSpeed Insights. Produce a prioritised list of 10 issues with the fix for each.
