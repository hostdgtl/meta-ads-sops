# Conversion Reporting

> **Source:** Jon Loomer | **Last Updated:** 2026-06-08 | **Status:** Complete

---

## What It Is

How Meta reports conversions in Ads Manager. These numbers are directional estimates, not exact counts. They will rarely match your own analytics perfectly due to differences in attribution, tracking methodology, and reporting windows.

## Why It Matters

Trusting Ads Manager numbers at face value can lead to bad decisions. Understanding why numbers differ from your analytics gives you a more accurate picture of true performance and prevents over- or under-investing in campaigns.

## How It Works

1. Meta counts conversions based on your attribution setting (default: 7-day click-through, 1-day engage-through, 1-day view-through)
2. **View-through conversions**: Someone was served an impression with no click of any kind and converted within 1 day — they may have bought because of an email or organic search, not your ad
3. **Engage-through conversions**: Someone clicked a non-link element (reaction, comment, share) or watched your video for 5+ seconds, then converted within 1 day — no link click required; these too may reflect conversions driven by other marketing channels
4. **Conversion Count**: By default, Meta reports All Conversions — one person can generate multiple counted results within the attribution window. Use Breakdown by Conversion Count in reporting to see First Conversion vs. All Other Conversions rows side-by-side without changing your setting
5. Meta uses statistical modeling to estimate some conversions it can't directly observe
6. Cross-device tracking, iOS privacy changes, and cookie restrictions all create gaps
7. Compare Attribution Settings shows how results change across different windows

## Common Mistakes

- Taking Ads Manager numbers as ground truth without cross-referencing
- Not understanding that view-through and engage-through conversions can significantly inflate reported results — neither requires a link click to your site
- Not using Breakdown by Conversion Count to check if inflated results are driven by a small group of people converting repeatedly
- Panicking when Ads Manager shows different numbers than Shopify or GA4
- Not using Compare Attribution Settings to diagnose discrepancies

## How to Apply It

1. Always cross-reference Ads Manager with your own analytics (Shopify, GA4)
2. Use Compare Attribution Settings to see click-only vs. click+view results
3. If numbers seem too good, check view-through attribution — it may be inflating
4. Build a simple tracking sheet: Ads Manager results vs. actual sales, weekly
5. Use Meta's numbers for optimization direction, your own numbers for business decisions

## When to Make Exceptions

- If you have strong CAPI implementation, Meta's numbers may be closer to reality
- Brand awareness campaigns where view-through is a legitimate metric
- Well-established accounts with consistent tracking show smaller discrepancies

## Related SOPs

- [Attribution Optimization](attribution-optimization.md)
- [Conversion Tracking](conversion-tracking.md)
- [Breakdown Effect](breakdown-effect.md)

## Sources

- [Meta Ads Conversion Results](https://www.jonloomer.com/meta-ads-conversion-results/)
- [Are Ads Manager Results Too Good to Be True?](https://www.jonloomer.com/are-ads-manager-results-too-good-to-be-true/)
- [Troubleshoot Inflated Results in Meta Ads Manager](https://www.jonloomer.com/troubleshoot-inflated-results-in-meta-ads-manager/)
- [Meta Ads Attribution Reporting: What Your Results Really Mean](https://www.jonloomer.com/meta-ads-attribution-reporting/)

---

*Part of the [Meta Ads SOP Library](../README.md) — built from Jon Loomer's free content.*
