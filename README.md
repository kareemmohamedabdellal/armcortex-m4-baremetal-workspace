# armcortex-m4-baremetal-workspace
Custom bare-metal build setup for STM32 (ARM Cortex-M4) featuring a custom startup code, linker script, and Makefile
## Features
- Startup Code (stm32_startup.c): Vector table setup, (.data) section copy from Flash to SRAM, and `.bss` clear.
- Linker Script (stm32_ls.ld): Memory mapping for Flash and SRAM.
- Makefile: Build automation using (arm-none-eabi-gcc).
- System Calls (syscalls.c): Minimal GCC stubs.

# Build
Run (make) in terminal to build the project 

---
Note: The main application code and headers are provided for testing and demonstration purposes. My main contribution is writing the bare-metal setup (Startup code, Linker script, and Makefile) from scratch.
