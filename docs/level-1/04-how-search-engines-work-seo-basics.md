---
description: "How Search Engines Work (SEO Basics) — SEO (search engine optimisation) is making your pages easy for search engines to find, understand and trust, so…"
---

# 04 · How Search Engines Work (SEO Basics)

**SEO (search engine optimisation)** is making your pages easy for search engines to find, understand and trust, so they appear when people search. This module explains how Google decides what to show, and sets up the free tool every SEO uses: **Google Search Console**.

## 1. Crawl, index, rank

1. **Crawling** — Googlebot follows links and sitemaps to discover pages.
2. **Indexing** — Google reads each page (text, headings, images, structured data) and stores it in its index. A page that isn't indexed can never rank.
3. **Ranking** — for each search, Google orders indexed pages by hundreds of signals: relevance to the query, quality and helpfulness of the content, links from other sites, page experience (speed, mobile, HTTPS), freshness and location.
4. **Serving** — results appear as blue links, plus features like the map pack, images, videos, "People also ask" and AI-generated overviews.

## 2. The three pillars of SEO

1. **Technical SEO** — can Google crawl and index the site? Fast, mobile-friendly, secure (HTTPS), no broken pages (Level 2, Module 1).
2. **On-page SEO / content** — does each page clearly answer a search? Titles, headings, useful content (Module 6).
3. **Off-page / authority** — do other trustworthy sites link to and mention you? Reviews and citations matter for local businesses (Level 3, Module 1).

## 3. Search intent

1. **Informational** — "how to make masala chai". Wants an answer or guide.
2. **Navigational** — "Chai Corner Baner". Wants a specific site.
3. **Commercial** — "best catering for office in Pune". Comparing options.
4. **Transactional / local** — "order samosa near me". Ready to act.
5. Look at the current top results for a search: if they're all guides, a sales page won't rank; if they're all local listings, you need a Google Business Profile. **Match the intent** of what already ranks.

## 4. Set up Google Search Console

1. Go to **search.google.com/search-console** and add a property. Choose **Domain** (covers all versions of your site) and verify with a DNS TXT record at your domain provider, or choose **URL prefix** and verify with an HTML tag.
2. Submit your XML sitemap under **Indexing → Sitemaps** (most CMSs create one at `/sitemap.xml`).
3. Use **URL inspection** to check if a page is indexed and to request indexing for new pages.
4. After a few days, open **Performance**: queries people used, impressions, clicks, CTR and average position.
5. Check **Pages** (indexing report) for pages Google couldn't index and why.

## Cheat sheet

| Concept | What to check |
|---|---|
| Crawled? | Sitemap submitted, pages linked internally |
| Indexed? | URL inspection → "URL is on Google" |
| Relevant? | Page matches the search intent |
| Trusted? | Links, reviews, brand mentions |
| Performance | Search Console → Performance (queries, CTR, position) |
| Problems | Search Console → Pages / Experience reports |

## How It Actually Works

Google's index is an enormous inverted index — for each word and concept, a list of documents that contain it — which lets it find candidate pages for any query in milliseconds. Ranking systems then score those candidates: language models judge how well a page satisfies the meaning behind the query (not just matching words), link analysis estimates authority, and quality systems demote thin, copied or unhelpful pages. Because searchers' clicks and satisfaction feed back into how results are evaluated, the long-term SEO strategy is simple to state and hard to fake: be the most genuinely useful result for the people searching.

## Exercise

Set up Google Search Console for a site you control (a free WordPress or Blogger site is fine), submit the sitemap and inspect your home page. For five searches related to your business, note the intent type and what kind of pages rank in the top five. Write one sentence per search on what page you'd need to compete.
