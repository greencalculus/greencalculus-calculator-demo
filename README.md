<div align="center">

<img src="https://raw.githubusercontent.com/greencalculus/.github/main/profile/assets/greencalculus-logo.png" width="72" height="72" alt="GreenCalculus" />

# GreenCalculus — Open Carbon Accounting Calculators

### Open-source, zero-dependency reference implementations for corporate greenhouse-gas accounting.

Fifteen self-contained calculators spanning the full corporate inventory — **Scope 1, 2 and 3**, plus
target-setting, financed emissions and climate disclosure.

[**Live preview**](https://greencalculus.github.io/greencalculus-calculator-demo/) · [greencalculus.com](https://greencalculus.com) · [Methodology](https://github.com/greencalculus/greencalculus-methodology) · [Standards](https://github.com/greencalculus/greencalculus-standards)

![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-Zero_dependencies-04BF62?style=flat-square)
![Scope 1·2·3](https://img.shields.io/badge/GHG_Protocol-Scope_1·2·3-04BF62?style=flat-square)
![IPCC AR6](https://img.shields.io/badge/IPCC_AR6-GWP--100-04BF62?style=flat-square)
![SBTi · PCAF · CBAM](https://img.shields.io/badge/SBTi_·_PCAF_·_CBAM-aligned-04BF62?style=flat-square)
![License: MIT](https://img.shields.io/badge/License-MIT-04BF62?style=flat-square)

</div>

---

Self-contained, reusable reference implementations of corporate carbon-accounting
calculators — built for sustainability officers, engineers, and CSRD compliance teams.
The gallery walks the whole corporate inventory:
roll everything up in the **GHG Inventory Aggregator**, then drill into **Scope 1**
(combustion), **Scope 2** (electricity, dual reporting) and **Scope 3** (business travel
+ the value-chain suite) — alongside SBTi targets, FLAG land emissions, PCAF financed
emissions and EU CBAM border carbon.

Each calculator is a **single HTML file**: vanilla JavaScript, zero dependencies, built to
GHG Protocol and IPCC AR6 — fork it, read it, embed it. Open a calculator, or jump to the
full live version.

---

## Calculators

| Calculator | Scope | Live version |
|---|---|---|
| 📊 **[GHG Inventory Aggregator](./ghg-inventory-aggregator.html)** | Consolidate Scope 1 + 2 + 3 → dual location/market grand totals + scope split | [Open live ↗](https://greencalculus.com/calculators/ghg-inventory-aggregator-scope123-calculator/) |
| 🔥 **[Scope 1 Stationary Combustion](./stationary-combustion.html)** | Direct fuel combustion → tCO₂e, 10 fuel types | [Open live ↗](https://greencalculus.com/calculators/scope-1-combustion-calculator/) |
| ⚡ **[Scope 2 Electricity](./scope-2-electricity.html)** | Purchased electricity → tCO₂e with dual location-based + market-based reporting (EAC/PPA/residual mix) | [Open live ↗](https://greencalculus.com/calculators/scope-2-electricity-calculator/) |
| ✈️ **[Scope 3 Business Travel](./scope-3-business-travel.html)** | Category 6 air/rail/road/hotel + radiative-forcing uplift; hub to the full Scope 3 value-chain suite | [Open live ↗](https://greencalculus.com/calculators/business-travel-air-calculator/) |
| 🎯 **[SBTi Near-Term Target](./sbti-near-term-target.html)** | Science-based target via Absolute Contraction | [Open live ↗](https://greencalculus.com/calculators/sbti-near-term-target-calculator/) |
| 🌿 **[FLAG Emissions](./flag-emissions.html)** | Forest, Land & Agriculture — LUC + LM + Removals | [Open live ↗](https://greencalculus.com/calculators/flag-emissions-calculator/) |
| 💰 **[PCAF Financed Emissions](./pcaf-financed-emissions.html)** | All 7 PCAF Part A asset classes + DQ score; hub to the 10-calc suite | [Open live ↗](https://greencalculus.com/calculators/pcaf-listed-equity-corporate-bonds/) |
| 🛂 **[CBAM Quarterly Reporting](./cbam-quarterly-reporting.html)** | Embedded emissions + certificate liability across the 6 CBAM goods; hub to the 12-calc disclosure suite | [Open live ↗](https://greencalculus.com/calculators/cbam-quarterly-reporting-calculator/) |
| 🌾 **[Scope 1 Biomass & Biofuel](./scope-1-biomass-biofuel.html)** | Biogenic + fossil split → fossil CO₂e in Scope 1, biogenic CO₂ as a memo | [Open live ↗](https://greencalculus.com/calculators/scope-1-biomass-biofuel-calculator/) |
| 🚢 **[Scope 1 Marine & Aviation Fuel](./scope-1-marine-aviation.html)** | Own ships & aircraft (MGO/HFO/Jet A-1/avgas) → tCO₂e + aviation RF memo | [Open live ↗](https://greencalculus.com/calculators/scope-1-marine-aviation-fuel-own-operations-calculator/) |
| ⚙️ **[Scope 1 + 2 CHP / Cogeneration](./scope-1-2-chp-cogeneration.html)** | Allocate CHP fuel emissions across power & heat (efficiency method) | [Open live ↗](https://greencalculus.com/calculators/scope-1-chp-cogeneration-calculator/) |
| ♨️ **[Scope 2 Purchased Steam & Hot Water](./scope-2-steam-hot-water.html)** | Steam/hot water → tCO₂e, location + market (supplier back-calc) | [Open live ↗](https://greencalculus.com/calculators/scope-2-purchased-steam-hot-water-calculator/) |
| 🔌 **[Scope 2 Residual Mix](./scope-2-residual-mix.html)** | AIB / Green-e residual factor on untracked electricity (market-based) | [Open live ↗](https://greencalculus.com/calculators/scope-2-residual-mix-calculator/) |
| 🔋 **[Scope 2 Renewable Procurement](./scope-2-renewable-procurement.html)** | REC / PPA / VPPA / onsite vs residual mix; reduction % | [Open live ↗](https://greencalculus.com/calculators/scope-2-renewable-procurement-rec-ppa-calculator/) |
| 🌡️ **[Scope 2 District Heating & Cooling](./scope-2-district-heating.html)** | District heat & cooling → tCO₂e, location + market | [Open live ↗](https://greencalculus.com/calculators/scope-2-district-heating-cooling-calculator/) |

The landing page ([`index.html`](./index.html)) is a gallery linking all fifteen calculators.

---

### 📊 GHG Inventory Aggregator

The capstone of a corporate carbon inventory — consolidates the three scopes into one auditable total.
Because Scope 2 is reported two ways, the inventory carries **two grand totals**:
`location-based = S1 + S2(location) + S3` and `market-based = S1 + S2(market) + S3` — the same Scope 1 and
Scope 3 flow into both, only the Scope 2 line differs. Enter scope subtotals (with Scope 3 split into the
material categories), pick the headline basis, and get the dual totals, a **scope-split bar**, and the
**Scope 3 share of total** — which for most companies is 70–90%. This is the consolidated inventory that
CSRD/ESRS E1, SECR, IFRS S2 and CDP expect.

- **Standard:** GHG Protocol Corporate Standard — Scopes 1, 2 & 3
- **Method:** inventory consolidation · dual Scope 2 totals · scope-split apportionment

### 🔥 Scope 1 Stationary Combustion

Converts fuel burned in owned or controlled equipment into tCO₂e across 10 fuel types
(natural gas in kWh GCV and m³; diesel, petrol, LPG, fuel oil, kerosene; industrial and
domestic coal; wood-chip biomass). Outputs a full calculation breakdown: emission factor,
GWP basis, raw kg result, and annualised figure.

- **Standard:** GHG Protocol Corporate Standard — Scope 1
- **Factors:** UK DESNZ 2024 · **GWP:** IPCC AR6 GWP-100

### ⚡ Scope 2 Electricity

Reports purchased electricity **two ways at once**, as the GHG Protocol Scope 2 Guidance requires in
markets with energy attribute certificates. The **location-based** method applies the average grid factor
for where power is consumed; the **market-based** method reflects contractual instruments —
`market = covered share × 0 + uncovered share × residual mix`. Pick a grid, choose an instrument (residual
mix, EACs — RECs/GOs/REGOs/I-RECs, a PPA, or a supplier-specific factor), set the renewable coverage, and
watch certificates drive the *market-based* number toward zero while the *location-based* number holds.

- **Standard:** GHG Protocol Scope 2 Guidance — dual reporting
- **Factors:** IEA / Ember location factors · AIB & EPA eGRID residual mix · **GWP:** IPCC AR6 GWP-100

### ✈️ Scope 3 Business Travel

Calculates **GHG Protocol Scope 3, Category 6** travel with the activity method —
`emissions = activity × factor` — across air (domestic, short-haul, long-haul economy & business), rail,
car/taxi, and hotel stays, with the optional **radiative-forcing uplift (×1.9)** for the non-CO₂
high-altitude effects of flying. Doubles as a hub linking the full **Scope 3 value-chain suite** (23 live
calculators across Categories 1–14): spend-based purchased goods, well-to-tank, T&D losses, freight by six
modes, waste, commuting & WFH, leased assets, use of sold products, end-of-life, franchises, and more — all
rolled up by the GHG Inventory Aggregator.

- **Standard:** GHG Protocol Corporate Value Chain (Scope 3) — Category 6
- **Factors:** UK DESNZ 2024 (pax-km / room-night) · **GWP:** IPCC AR6 GWP-100

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

### 💰 PCAF Financed Emissions

One universal engine for all **7 PCAF Part A asset classes** — `financed emissions =
(outstanding ÷ denominator) × investee emissions`. Selecting an asset class relabels the
attribution denominator (EVIC, total equity + debt, property value at origination,
PPP-adjusted GDP, …), computes the attribution factor and the **auto-derived PCAF
data-quality score (1–5)**, and deep-links to that class's live calculator. Doubles as a
hub linking the full 10-calculator PCAF suite (Part A, facilitated, insurance-associated,
and the cross-asset data-quality tool).

- **Standard:** PCAF Global GHG Accounting & Reporting Standard (Financed Emissions)
- **Method:** attribution-factor accounting · auto-derived data-quality score

### 🛂 CBAM Quarterly Reporting

Estimates the **embedded emissions** of EU imports across the six CBAM goods (cement, iron
& steel, aluminium, fertilisers, hydrogen, electricity) — `embedded = quantity × (direct +
indirect intensity)` — then layers on the certificate liability: the **2026–2034 phase-in**
(2.5% rising to 100% as EU ETS free allocation is withdrawn) and a **rebate** for any carbon
price already paid in the country of origin. A *transitional* toggle reflects the report-only
period through 2025. Doubles as a hub linking the full **12-calculator climate disclosure &
compliance suite** (EU ETS, CSRD E1, IFRS S2, TCFD, CDP, SECR, SEC, CA SB-253/261, AASB S2,
Singapore).

- **Regulation:** (EU) 2023/956 — Carbon Border Adjustment Mechanism
- **Method:** embedded-emissions accounting · phase-in factor · origin carbon-price rebate
- **Note:** intensity defaults are illustrative; the live tool uses the Commission's
  published default-value tables per good and country of origin

---

## Technical spec

| Property | Detail |
|---|---|
| Dependencies | Zero — Vanilla JS only |
| Rendering | Modern CSS, `clamp()` fluid typography, dark theme |
| Numbers | JetBrains Mono, `tabular-nums` |
| Hosting | GitHub Pages |
| License | MIT |

> **Note:** these are simplified, self-contained reference implementations. The production
> calculators on GreenCalculus.com read live emission factors from the Master Brain data
> layer and add full audit trails, export, and uncertainty disclosure.

---

## Methodology

All emission factors and GWP values are documented in:
→ [greencalculus/greencalculus-methodology](https://github.com/greencalculus/greencalculus-methodology)

---

## Full platform

Fifteen open reference calculators from the [GreenCalculus](https://greencalculus.com)
traceable carbon-accounting platform — built for sustainability officers, engineers, and
CSRD compliance teams.

**Built and maintained by [Jeremiah Say](https://greencalculus.com/about/jeremiah-say/)**
— Lead Systems Architect · GHG Protocol · IPCC AR6 · CSRD/ESRS E1 · SBTi · PCAF

---

## License

MIT
