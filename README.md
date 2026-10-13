# Low-Power Conditional-Capture Flip-Flop (CCFF) in 32 nm CMOS

Design and analysis of a single-ended low-power conditional-capture flip-flop that suppresses
redundant internal switching when the input data equals the stored output (D = Q).
Course project for **ENCS333 – Integrated Circuits**, Birzeit University.

**Team:** Lara Abu Asfour · Israa Turkman · Donia Said

## Overview
- Transistor-level schematics of a conventional master–slave D flip-flop (baseline) and the proposed CCFF
- CCFF optimizations: data-path upsizing, feedback-path strengthening, and a weak keeper on the internal dynamic node
- Full-custom layout in Electric VLSI
- Pre-layout and post-layout (parasitic-extracted) simulations in LTspice
- Comparison against the baseline and three published low-power flip-flop designs

## Tools
Electric VLSI · LTspice · PTM 32 nm models

## Files
| File | Description |
|---|---|
| `project_Ic.jelib` | Electric library: schematics (inverter, NOR2, D flip-flop, CCFF) |
| `projectIcLayout.jelib` | Electric library: layouts |
| `IC Paper.pdf` | Project paper (IEEE TCAS-II format) |

## Opening the design
In Electric VLSI: **File → Open Library**, then select one of the `.jelib` files.

## Results
Results are summarized in the paper (`IC Paper.pdf`).
