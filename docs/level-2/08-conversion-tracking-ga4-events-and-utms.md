---
description: "Conversion Tracking: GA4 Events & UTMs — If you can't tell which campaign produced a lead or sale, you can't decide where to spend. This module sets up…"
---

# 08 · Conversion Tracking: GA4 Events & UTMs

If you can't tell which campaign produced a lead or sale, you can't decide where to spend. This module sets up **UTM parameters** for every link you share and **GA4 key events** for every important action, so each rupee and hour is accountable.

## 1. UTM parameters

1. UTMs are tags added to a URL that tell GA4 where a visit came from:
   `https://chaicorner.in/office-catering?utm_source=instagram&utm_medium=social&utm_campaign=diwali_catering`
2. **utm_source** — the platform (google, instagram, newsletter, whatsapp).
3. **utm_medium** — the channel type (cpc, social, email, referral, qr).
4. **utm_campaign** — the campaign name (diwali_catering, may_offer).
5. Optional **utm_content** (which ad or link) and **utm_term** (keyword).
6. Use Google's **Campaign URL Builder** and keep a shared spreadsheet of naming rules: lowercase, underscores, consistent names.
7. Don't use UTMs on internal links within your own site — they overwrite the original source.
8. Google Ads auto-tags with `gclid` when GA4 is linked, so you don't need manual UTMs there.

## 2. Key events in GA4

1. Decide what counts: form submit (`generate_lead`), WhatsApp click, phone click, purchase, sign-up.
2. Thank-you page method: Admin → **Events → Create event**, condition `event_name = page_view` and `page_location contains /thank-you`, name it `generate_lead`, then mark it as a **key event**.
3. Click events (WhatsApp/phone buttons) are easiest with **Google Tag Manager**: create a GA4 Event tag (`whatsapp_click`) triggered by clicks on links containing `wa.me`, publish, and mark as key event.
4. E-commerce sites should send the recommended `purchase` event with value and currency (most platforms do this through their GA4 integration).
5. Test with GA4 **DebugView** and Tag Manager **Preview** before relying on the data.

## 3. Send conversions to ad platforms

1. **Google Ads**: import GA4 key events (Goals → Conversions → Import) or use the Google Ads conversion tag; set the primary conversion so bidding optimises for it.
2. **Meta**: track the same action with the Pixel/Conversions API `Lead` event.
3. Assign realistic **values** (e.g. average catering order ₹6,000 × 30% close rate = ₹1,800 per lead) so platforms can optimise for value.

## 4. Read the results

1. GA4 **Traffic acquisition** with key events shows leads by channel; add **Session campaign** as a secondary dimension to compare campaigns.
2. **Advertising → Attribution** reports show which channels contribute along the path.
3. Reconcile with reality monthly: compare GA4 leads with leads actually received in your inbox/CRM. Small gaps are normal (consent, blockers); big gaps mean broken tracking.

## Cheat sheet

| Parameter | Example |
|---|---|
| utm_source | instagram, newsletter, google |
| utm_medium | social, email, cpc, qr |
| utm_campaign | diwali_catering |
| utm_content | reel_v2, header_link |
| Key event | generate_lead, whatsapp_click, purchase |
| Testing | DebugView, Tag Manager Preview |

## How It Actually Works

When someone lands on your site, GA4 reads the referrer and URL parameters to assign the session's source, medium and campaign; UTMs simply override the guesswork with explicit labels. A key event fired during that session is credited to those values (and, in attribution reports, to earlier sessions too). Ad platforms use the same conversion signals to train their bidding models, which is why one accurate conversion definition — shared across GA4, Google Ads and Meta — is the foundation of every optimisation decision you'll make.

## Exercise

Create a UTM naming sheet and tagged links for one email, one Instagram bio link, one WhatsApp broadcast and one QR code. Set up a `generate_lead` key event (thank-you page or Tag Manager click), test it in DebugView, and document how you'll reconcile GA4 leads with real enquiries each month.
