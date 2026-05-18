# Ads Manager Updates

> **Source:** Jon Loomer | **Last Updated:** 2026-05-18 | **Status:** Complete

---

## What It Is

A living tracker of significant Meta Ads Manager changes. Meta constantly updates the platform — features move, get renamed, or disappear. This SOP tracks recent changes and provides context for navigating them.

## Why It Matters

Panicking when the UI changes wastes time. Core advertising concepts remain stable even as the interface evolves. Knowing what changed and why helps you adapt quickly.

## How It Works

### Recent Notable Changes (as of May 2026)

- **Meta Ads AI Connectors (open beta):** Allows advertisers to manage campaigns through third-party AI agents (ChatGPT, Claude, etc.) using the MCP standard. Connect by adding `mcp.facebook.com/ads` as a custom connector and signing in with your Meta account — no developer credentials or coding required. Supports four capabilities: reporting/insights, campaign creation and editing, product catalog management, and signal/CAPI diagnostics. Access is not yet universal. Jon Loomer recommends caution — prior unapproved AI integrations triggered account shutdowns; wait until you're comfortable before implementing
- **Purchase Audience Retention Expanded to 730 Days:** Starting May 18, 2026, website/app activity custom audiences based on purchase events can be retained for up to 730 days (previously 180 days). Existing 180-day purchase audiences auto-update to 730 days on that date — opt out in Audience Manager beforehand if needed
- **Higher-Quality Clicks for Link Click / Landing Page View Optimizations:** Meta's documentation now states it "may prioritize higher-quality clicks" when optimizing for link clicks or landing page views. These optimizations have historically driven low-quality traffic via Audience Network — this signals an intent to improve that
- **One-Click CAPI Now Active:** One-Click Conversions API has begun activating automatically for eligible accounts in Events Manager. If web CAPI previously failed to connect, try again — it may now be live. No-cost, no developer, no ongoing maintenance required
- **AI Translations (New):** In the ad creation flow, you can now select up to 12 languages for automatic translation of all ad creatives and text, including text on images. All 12 languages are selected by default — deselect individually if needed. Option exists to translate the full ad or only specific parts. Treat as experimental; review output for sensitive or brand-critical copy
- **Live Video Ads (New):** Under Budget & Schedule, you can now choose to promote a current live video or an upcoming live video. For a current live video, select an existing post featuring the live broadcast under Ad Setup
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

---

*Part of the [Meta Ads SOP Library](../README.md) — built from Jon Loomer's free content.*
