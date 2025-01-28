# rpi-pico-meshtastic
Meshtastic firmware for Raspberry Pico.

### Raspberry Pi Pico pinout

```bash
+------------+--------+------------------------------------------+
|    LoRa    |  Pico  | Features                                 |
+------------+--------+------------------------------------------+
| VCC        |  VSYS  | Power Input                              |
| GND        |  GND   | Ground                                   |
| LoRa_BUSY  |  GP2   | Busy status output pin                   |
| LoRa_CS    |  GP3   | SPI chip selection pin (low active)      |
| LoRa_CLK   |  GP10  | SPI communication SCK pin, clock input   |
| LoRa_MOSI  |  GP11  | SPI communication MOSI pin, data input   |
| LoRa_MISO  |  GP12  | SPI communication MISO pin, data output  |
| LoRa_RESET |  GP15  | Reset pin (low active)                   |
| LoRa_DIO1  |  GP20  | SX1262 interrupt output pin              |
| BAT_AD     |  GP26  | Onboard battery ADC pin                  |
+------------+--------+------------------------------------------+
```

### Links

- [Meshtastic Project](https://meshtastic.org)
- [Meshtastic Github](https://github.com/meshtastic)

- [Raspberry Pico](https://datasheets.raspberrypi.com/pico/pico-datasheet.pdf)
- [Raspberry Pico W](https://datasheets.raspberrypi.com/picow/pico-w-datasheet.pdf)

- [Raspberry Pico 2](https://datasheets.raspberrypi.com/pico/pico-2-datasheet.pdf)
- [Raspberry Pico 2 W](https://datasheets.raspberrypi.com/picow/pico-2-w-datasheet.pdf)
