# 2D Systolic Array AI Accelerator Core (GEMM Engine)
Lead Silicon Architect: Mohammed Abdullah
FPGA Verified on AMD Artix-7 (102 mW Total Power, Clock Region X0Y0)

[![SystemVerilog](https://img.shields.io/badge/HDL-SystemVerilog-orange?style=for-the-badge)](https://github.com/abdullaah0309)
[![Artix-7](https://img.shields.io/badge/FPGA-AMD%20Artix--7%20Met-brightgreen?style=for-the-badge)](https://github.com/abdullaah0309)
[![Live Portfolio](https://img.shields.io/badge/Portfolio-abdullaah0309.github.io-00f5d4?style=for-the-badge)](https://abdullaah0309.github.io)

---

## Microarchitecture Overview
- Spatial Compute Grid: Weight-stationary 2D Processing Element (PE) matrix optimized for General Matrix Multiplication (GEMM).
- Skew Buffering: Pipelined input boundary delay registers ensuring precise spatial-temporal alignment.
- Zero-Bubble Flow: Pipelined accumulation registers preventing pipeline stalls across matrix tiles.

---

## FPGA Verification (AMD Artix-7 xc7a35tcsg324-1)
- Target Frequency: 100 MHz Timing Met
- Total Power: 102 mW (placed & routed in clock region X0Y0)

---
(c) 2026 Mohammed Abdullah. Designed for high-performance silicon engineering.
