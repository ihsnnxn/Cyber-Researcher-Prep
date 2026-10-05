# Crackme 01 — [Name/Source]

## Challenge
[What it asks for — e.g., find the correct password]

## Tools Used
- Ghidra
- x64dbg

## Approach

### 1. Initial Recon
- Ran `strings` — found "[string]"
- Checked PE headers — [observations]

### 2. Static Analysis (Ghidra)
- Located `main` at [address]
- Found comparison at [address]: `strcmp(user_input, "secret")`

### 3. Dynamic Verification (x64dbg)
- Set breakpoint at [address]
- Ran input "[test]" — breakpoint hit
- Register `EAX` contained "[value]"

## Solution
The correct input is `[password]`

## Key Learnings
- [What you learned — e.g., how strcmp returns, how to trace API calls]

## Screenshots
![Ghidra decompilation](screenshots/crackme01-ghidra.png)
