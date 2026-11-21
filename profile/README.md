# soccentric-stm32

A complete, reproducible firmware baseline for the **STM32F767ZI** (NUCLEO-F767ZI): a dual-bank A/B bootloader with UART update and rollback, demo applications on three RTOS stacks, and the validation and factory tooling around them.

**Project site:** https://soccentric-stm32.github.io/

## Bootloader

| Repository | What it is |
|---|---|
| [bootloader](https://github.com/soccentric-stm32/bootloader) | A/B bootloader: dual-bank, UART (HWLINK) update, CRC32, trial boot and rollback |
| [bootloader-gui](https://github.com/soccentric-stm32/bootloader-gui) | BOOT Flasher: desktop GUI for the bootloader |

## Applications

| Repository | Stack |
|---|---|
| [app-c-freertos](https://github.com/soccentric-stm32/app-c-freertos) | C on FreeRTOS |
| [app-c-zephyr](https://github.com/soccentric-stm32/app-c-zephyr) | C on Zephyr |
| [app-rust-freertos](https://github.com/soccentric-stm32/app-rust-freertos) | Rust on FreeRTOS |
| [app-rust-zephyr](https://github.com/soccentric-stm32/app-rust-zephyr) | Rust on Zephyr |
| [app-rust-embassy](https://github.com/soccentric-stm32/app-rust-embassy) | Rust on Embassy |

## Validation

| Repository | What it is |
|---|---|
| [validation-firmware](https://github.com/soccentric-stm32/validation-firmware) | HWVAL: FreeRTOS hardware validation firmware |
| [validation-gui](https://github.com/soccentric-stm32/validation-gui) | HWVAL Studio: PySide6 GUI for tests and firmware update |

## Factory

| Repository | What it is |
|---|---|
| [factory-firmware](https://github.com/soccentric-stm32/factory-firmware) | Writes `.sys`, `.cal` and `.diag` factory data over UART |
| [factory-data-gui](https://github.com/soccentric-stm32/factory-data-gui) | Generates factory data files from CSV |
| [factory-station](https://github.com/soccentric-stm32/factory-station) | End-of-line test and provisioning station |

## Website

[soccentric-stm32.github.io](https://github.com/soccentric-stm32/soccentric-stm32.github.io) hosts the project site.
