# VHDL Counter with Overflow Handling
This repository contains a VHDL implementation of a 4-bit counter.  The original code has a potential overflow issue. A corrected version with overflow handling is also provided.

## Original Code (counter.vhdl):
The original counter increments without checking for overflow. This can lead to unexpected behavior.

## Corrected Code (counter_fixed.vhdl):
The corrected version handles overflow by wrapping around to 0 after reaching the maximum count (15). This ensures predictable counter behavior.

## How to Use:
1. Simulate both versions using your preferred VHDL simulator to observe the difference in behavior when the counter reaches its maximum value.
2. Study the corrected code to understand how to properly handle overflow in your own VHDL designs.