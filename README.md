# rpi-pico-meshtastic
Meshtastic firmware for Raspberry Pico.

### raspberry pico pinout

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

