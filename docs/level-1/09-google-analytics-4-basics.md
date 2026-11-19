---
description: "Google Analytics 4 Basics — Google Analytics 4 (GA4) shows who visits your website, where they came from and what they do. Without measurement, you can't…"
---

# 09 · Google Analytics 4 Basics

**Google Analytics 4 (GA4)** shows who visits your website, where they came from and what they do. Without measurement, you can't tell which channel or campaign is working. This module sets up GA4 and teaches the reports you'll use weekly.

## 1. Create a property and install the tag

1. Go to **analytics.google.com**, create an account, then a **GA4 property** (set your country and currency, e.g. India, INR).
2. Create a **Web data stream** for your website URL. GA4 gives you a **Measurement ID** (`G-XXXXXXX`).
3. Install the tag: in WordPress use the **Site Kit by Google** plugin; in Wix/Shopify paste the Measurement ID in the analytics settings; or add the Google tag snippet to every page's `<head>`. **Google Tag Manager** is the flexible option for later.
4. Keep **Enhanced measurement** on — it automatically tracks page views, scrolls, outbound clicks, site search, video engagement and file downloads.
5. Open **Reports → Realtime** and visit your site from your phone; you should appear within a minute.

## 2. The reports you'll use

1. **Reports → Acquisition → Traffic acquisition** — sessions by channel: Organic Search, Direct, Paid Search, Organic Social, Referral, Email.
2. **Reports → Engagement → Pages and screens** — which pages get views and how long people engage.
3. **Reports → User attributes / Tech** — country, city, device (mobile vs desktop).
4. **Engagement rate** — share of sessions that lasted over 10 seconds, viewed 2+ pages, or triggered a conversion. It replaced "bounce rate" as the main quality signal (bounce rate = the opposite).
5. Set the date range (top right) and compare to the previous period to spot trends.

## 3. Key events (conversions)

1. GA4 is event-based: every interaction is an **event**.
2. Mark the actions that matter as **key events** (Admin → Events → mark as key event), e.g. `generate_lead` when the catering form is submitted or the thank-you page loads.
3. A simple no-code method: create an event that fires when the page path contains `/thank-you` (Admin → Events → Create event), then mark it as a key event.
4. Now Traffic acquisition shows key events per channel — which sources bring enquiries, not just visits.

## 4. Privacy and good hygiene

1. Add a privacy policy explaining analytics and cookies.
2. Exclude your own visits where possible (Admin → Data streams → Configure tag settings → Define internal traffic) so they don't skew data.
3. Link GA4 with **Search Console** and later **Google Ads** (Admin → Product links) to see search queries and ad performance in one place.
4. Data retention: set event data retention to the maximum available (Admin → Data retention) so explorations can look further back.

## Cheat sheet

| Task | Where |
|---|---|
| Measurement ID | Admin → Data streams |
| Live check | Reports → Realtime |
| Channels | Acquisition → Traffic acquisition |
| Top pages | Engagement → Pages and screens |
| Mark conversions | Admin → Events → key event |
| Link Search Console / Ads | Admin → Product links |
| Exclude own traffic | Data stream → tag settings → internal traffic |

## How It Actually Works

When a page loads, the Google tag sends small event messages (page_view, scroll, click) with an anonymous identifier stored in a first-party cookie, plus information like the referring site and campaign parameters. GA4 groups these events into sessions and users, then assigns each session to a **channel** using rules about the source and medium (for example, a visit from google.com without ad parameters is Organic Search). Because cookies can be blocked or cleared and some users decline consent, analytics is a strong directional signal rather than a perfect count — compare trends and ratios, not single numbers.

## Exercise

Install GA4 on a site you control, confirm your visit in Realtime, and create a key event for a thank-you page or form submission. After a week, write down sessions by channel, the top five pages, mobile vs desktop share, and engagement rate.
