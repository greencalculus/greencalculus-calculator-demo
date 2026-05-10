# GreenCalculus — Scope 1 Stationary Combustion Calculator

**Live demo:** https://greencalculus.github.io/greencalculus-calculator-demo/

A production-grade Scope 1 stationary combustion emissions calculator.
Built to GHG Protocol Corporate Standard, IPCC AR6 GWP-100.
Zero dependencies — Vanilla JS + Modern CSS only.

---

## Live calculator

→ **[Open calculator](https://greencalculus.github.io/greencalculus-calculator-demo/)**

Supports 10 fuel types:
- Natural gas (kWh GCV and m³)
- Diesel, Petrol, LPG
- Fuel oil, Kerosene
- Coal (industrial and domestic)
- Wood chips (biomass — CH4 + N2O only per GHG Protocol)

Outputs tCO₂e with full calculation breakdown showing:
emission factor, GWP basis, raw kg result, and annualised figure.

---

## Technical spec

| Property | Detail |
|---|---|
| Standard | GHG Protocol Corporate Standard — Scope 1 |
| GWP basis | IPCC AR6 GWP-100 |
| Emission factors | UK DESNZ 2024 |
| Dependencies | Zero — Vanilla JS only |
| Rendering | CSS `@layer`, `clamp()` fluid typography |
| Numbers | JetBrains Mono, `tabular-nums` |
| Hosting | GitHub Pages |

---

## Methodology

All emission factors and GWP values are documented in:  
→ [greencalculus/greencalculus-methodology](https://github.com/greencalculus/greencalculus-methodology)

---

## Full platform

This is a demo of one calculator from [GreenCalculus.com](https://greencalculus.com),
which hosts 1,000+ carbon and environmental calculators for
sustainability officers, engineers, and CSRD compliance teams.

**Built by [Jeremiah Say](https://greencalculus.com/about/jeremiah-say/)**  
Lead Systems Architect · GHG Protocol · IPCC AR6 · CSRD

---

## License

MIT
