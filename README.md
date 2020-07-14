# Microchip 25x embedded-hal SPI driver crate

![](https://img.shields.io/crates/v/adxl313.svg)
![](https://docs.rs/adxl313/badge.svg)

Rust HAL implementation (using SPI drivers) for Microchip's 25 series EEPROM chips.

## Usage

Include [library](https://crates.io/crates/microchip-eeprom-25x) as a dependency in your Cargo.toml

```
[dependencies.microchip-eeprom-25x]
version = "<version>"
```

Use embedded-hal implementation to get SPI and a GPIO OutputPin for the chip select.

