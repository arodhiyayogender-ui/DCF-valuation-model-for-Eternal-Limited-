# DCF-valuation-model-for-Eternal-Limited-
DCF valuation model for Eternal Limited (NSE: ETERNAL) — 3-statement model, WACC, sensitivity analysis
# Eternal Limited (NSE: ETERNAL) — DCF Valuation Model

**Prepared by:** Yogender  
**Date:** June 2025  
**Tool:** Microsoft Excel (no VBA, no add-ins)

---

## Overview

A bottom-up discounted cash flow (DCF) valuation of Eternal Limited, formerly known as Zomato Limited — India's leading food-tech and quick-commerce platform. The model is built on FY2025 Annual Report data and projects financials through FY2031E.

## Model Structure

| Sheet | Contents |
|---|---|
| Cover | Company snapshot, model overview |
| Assumptions | All driver inputs — segment growth rates, margins, capex, working capital |
| P&L | Consolidated income statement FY2023A–FY2031E |
| Balance Sheet | Asset and liability projections |
| Cash Flow | CFO, CFI, CFF and FCFF build |
| WACC | CAPM-based cost of equity, cost of debt, capital structure weighting |
| DCF | 6-year FCFF discounting, terminal value, equity bridge, intrinsic value per share |
| Sensitivity | Two-variable sensitivity tables — WACC × terminal growth rate; WACC × terminal EBITDA margin |

## Key Assumptions

- **WACC:** 15.7% (Rf 7.0% + β 1.25 × ERP 7.0%; Kd post-tax 7.1%)
- **Terminal growth rate (g):** 5.5%
- **Forecast horizon:** FY2026E – FY2031E (6 years explicit)
- **Terminal EBITDA margin:** 16% (from –17% in FY2023A)
- **Discounting:** Mid-year convention

## Key Output

| Metric | Value |
|---|---|
| Intrinsic Value per Share | ₹40 (base case) |
| Current Market Price (CMP) | ₹244 |
| Implied Premium to DCF | ~6x |
| Enterprise Value (base) | ₹34,724 Cr |

The significant premium of CMP to intrinsic value reflects the market's expectation of sustained hyper-growth beyond the 6-year explicit forecast — consistent with Eternal's position as a high-growth story stock. The model is intentionally built on conservative assumptions to stress-test valuation rather than justify current pricing.

## Data Sources

- Eternal Limited Annual Report FY2024-25 (BSE filing, July 2025)
- Screener.in for historical financials
- Damodaran Online for India equity risk premium (January 2025)

## Formatting Conventions

| Font Colour | Meaning |
|---|---|
| Blue | Hardcoded input — change to adjust assumptions |
| Black | Formula computed on same sheet |
| Green | Cross-sheet link |
| Grey | Helper / informational row |

---

*This model is prepared for academic and research purposes only. It does not constitute investment advice.*
