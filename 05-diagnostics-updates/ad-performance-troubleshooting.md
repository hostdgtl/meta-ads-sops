# Ad Performance Troubleshooting

> **Source:** Jon Loomer | **Last Updated:** 2026-04-28 | **Status:** Complete

---

## What It Is

A diagnostic framework for identifying and fixing common performance issues in Meta ad campaigns. Start by verifying whether results are actually bad, then systematically investigate causes.

## Why It Matters

Most performance issues have identifiable causes that don't require blowing up your account. A structured troubleshooting approach prevents panic-driven decisions that often make things worse.

## How It Works

### Step 1: Are Results Actually Bad?
- Check Compare Attribution Settings — results may look different across windows
- Verify view-through conversions aren't inflating numbers
- Cross-reference with your own analytics (Shopify, GA4)
- Results that seem "too good" may include view-through inflation

### Step 2: Diagnose the Problem

**No delivery / very low spend:**
- Check budget — is it sufficient for your bid strategy?
- Check audience size — too narrow?
- Check ad approval status — any rejections?
- Learning phase may need more time

**Results dropped suddenly:**
- Creative fatigue: frequency going up, CTR going down
- Seasonality: compare to same period last year
- Competition: more advertisers in your space?
- Offer fatigue: has the market seen your promotion too long?
- Platform changes: check Ads Manager Updates SOP

**High cost per result:**
- Check placement breakdown — is one placement eating budget with poor results?
- Check audience breakdown — are you reaching the wrong demographics?
- Review creative — is it truly diverse and compelling?
- Consider Value Rules if delivery skews to low-value segments

### Step 3: Fix It
- **Creative fatigue:** Add diverse new creative using the Creative Testing tool
- **Wrong demographics:** Apply Value Rules, not hard restrictions
- **Placement issues:** Exclude consistently underperforming placements (with data)
- **Tracking problems:** Verify pixel and CAPI in Events Manager
- **Algorithm needs time:** Don't make changes too quickly — wait for the learning phase to complete

## Common Mistakes

- Making changes within the first 48-72 hours before the learning phase completes
- Blaming Andromeda or "the algorithm" instead of examining creative and offer
- Restarting campaigns from scratch instead of diagnosing and fixing
- Looking at vanity metrics (impressions, clicks) instead of conversion metrics

## How to Apply It

1. When performance drops, run through the diagnostic steps above in order
2. Identify the most likely cause before making changes
3. Make one change at a time and wait for data before judging
4. Document what you changed and what happened — build institutional knowledge

## When to Make Exceptions

- Genuine tracking failures (broken pixel, CAPI down) require immediate fixes regardless of learning phase
- Compliance issues (ad rejected, account restricted) need immediate attention

## Related SOPs

- [Common Advertiser Mistakes](common-advertiser-mistakes.md)
- [Conversion Reporting](../04-measurement-reporting/conversion-reporting.md)
- [Breakdowns](../04-measurement-reporting/breakdowns.md)
- [Creative Testing](../03-creative-ads/creative-testing.md)

## Sources

- [Troubleshoot Inflated Results in Meta Ads Manager](https://www.jonloomer.com/troubleshoot-inflated-results-in-meta-ads-manager/)
- [Meta Ads Not Working](https://www.jonloomer.com/meta-ads-not-working/)
- [Creative Fatigue: What It Is and How to Prevent It](https://www.jonloomer.com/creative-fatigue-meta-ads/)

---

*Part of the [Meta Ads SOP Library](../README.md) — built from Jon Loomer's free content.*
