# Ads Manager Updates

> **Source:** Jon Loomer | **Last Updated:** 2026-06-29 | **Status:** Complete

---

## What It Is

A living tracker of significant Meta Ads Manager changes. Meta constantly updates the platform — features move, get renamed, or disappear. This SOP tracks recent changes and provides context for navigating them.

## Why It Matters

Panicking when the UI changes wastes time. Core advertising concepts remain stable even as the interface evolves. Knowing what changed and why helps you adapt quickly.

## How It Works

### Recent Notable Changes (as of June 2026)

- **Embedded Appointment Booking for Lead Ads (June 2026):** After submitting an Instant Form, prospects can now book an appointment without leaving the app. The scheduling partner's calendar loads directly inside the Instant Form Thank You page, with contact details carried over automatically. Setup: in the Instant Form editor, select the booking CTA and paste your scheduling link — Meta auto-detects the calendar provider. Supported at launch: Calendly and HighLevel; HubSpot support coming August 2026. Rollout is staged — not all accounts have access yet. Most impactful for service businesses (local, B2B, health, real estate) that rely on booked appointments as the primary conversion event
- **ChatGPT Ads Conversion Optimization (June 2026):** ChatGPT ads now support conversion-optimized campaigns. Previously, the platform could only track conversions, not optimize delivery toward them — a major limitation. Accounts with a Pixel or Conversions API configured received early access starting June 5th, with broader rollout through June 25th. If you're running ChatGPT ads and haven't checked this yet, verify your conversion event setup in the OpenAI Ads dashboard. This changes the calculus on whether ChatGPT ads can be a performance channel rather than just a brand/awareness play
- **AI Disclosure Checkbox (June 2026):** A checkbox now appears above the primary text field when creating an ad. If your ad includes media created or edited with AI (Meta's tools or third-party tools like DALL·E, Photoshop AI), check this box — it may add an "AI Info" label visible to viewers. Meta also uses automated detection to add labels regardless, so missing the checkbox doesn't avoid disclosure. Advertisers running in California, New York, India, or Taiwan should treat this as required. The checkbox is easy to miss due to its small footprint in the UI — build checking it into your ad creation workflow
- **Creative Testing Tool Limit Expanding (June 2026):** Official docs state a maximum of 5 ads per Creative Testing test, but some advertisers now report seeing options for up to 7 or 10. Rollout is gradual — check what your account allows

- **Push Delivery to This Ad (June 2026):** When a published ad is getting limited or no spend within an ad set, Meta now shows an alert and offers a "Push Delivery to This Ad" option. This lets you dedicate a specific percentage of your campaign or ad set budget to that ad for a defined period. Duration range: 1–30 days (the UI suggests 7 days, but that's a recommendation, not a hard cap). Caution: pushing to more than one ad simultaneously risks delivery issues and minimum per-ad spend may not be met. After the push period, delivery reverts to normal algorithmic distribution. Rollout is still incomplete — not all accounts have access yet
- **Post-View Reels Ads (June 2026, Global Rollout):** A new ad placement that drops between organic Reels clips. Ads auto-play but only appear in Reels longer than 60 seconds. Viewers see a 5-second countdown before a skip button appears; skipping returns them to the original Reel. Now available to all advertisers globally. Eligible via Advantage+ Placements — no manual opt-in required. Provide 9x16 creative to ensure correct formatting in this placement

- **Grouping Reports (New, May 2026):** A new Grouping feature now appears next to the Breakdowns menu in Ads Manager (campaigns and ad sets view). Unlike Breakdowns — which splits each item into rows per variable value — Grouping rolls up campaigns or ad sets that share the same variable value into a single aggregated row. Four variable categories: Ad Settings, Attribution, Budget and Bidding, Business Goals. Useful for comparing performance across structurally similar campaigns without manual filtering. Not yet available to all accounts
- **Meta Ads AI Connectors (open beta):** Allows advertisers to manage campaigns through third-party AI agents (Claude, ChatGPT, and Perplexity) using the MCP standard. Connect by adding `mcp.facebook.com/ads` as a custom connector and signing in with your Meta account — no developer credentials or coding required. Supports four capabilities: reporting/insights, campaign creation and editing, product catalog management, and signal/CAPI diagnostics. Access is not yet universal. Jon Loomer recommends caution — prior unapproved AI integrations triggered account shutdowns; wait until you're comfortable before implementing
- **Purchase Audience Retention Expanded to 730 Days:** Starting May 18, 2026, website/app activity custom audiences based on purchase events can be retained for up to 730 days (previously 180 days). Existing 180-day purchase audiences auto-update to 730 days on that date — opt out in Audience Manager beforehand if needed
- **Higher-Quality Clicks for Link Click / Landing Page View Optimizations:** Meta's documentation now states it "may prioritize higher-quality clicks" when optimizing for link clicks or landing page views. These optimizations have historically driven low-quality traffic via Audience Network — this signals an intent to improve that
- **One-Click CAPI Now Active:** One-Click Conversions API has begun activating automatically for eligible accounts in Events Manager. If web CAPI previously failed to connect, try again — it may now be live. No-cost, no developer, no ongoing maintenance required
- **AI Translations (New):** In the ad creation flow, you can now select up to 12 languages for automatic translation of all ad creatives and text, including text on images. All 12 languages are selected by default — deselect individually if needed. Option exists to translate the full ad or only specific parts. Treat as experimental; review output for sensitive or brand-critical copy
- **AI Instant Form Generation (May 2026):** Meta can now auto-generate an Instant Form from a website URL or short text prompt. Enter your landing page URL and Meta drafts the form structure — questions, value props, and qualifiers — in seconds. Useful for quick lead gen setup; treat output as a first draft and edit before publishing, especially for brand voice and complex qualifiers
- **Pixel Collection Controls (May 2026):** A new Events Manager setting lets advertisers control whether the Pixel automatically collects expanded page and product data (product names, prices, availability, page metadata, business details). May be enabled by default on some accounts. Audit your Events Manager settings — this affects what data is shared with Meta and should align with your privacy policy
- **Live Video Ads (New):** Under Budget & Schedule, you can now choose to promote a current live video or an upcoming live video. For a current live video, select an existing post featuring the live broadcast under Ad Setup. Supports any available performance goal — including optimizing for purchases. For an upcoming live video, set a start and end date/time so ads run in sync with your broadcast. Useful for events, product launches, and live Q&As that benefit from paid amplification
- **Pixel Upgrades:** Enhanced tracking capabilities and setup flow
- **Value Rules Reorganized:** Value Rules are now categorized into Conversion Location (Website, App, Instant Forms) and Placements. You can now add and configure Value Rules directly from the Placements section of the ad set — not just from campaign settings
- **Dynamic Creative Changes:** Evolution of the Dynamic Creative feature into Flexible Format
- **Expanded Audience Labels:** Clearer labeling of how Advantage+ Audience works
- **Breakdowns Restored for Conversions:** Previously removed breakdown options for conversion reporting brought back
- **Existing Customer Budget Cap Removed:** No longer available in Advantage+ Shopping/Sales Campaigns
- **6-Ad Recommendation Removed:** Meta no longer suggests a maximum of 6 ads per ad set
- **Meta AI Business Assistant:** New AI-powered assistant for advertiser support

### How to Stay Current
1. Follow Loomer's blog — weekly "Advertiser Field Notes" posts cover all significant changes
2. Check Ads Manager release notes in the platform
3. Don't panic when things move — search for the feature name to find its new location
4. Core concepts (attribution, targeting, creative) remain stable across UI changes

## Common Mistakes

- Assuming a UI change means a strategy change is needed
- Not reading update announcements and missing new features (like Value Rules)
- Following outdated tutorials that reference removed features
- Ignoring new features that could improve results (one-click CAPI, Flexible Format)

## How to Apply It

- Bookmark Loomer's blog for weekly updates
- When you notice something different in Ads Manager, check the Field Notes before troubleshooting
- Test new features when they launch rather than waiting months
- Update your SOPs when platform changes affect a specific topic

## When to Make Exceptions

- Major platform overhauls may require strategy adjustment (rare — last was the Advantage+ rollout)
- New features in beta may not be stable enough for production campaigns

## Related SOPs

- [Conversion Tracking](../04-measurement-reporting/conversion-tracking.md)
- [Value Rules](../01-campaign-strategy-structure/value-rules.md)
- [Meta Andromeda](../03-creative-ads/meta-andromeda.md)

## Sources

- [Jon Loomer Blog — Weekly Field Notes](https://www.jonloomer.com/blog/)
- [One-Click Conversions API, Pixel Updates, and More](https://www.jonloomer.com/one-click-conversions-api-pixel-updates/)
- [Meta AI Business Assistant and Tracking Updates](https://www.jonloomer.com/meta-ai-business-assistant/)
- [Ads Manager Changes](https://www.jonloomer.com/facebook-ads-manager-changes/)
- [Meta Ads AI Connectors, App Usage Drops, and More](https://www.jonloomer.com/meta-ads-ai-connectors/)
- [Meta Ads AI Connectors and Claude: Setup, Uses, and Risks](https://www.jonloomer.com/meta-ads-ai-connectors-claude/)
- [ChatGPT Ads Go Self-Serve, Purchase Retention Expands, and More](https://www.jonloomer.com/chatgpt-ads-self-serve/)
- [One-Click CAPI Activated, New Meta Ads Features, and More](https://www.jonloomer.com/one-click-capi-activated-new-meta-ads-features/)
- [The Future of the Meta Advertiser](https://www.jonloomer.com/future-of-meta-advertiser/)
- [Hands-On With ChatGPT Ads: Initial Impressions](https://www.jonloomer.com/chatgpt-ads-initial-impressions/)
- [Meta Ads Grouping Reports, ChatGPT Conversions, and More](https://www.jonloomer.com/meta-ads-grouping-reports-chatgpt-conversions/)
- [Hands-On With Push Delivery to This Ad](https://www.jonloomer.com/hands-on-push-delivery-to-this-ad/)
- ["Push Delivery to This Ad" (Plus 4 Updates)](https://www.jonloomer.com/push-delivery-to-this-ad/)
- [AI Disclosure Checkbox, ChatGPT Attribution, and More](https://www.jonloomer.com/ai-disclosure-checkbox-chatgpt-attribution/)
- [How Many Meta Ads Campaigns Should You Have at Once?](https://www.jonloomer.com/how-many-meta-ads-campaigns/)
- [Meta Launches Embedded Appointment Booking for Lead Ads](https://www.socialmediatoday.com/news/meta-launches-integrated-booking-for-lead-ads/823711/)
- [Jon Loomer Blog — Advertiser Field Notes (June 25, 2026)](https://www.jonloomer.com/blog/)

---

*Part of the [Meta Ads SOP Library](../README.md) — built from Jon Loomer's free content.*
