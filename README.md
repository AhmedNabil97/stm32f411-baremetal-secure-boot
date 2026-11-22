# stm32f411-baremetal-secure-boot
Modular bare metal firmware framework with secured dual slot bootloader for stm32f411CEU6

## Objectives
- Build a zero-HAL, register-level bare-metal firmware architecture from scratch.
- Set up a complete custom toolchain build and debug workflow without IDE code generators.
- Design and implement a **dual-slot secure bootloader** supporting firmware updates, integrity checks, and rollback recovery.
- Document architecture decisions, memory layouts, and reference manual findings step by step.
