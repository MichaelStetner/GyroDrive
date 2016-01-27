# GyroDrive
Motorized microdrive with integrated gyroscope, accelerometer, and compass

## Connector
The connector is a 7-pin male nano dual row connector from Omnetics (part number A75243-001).

Here is the pinout solder pads, as viewed from above with the connector pins pointing up

|          |          |          |          |          |          |          |
|----------|----------|----------|----------|----------|----------|----------|
| Stim out |    S4    |    S3    |   AGND   |   ICOM   |    +VS   |    SCL   |
| Stim in  |    IX    |    -VS   |    S2    |    S1    |    DGND  |    SDA   |

Here is the same pinout for the connector pins, as viewed looking head on into the pins with the board on the bottom
|          |          |          |          |          |          |          |
|----------|----------|----------|----------|----------|----------|----------|
|    SDA   |   DGND   |    S1    |    S2    |   -VS    |    IX    | Stim in  |
|    SCL   |   +VS    |   ICOM   |   AGND   |    S3    |    S4    | Stim out |
