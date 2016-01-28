# GyroDrive
Motorized microdrive with integrated gyroscope, accelerometer, and compass

## Connector
The connector is a 7-pin male nano dual row connector from Omnetics (part number A75243-001).

Here is the pinout solder pads, as viewed from above with the connector pins pointing up

```
|                                                                       |
|                              Connector                                |
|                                Body                                   |
|                                                                       |
|                                                                       |
|-----------------------------------------------------------------------|

  |------|  |------|  |------|  |------|  |------|  |------|  |------|
  |      |  |      |  |      |  |      |  |      |  |      |  |      |
  |  S1  |  |  S2  |  | SCL  |  | SDA  |  | -VS  |  | +VS  |  | STIM |
  |      |  |      |  |      |  |      |  |      |  |      |  | OUT  |
  |      |  |      |  |      |  |      |  |      |  |      |  |      |
  |------|  |------|  |------|  |------|  |------|  |------|  |------|

  |------|  |------|  |------|  |------|  |------|  |------|  |------|
  |      |  |      |  |      |  |      |  |      |  |      |  |      |
  | DGND |  |  IX  |  |  S3  |  |  S4  |  | ICOM |  | AGND |  | STIM |
  |      |  |      |  |      |  |      |  |      |  |      |  |  IN  |
  |      |  |      |  |      |  |      |  |      |  |      |  |      |
  |------|  |------|  |------|  |------|  |------|  |------|  |------|
```


Here is the same pinout for the connector pins, as viewed looking head on into the pins with the board on the bottom

```
   /                                                                /
  /                                                                /
 /                                                                /
|----------------------------------------------------------------|
| |------| |------| |------| |------| |------| |------| |------| |
| | STIM | | AGND | | ICOM | |  S4  | |  S3  | |  IX  | | DGND | |
| |  IN  | |      | |      | |      | |      | |      | |      | |
| |------| |------| |------| |------| |------| |------| |------| |
|                                                                |    
| |------| |------| |------| |------| |------| |------| |------| |
| | STIM | | +VS  | | -VS  | | SDA  | | SCL  | |  S2  | |  S1  | |
| | OUT  | |      | |      | |      | |      | |      | |      | |  /
| |------| |------| |------| |------| |------| |------| |------| | /
|----------------------------------------------------------------|/
                            Board side
```
