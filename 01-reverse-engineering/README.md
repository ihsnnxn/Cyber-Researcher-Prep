# Reverse Engineering

Learning reverse engineering with Ghidra, x64dbg, and static analysis tools.

## Progress

| Challenge | Tool | Status | Writeup |
|-----------|------|--------|---------|
| crackme-01 | Ghidra | ✅ Solved | [Link](ghidra-crackmes/crackme-01.md) |
| crackme-02 | Ghidra + x64dbg | ✅ Solved | [Link](ghidra-crackmes/crackme-02.md) |
| PE analysis | PEStudio | ✅ Documented | [Link](pe-analysis/pestudio-notes.md) |

## Methodology

1. **Static triage** — PEStudio: imports, entropy, strings
2. **Disassembly** — Ghidra: identify main, compare functions
3. **Dynamic (if needed)** — x64dbg: breakpoints, API tracing
4. **Document** — screenshots, reasoning, key findings
