# rpi-pico-meshtastic
Meshtastic firmware for Raspberry Pico / RP2040-LoRa.
Boards: rpipico, rpico2, rpipicow, rpipico2w, rp2040-lora

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

### Current consumption

```text
+-------------------+----------------------------------+-----------------------------------+
|       board       | approximate current consumption* | approximate current consumption** |
+-------------------+----------------------------------+-----------------------------------+
| raspberry pico    | 40-45 mA                         | 30mA (48Mhz) 35mA (72Mhz)         |
| raspberry pico w  | 95-100 mA (wifi on)              | ---                               |
|                   | 65 mA (wifi off)                 | ---                               |
| raspberry pico 2  | 40-45 mA                         | ---                               |
| raspberry pico 2w | 90-95 mA (wifi on)               | ---                               |
|                   | --- (wifi off)                   | ---                               |
| rp2040-lora       | 45 mA                            | ---                               |
+---------------------+--------------------------------+-----------------------------------+

* firmware without modification
** firmware with CPU frequency modification
```

### Links

### Meshtastic

- [Meshtastic Project](https://meshtastic.org)
- [Meshtastic Github](https://github.com/meshtastic)

### Raspberry Pico:

- [Raspberry Pico](https://datasheets.raspberrypi.com/pico/pico-datasheet.pdf)
- [Raspberry Pico W](https://datasheets.raspberrypi.com/picow/pico-w-datasheet.pdf)

### Raspberry Pico 2

- [Raspberry Pico 2](https://datasheets.raspberrypi.com/pico/pico-2-datasheet.pdf)
- [Raspberry Pico 2 W](https://datasheets.raspberrypi.com/picow/pico-2-w-datasheet.pdf)

### RP-2040-LoRa
- [RP2040-LoRa](https://www.waveshare.com/wiki/RP2040-LoRa)
