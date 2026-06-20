# Contributing to GreenCalculus Calculator Demos

Thanks for your interest in contributing! These demos are open source (MIT) and we
welcome fixes, improvements, and new calculator demos from the community.

## Ways to contribute

- **Report a bug** — wrong result, broken input, or a calculation that doesn't match the
  stated methodology. Open an [issue](../../issues) with the calculator name, the inputs
  you used, the result you got, and the result you expected.
- **Request a calculator or fuel/factor** — tell us the scope, standard, and source you'd
  like covered.
- **Improve a demo** — accessibility, mobile layout, clearer labels, or code quality. Each
  demo is a single self-contained HTML file with zero dependencies — keep it that way.
- **Methodology questions** — if a factor or formula looks off, link the source. All
  calculators are built to the GHG Protocol and IPCC AR6 and should be fully traceable.

## Submitting a pull request

1. Fork the repository and create a branch (`fix/scope-2-rounding`, `feat/new-calculator`).
2. Keep changes focused — one fix or feature per PR.
3. Test by opening the affected HTML file in a browser; confirm the numbers.
4. Describe **what** changed, **why**, and **cite the source** for any factor or formula change.
5. Open the PR against `main`.

## Ground rules

- No build step, no frameworks, no external dependencies — vanilla JS only.
- Emission factors must cite a published, authoritative source (GHG Protocol, IPCC, DEFRA, etc.).
- Be respectful and constructive.

Questions? Open an issue or reach us at hello@greencalculus.com.
