# doppler4arduino

Use this Link in Arduino IDE 
Arduino->Settings->Board URLs
https://noscene.github.io/doppler4arduino/package_doppler_index.json


```
/*
 * 
 * DOPPLER-Board-Layout: 
 *                                                                                    ---------------- FPGA Pins ------------------
 *                                                                                   LedR LedG LedB
 * DIL Pin 48   47   46   45   44   43   42   41   40   39   38   37   36   35   34   33   32   31   30   29   28   27   26   25
 *       |--O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O---|
 * name  | VIN  5V  3.3V PA11 PA10 PA09 PA08 PA07 PA06 PA05 PA04 PB09 PB08 PA02  GND  F41  F40  F39  F38  F37  F36  F35  F34  F32  |
 *       |                                                                                            ö  ö  ö  ö                   |
 *      |                                                                                             ö  ö  ö  ö         |BTN:S1|  |
 *     | USB                           DOPPLER: SamD51 <- SPI -> icE40        |BTN:RESET|             ö  ö  ö  ö                   |
 *      |                                                                                             ö  ö  ö  ö         |BTN:S2|  |
 *       |                                                                                                                         |
 * name  | GND PA13 PA12 PB11 PB14 PA15 PB10 PA31 PA30  RES PA19 PA20 PA21 PA22 3.3V  F11  F12  F13  F18  F19  F20  F21  F23  F25  |
 *       L--O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O----O---|
 * DIL Pin  1    2    3    4    5    6    7    8    9   10   11   12   13   14   15   16   17   18   19   20   21   22   23   24
 *             SCL  SDA                       SWD  SWC RES
 *             -- I2C--                       --- SWD  ---   ----- Shared  -----      ---------------- FPGA Pins ------------------
 */
```

