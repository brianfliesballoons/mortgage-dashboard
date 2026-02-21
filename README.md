# Mortgage Opportunity Dashboard

Live dashboard for assessing reverse mortgage (HECM) and refinance opportunities in the Temecula / Winchester / Murrieta market (Riverside County, CA).

## Features

- **Live Treasury CMT Yield Curve** — 1mo through 30yr rates with sparkline trends
- **SOFR Rate** — Secured Overnight Financing Rate
- **HECM Reverse Mortgage Calculator** — PLF-based principal limit using live 10-Yr CMT, 2026 limit ($1,249,125)
- **Refinance Analyzer** — P&I comparison with breakeven calculation
- **UWM Rate Sheet** — Manual entry for United Wholesale Mortgage rates (from Blink+)
- **PropertyRadar Integration** — Property search with equity/age filters and opportunity tagging

## Data Sources

| Data | Source | Frequency |
|------|--------|-----------|
| CMT Yield Curve | US Treasury | Daily |
| SOFR | NY Federal Reserve | Daily |
| UWM Rates | UWM Blink+ | Manual |
| Property Data | PropertyRadar API | On-demand |

## Setup

Single-file HTML app. No build step.

1. Enable GitHub Pages (Settings → Pages → main / root)
2. Access at `https://yourusername.github.io/mortgage-dashboard/`