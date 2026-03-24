# 1612x-CPU-Design
AIM:
To design and implement a 16-bit CPU based on Morris Mano’s architecture using Logisim.

TASKS COMPLETED:
1. Designed 16-bit and 12-bit registers (AR, PC, DR, AC, IR, TR).
2. Implemented a 16-bit Common Bus and ALU.
3. Designed the Sequence Counter and Control Unit logic.
4. Integrated sub-circuits into a functional Main Circuit.

TECHNICAL SPECIFICATIONS:
- RAM: 4096x16
- Instruction Set: 25 total (Memory-Reference & Register-Reference)
- Control: Timing Signal Generator (T0 to T15)
- Logic: RTL-based micro-operations

HOW TO USE:
Load the .circ file into Logisim. The simulation supports the fetch-decode-execute 
cycle by cycling the system clock.
