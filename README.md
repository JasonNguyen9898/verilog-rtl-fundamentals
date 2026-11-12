# Digital Design & RTL Fundamentals

A learning portfolio documenting my progress in digital logic, **Verilog/SystemVerilog**, synthesizable RTL design and functional verification.

I am an Electronics Engineering graduate developing practical digital hardware design skills through small, documented projects. This repository focuses on fundamentals; larger protocol and ASIC/FPGA projects will be published separately as I develop and verify them.

> **Status:** Learning in progress. A project is not marked verified until its testbench has been run and the results documented.

## Learning roadmap

- **Digital logic:** combinational and sequential circuits, multiplexers, counters, shift registers, latches, flip-flops and registers
- **RTL coding:** Verilog/SystemVerilog syntax, blocking vs. non-blocking assignments, synthesizable coding and avoiding unintended latches
- **State machines:** Moore and Mealy FSM design and implementation
- **Verification:** testbenches, simulation, waveforms, debugging and edge-case testing
- **Timing and CDC:** setup/hold time, clock skew, metastability and synchronizer fundamentals

## Exercises

| Exercise | Main concept | Status |
| --- | --- | --- |
| [01 — 2-to-1 Multiplexer](01_combinational_logic/01_mux_2to1/README.md) | Combinational RTL, truth tables and exhaustive testing | **Not started** |

More exercises will be added only as they are designed and documented.

## Repository conventions

Each completed exercise will aim to include:

1. **Specification:** circuit requirements and expected behaviour
2. **RTL:** synthesizable source code
3. **Verification:** testbench and cases checked
4. **Evidence:** actual simulator output or waveforms
5. **Reflection:** debugging notes and lessons learned

Typical project layout (files appear when written):

```text
01_combinational_logic/
  01_mux_2to1/
    README.md
    rtl/
    tb/
    results/
docs/
  learning_log.md
```

## Learning log

See [docs/learning_log.md](docs/learning_log.md) for dated progress updates.

## Future portfolio tracks

Once the fundamentals are established, I plan to publish separate projects covering UART, SPI, I2C, FIFOs and more comprehensive functional verification. Advanced ASIC subjects such as static timing analysis, physical design and RTL-to-GDSII will be kept in a distinct track.

*This is a learning portfolio. Planned topics are goals, not claims of completed experience.*
