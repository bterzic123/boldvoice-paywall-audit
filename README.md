# Paywall Audit — BoldVoice

**Live:** https://bterzic123.github.io/boldvoice-paywall-audit/

Four ideas for the BoldVoice paywall, each backed by a number from Adapty's State of Paywalls 2026, plus a clickable rebuild of the paywall and the moment after close, in BoldVoice's own design. Switch Today / Proposed above the phone to compare with what ships now.

## The ideas

| # | Idea | Report anchor | Potential outcome |
| :-- | :-- | :-- | :-- |
| 1 | Give people a second look when they close | 4.5: only 4% of apps show a second paywall on close; it converts at 0.88× the main paywall and beats it in 45% of apps | ARPU +10–15% (based on Adapty data) |
| 2 | Put your 4.8 stars on the paywall | 3.1: only 27% of top paywalls show social proof; 5.3 | CR +10–30% (observed in winning A/B tests) |
| 3 | Write the headline to the person | 3.5: only 2% of top paywall headlines use what the app knows about the user; 5.3 | CR +8–17% (observed in winning A/B tests) |
| 4 | Hold the X for three seconds | 3.7: 22% of apps delay the close button, half by 3–5 s; 5.3 | CR +8–15% (observed in winning A/B tests) |

**Benchmarks used:** Education apps in the US where the report breaks it down, all apps otherwise. App Store data, Oct 2025–Sep 2026.

**The report:** [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=boldvoice): 78,000+ paywalls, 30,000+ apps, benchmarks by region and category.

## Grounding

Prices, the trial, the rating, user count, Top 10 line and the review quote come from BoldVoice's own App Store listing and in-app screens. The weekly figure on the offer is €99.99 ÷ 52. No discount is shown, because the store lists one product. Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for BoldVoice.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
