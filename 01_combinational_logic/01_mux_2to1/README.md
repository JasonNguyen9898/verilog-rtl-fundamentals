# Exercise 01 — 2-to-1 Multiplexer

**Status:** Not started — no RTL, testbench or verification results have been uploaded.

## Objective

Design a combinational 2-to-1 multiplexer in Verilog and verify all input combinations.

## Specification

- Inputs: `a`, `b`, `sel` (each 1 bit)
- Output: `y` (1 bit)
- Behaviour: `y = a` when `sel = 0`; `y = b` when `sel = 1`

| sel | a | b | expected y |
| --- | --- | --- | --- |
| 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 1 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 |
| 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 0 |
| 1 | 1 | 1 | 1 |

## Tasks

- [ ] Write a synthesizable combinational Verilog module
- [ ] Write a testbench that checks all 8 input combinations
- [ ] Run the simulation and record the command/tool used
- [ ] Save evidence of the results (log or waveform)
- [ ] Describe the coding choices and any debugging
- [ ] Update this README with verification outcomes

## Planned files

- `rtl/mux_2to1.v` — RTL design
- `tb/tb_mux_2to1.v` — self-checking testbench
- `results/` — simulation evidence

We will add these files as they are developed, rather than publishing untested source code.
