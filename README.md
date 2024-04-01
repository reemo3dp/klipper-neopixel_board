# High Level Notes

- STM32 or RP2040 MCU (what's the difference?)
- Connectivity
  - USB
  - UART
  - CAN
  - I2C / SPI ports
  - SWD header
- 4-Port Level Shifter (e.g. 74AHCT125) for 5V data
- Dedicated stepdowns for 12V and 5V power for neopixels
- 4 Neopixel Lines
  - Each with one JST-XH 4p (DIN, DOUT, 5V, GND) and one JST-XH 3p (DIN, 5V, GND)
- Replacable car fuses (2A/5A) for each Neopixel out
- All other GPIOs exposed + 5V/12V/VCC
