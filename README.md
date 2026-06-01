# GreenCalculus — Carbon Calculator Demos

**Live demos:** https://greencalculus.github.io/greencalculus-calculator-demo/

Open-source, self-contained demos of production calculators from
[GreenCalculus.com](https://greencalculus.com) — the platform hosting 1,000+ carbon
and environmental calculators for sustainability officers, engineers, and CSRD
compliance teams.

Each demo is a **single HTML file**: vanilla JavaScript, zero dependencies, built to
GHG Protocol and IPCC AR6. Open the demo, or jump straight to the full live calculator.

---

## Calculators

| Demo | Scope | Live calculator |
|---|---|---|
| 🔥 **[Scope 1 Stationary Combustion](./stationary-combustion.html)** | Direct fuel combustion → tCO₂e, 10 fuel types | [Open live ↗](https://greencalculus.com/calculators/scope-1-combustion-calculator/) |
| 🎯 **[SBTi Near-Term Target](./sbti-near-term-target.html)** | Science-based target via Absolute Contraction | [Open live ↗](https://greencalculus.com/calculators/sbti-near-term-target-calculator/) |
| 🌿 **[FLAG Emissions](./flag-emissions.html)** | Forest, Land & Agriculture — LUC + LM + Removals | [Open live ↗](https://greencalculus.com/calculators/flag-emissions-calculator/) |

The landing page ([`index.html`](./index.html)) is a gallery linking all three.

---

### 🔥 Scope 1 Stationary Combustion

Converts fuel burned in owned or controlled equipment into tCO₂e across 10 fuel types
(natural gas in kWh GCV and m³; diesel, petrol, LPG, fuel oil, kerosene; industrial and
domestic coal; wood-chip biomass). Outputs a full calculation breakdown: emission factor,
GWP basis, raw kg result, and annualised figure.

- **Standard:** GHG Protocol Corporate Standard — Scope 1
- **Factors:** UK DESNZ 2024 · **GWP:** IPCC AR6 GWP-100

### 🎯 SBTi Near-Term Target

Builds a science-based near-term target with the **Absolute Contraction Approach (ACA)** —
`target = baseline × (1 − rate)^years`. Picks an ambition tier (Minimum 1.5°C, Accelerated,
Leadership, or custom rates), tests **Scope 3 materiality** (the ≥40% trigger and ≥67%
coverage rule), validates the **4.2%/yr Scope 1+2 floor**, and projects a year-by-year
reduction trajectory with cumulative cuts.

- **Standard:** SBTi Corporate Near-Term Criteria · GHG Protocol · IPCC AR6 WG3
- **Method:** Absolute Contraction Approach (used by >90% of validated companies)

### 🌿 FLAG Emissions

Calculates **Forest, Land & Agriculture** emissions across three pillars reported as
separate inventory lines: **Land Use Change** (one-time deforestation stock loss, optionally
amortised over 20 years; ongoing peatland drainage), **Land Management** (annual biogenic
CH₄/N₂O from livestock, nitrogen fertiliser, rice, and crop-residue burning), and **Carbon
Removals** (forestry and soil sequestration — reported separately, never netted). Includes
the **SBTi FLAG 20%** eligibility check.

- **Standard:** GHG Protocol Land Sector & Removals Standard (2026) · SBTi FLAG
- **Factors:** IPCC AR6 Tier 1 · DEFRA 2025 · **GWP:** IPCC AR6 GWP-100

---

## Technical spec

| Property | Detail |
|---|---|
| Dependencies | Zero — Vanilla JS only |
| Rendering | Modern CSS, `clamp()` fluid typography, dark theme |
| Numbers | JetBrains Mono, `tabular-nums` |
| Hosting | GitHub Pages |
| License | MIT |

> **Note:** these are simplified demonstrations. The production calculators on
> GreenCalculus.com read live emission factors from the Master Brain data layer and
> include full audit trails, export, and uncertainty disclosure.

---

## Methodology

All emission factors and GWP values are documented in:
→ [greencalculus/greencalculus-methodology](https://github.com/greencalculus/greencalculus-methodology)

---

## Full platform

A demo of three calculators from [GreenCalculus.com](https://greencalculus.com),
which hosts 1,000+ carbon and environmental calculators for sustainability officers,
engineers, and CSRD compliance teams.

**Built by [Jeremiah Say](https://greencalculus.com/about/jeremiah-say/)**
Lead Systems Architect · GHG Protocol · IPCC AR6 · CSRD

---

## License

MIT
