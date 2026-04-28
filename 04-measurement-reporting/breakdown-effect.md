# Breakdown Effect

> **Source:** Jon Loomer | **Last Updated:** 2026-04-28 | **Status:** Complete

---

## What It Is

The Breakdown Effect is a known Meta reporting behavior where the sum of broken-down results does not equal the total. When you apply a breakdown (e.g., by age or placement), the individual rows may add up to more or less than the overall total.

## Why It Matters

If you don't know about this, you'll waste time trying to reconcile numbers that will never match. Understanding the Breakdown Effect prevents false conclusions and keeps your analysis focused on directional insights rather than exact accounting.

## How It Works

1. When you break down results, Meta attributes each conversion to the breakdown value where it occurred
2. Some conversions can't be attributed to a specific breakdown value (e.g., cross-device, delayed attribution)
3. Meta may count a single conversion across multiple breakdown values in some edge cases
4. The result: individual breakdown rows don't always sum to the campaign total
5. This is expected behavior, not a bug

## Common Mistakes

- Panicking when breakdown totals don't match campaign totals
- Spending hours trying to reconcile the numbers
- Drawing precise conclusions from breakdown data that is inherently approximate
- Abandoning breakdowns entirely because the numbers "don't add up"

## How to Apply It

1. Accept that breakdowns are directional, not precise
2. Look for patterns and proportional insights, not exact counts
3. If Audience Segments show 30% to Engaged Audience, the exact number matters less than the proportion
4. Use breakdowns to identify major trends (e.g., one placement getting 60% of spend with poor results)
5. Cross-reference with your own analytics for precise numbers when needed

## When to Make Exceptions

- If the discrepancy is massive (e.g., breakdown total is 2x the campaign total), investigate — this may indicate a tracking or reporting bug, not just the standard Breakdown Effect

## Related SOPs

- [Breakdowns](breakdowns.md)
- [Conversion Reporting](conversion-reporting.md)
- [Ad Performance Troubleshooting](../05-diagnostics-updates/ad-performance-troubleshooting.md)

## Sources

- [Attribution Breakdowns vs. Compare Attribution Settings](https://www.jonloomer.com/attribution-breakdowns-vs-compare-attribution-settings/)
- [Breakdowns in Meta Ads Manager](https://www.jonloomer.com/breakdowns-meta-ads-manager/)

---

*Part of the [Meta Ads SOP Library](../README.md) — built from Jon Loomer's free content.*
