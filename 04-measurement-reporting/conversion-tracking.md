# Conversion Tracking

> **Source:** Jon Loomer | **Last Updated:** 2026-05-25 | **Status:** Complete

---

## What It Is

The technical foundation that lets Meta track what happens after someone interacts with your ad. Built on two systems: Meta Pixel (browser-side) and Conversions API / CAPI (server-side). Without accurate tracking, the algorithm cannot optimize properly.

## Why It Matters

Every optimization decision Meta makes depends on conversion data. If your tracking is broken, incomplete, or misconfigured, Meta optimizes toward the wrong signals — wasting budget and producing unreliable results.

## How It Works

1. **Meta Pixel**: JavaScript code on your website that fires events when users take actions (ViewContent, AddToCart, Purchase, etc.)
2. **Pixel Collection Controls (May 2026):** A new setting in Events Manager lets advertisers control whether the Pixel automatically collects expanded page and product information — product names, prices, availability, page metadata, and business details visible on the page. Some accounts have this enabled by default. Meta's rationale is that richer signal helps delivery optimize more accurately, especially post-third-party-cookie. Check Events Manager to review and control this setting; don't assume it's off
3. **Conversions API (CAPI)**: Server-side tracking that sends events directly from your server to Meta, bypassing browser limitations
4. **One-Click CAPI**: A no-cost, no-developer simplified CAPI setup. As of May 2026, it has begun activating automatically for eligible accounts — check Events Manager and reconnect if previously unsuccessful
5. **Event deduplication**: When both Pixel and CAPI fire for the same event, Meta deduplicates to avoid double-counting
6. **Domain verification**: Required for proper attribution and to maintain tracking through iOS privacy restrictions

## Common Mistakes

- Having Pixel installed but not CAPI (losing data from ad blockers and iOS restrictions)
- Not deduplicating events between Pixel and CAPI (double-counting conversions)
- Using incorrect event names or misconfigured event parameters
- Not verifying that events are firing correctly in Events Manager
- Skipping domain verification
- Not reviewing Pixel Collection Controls — they may be enabled by default, collecting more data than intended for your privacy policy or compliance requirements

## How to Apply It

### Setup Checklist
1. Install Meta Pixel on all pages of your website
2. Configure standard events: ViewContent, AddToCart, InitiateCheckout, Purchase (with value and currency)
3. Set up Conversions API (use one-click CAPI if available for your platform)
4. Verify event deduplication is working in Events Manager
5. Verify your domain in Business Settings
6. Test all events using the Events Manager Test Events tool
7. Check Events Manager weekly for any errors or dropped events
8. Review Pixel Collection Controls in Events Manager — confirm the automatic page/product data collection setting matches your privacy policy and data sharing preferences

## When to Make Exceptions

- Medical/healthcare verticals may have HIPAA restrictions on pixel/CAPI data
- Some platforms don't support one-click CAPI — manual server-side implementation needed
- Privacy-first markets (EU) may require consent management before firing events

## Related SOPs

- [Conversion Reporting](conversion-reporting.md)
- [Attribution Optimization](attribution-optimization.md)
- [Ads Manager Updates](../05-diagnostics-updates/ads-manager-updates.md)

## Sources

- [Conversions for Meta Advertising Checklist](https://www.jonloomer.com/conversions-for-meta-advertising-checklist/)
- [One-Click Conversions API, Pixel Updates, and More](https://www.jonloomer.com/one-click-conversions-api-pixel-updates/)
- [One-Click CAPI Activated, New Meta Ads Features, and More](https://www.jonloomer.com/one-click-capi-activated-new-meta-ads-features/)
- [Jon Loomer Blog — Advertiser Field Notes (May 21, 2026)](https://www.jonloomer.com/blog/)

---

*Part of the [Meta Ads SOP Library](../README.md) — built from Jon Loomer's free content.*
