# STM32F103x8 memory configuration adjustment for mbed-os

This repository contains a small board-specific adjustment for mbed-os on the STM32F103x8.

## What was changed
The flash memory configuration was updated from 64 KB to 128 KB to match the actual device specification.

## Why
Some board definitions may not reflect the correct flash size for this STM32 variant.  
This adjustment helps ensure the firmware build uses the proper memory layout.

## Scope
This is a minimal, single-change repository focused on board configuration.

## Notes
This repository is useful as a reference for embedded firmware configuration on STM32F103-based boards.
