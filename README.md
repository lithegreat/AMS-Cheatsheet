# Analog and Mixed-Signal Circuit Design — Cheatsheet

[![CI](https://github.com/lithegreat/AMS-Cheatsheet/actions/workflows/ci.yml/badge.svg)](https://github.com/lithegreat/AMS-Cheatsheet/actions/workflows/ci.yml)
[![Latest PDF](https://img.shields.io/github/v/release/lithegreat/AMS-Cheatsheet?label=latest%20PDF)](https://github.com/lithegreat/AMS-Cheatsheet/releases/tag/latest)

A compact LaTeX cheatsheet for the **Analog and Mixed-Signal Circuit Design** course, built on the [latex4ei](https://github.com/latex4ei/latex4ei-packages) template.

## Download

The latest compiled PDF is automatically built and published on every push to `main`.
**[Download latest PDF](https://github.com/lithegreat/AMS-Cheatsheet/releases/tag/latest)**

## Content

1. **Semiconductor process and device basics** — MOSFET physics, I/V characteristics, small-signal model, basic stages (CS/CD/CG), body effect, noise, mismatch, capacitors, bipolar transistors, current mirrors
2. **Amplifiers** — Op-amp design, differential pairs, folded cascode, two-stage op-amp, frequency response, compensation, noise analysis, gain boosting
3. **References & Comparators** — Bandgap references, linear regulators, switches, comparators, clocked comparators, offset compensation

## Build locally

Requires a LaTeX distribution with `UseLATEX.cmake`. The CI uses the `makeappdev/uselatex` Docker image.

```shell
mkdir build && cd build
cmake ..
make
```

The compiled `AMS.pdf` will be placed in the `build/` directory.
