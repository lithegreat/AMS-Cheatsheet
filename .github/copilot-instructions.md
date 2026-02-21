# Copilot Instructions for AMS-Cheatsheet

## Repository purpose

This repository contains a **LaTeX cheatsheet** for the course **Analog and Mixed-Signal Circuit Design**.

It is based on the **latex4ei template** and should keep latex4ei structure and conventions intact.

Primary topic coverage:

1. Semiconductor process and device basics
2. Amplifiers
3. References & comparators

When generating or editing content, keep the material concise, exam-oriented, and suitable for a compact cheatsheet format.

## Content style requirements

- Write in short, information-dense bullet points.
- Prefer formulas, key assumptions, and design trade-offs over long explanations.
- Include units and conditions for equations where relevant.
- Use consistent analog notation and symbols throughout.
- Focus on practical circuit intuition and common approximations.

## Topic-specific expectations

## Canonical course outline (must reflect this structure)

When drafting or reorganizing cheatsheet content, map sections to the course outline below.

### Chapter 1: Semiconductor process and device basics

a) Semiconductor process and device basics
- Intro and nomenclature

b) MOSFET Basics
- Physics
- I/V characteristics
- Operation regions
- Small-signal model

c) Basic MOSFET circuits
- Source follower
- Common-source configuration
- Common-gate configuration

d) Integrated resistors
- Technology choices
- Non-idealities
- Noise
- Layout

e) MOSFET Advanced
- Body effect
- Temperature
- Mismatch
- Noise
- Reliability

f) Integrated capacitors
- Technology choices
- Layout
- Parasitic MOS caps
- Parasitic wiring effects
- Inductors

g) Device modeling and circuit simulation
- Models and choices
- Simulation flow
- Analog circuit scaling

h) Bipolar transistors
- Modes of operation
- I/V characteristic
- Small-signal model
- Layout
- Comparison to MOSFET

i) Manufacturing issues
- How technology ties to circuits
- Consequences for systems, design, and verification

j) Current mirrors
- Basic principle
- Degeneration / cascading
- Mismatch effects

### Chapter 2: Amplifiers

a) Ideal and more real op-amps
- Amplification
- Feedback
- Basic op-amp configurations
- Non-idealities
- Practical application example

b) Basic op-amp design
- Differential pair configurations
- Challenges and limitations
- Folded cascode
- 2-stage op-amp
- Output stages
- Non-idealities

c) Frequency response and compensation
- Feedback / Bode plots
- Types of compensation
- Miller effect
- Compensation alternatives

d) Amplifier optimization
- Basics
- Noise analysis
- Noise quantification and calculation
- System noise considerations
- Noise optimization

e) Advanced gain stages
- Offset reduction
- Gain boosting

### Chapter 3: References & comparators

a) References
- Current sources
- Temperature behavior
- Voltage reference concept
- Bandgap circuits

b) System example: linear voltage regulator
- Basics
- Practical example

c) Switches
- Resistive behavior
- Switched capacitor

d) Comparators
- Concept
- Hysteresis
- Clocked comparators
- Time hysteresis / sample & hold
- Offset compensation

## LaTeX and repository conventions

- Treat `latex4ei` as the authoritative template layer; avoid modifying template internals unless explicitly requested.
- Keep edits compatible with the existing LaTeX structure in `AMS.tex` and `latex4ei/*` styles/classes.
- Reuse existing macros and formatting patterns before introducing new commands.
- Avoid adding new packages unless absolutely necessary.
- Keep equations compact and aligned with cheatsheet readability.

## What to avoid

- Do not turn sections into textbook-like prose.
- Do not introduce off-topic AMS areas beyond this cheatsheet scope.
- Do not add speculative claims without standard assumptions.
- Do not reformat unrelated parts of the document.

## Output quality bar

For any generated addition:

- technically correct,
- concise enough for a cheatsheet,
- consistent notation,
- immediately useful for exam review or quick design recall.
