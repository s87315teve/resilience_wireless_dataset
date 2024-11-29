長程通訊之OFDM信號特徵資料
===

# Communication Parameter
| **Parameter**         | **Description**                           |
|------------------------|-------------------------------------------|
| Latitude              | 24.78254 - 24.79097                      |
| Longitude             | 120.99236 - 121.00261                    |
| Rx Height             | Random between 1 m and 22.5 m            |
| Rx Coordinates (X&Y)  | Random within map boundaries              |
| Tx Height             | 25 m                                     |
| Tx Coordinates (X&Y)  | Random within map boundaries              |
| Number of Tx          | 1,000 per frequency                      |
| Number of Rx          | 10,000 per Tx                            |
| Frequency             | 900 MHz, 2.6 GHz, 5.8 GHz                |
| Antenna Pattern       | Isotropic                                |
| Polarization Direction| Vertical                                 |
| Number of bounces     | 5                                        |



# Dataset Description
| **Contents**           | **Description**                             |
|-------------------------|---------------------------------------------|
| $Tx_x$                 | X coordinate of Tx (m)                     |
| $Tx_y$                 | Y coordinate of Tx (m)                     |
| $Tx_z$                 | Z coordinate of Tx (m)                     |
| $Rx_x$                 | X coordinate of Rx (m)                     |
| $Rx_y$                 | Y coordinate of Rx (m)                     |
| $Rx_z$                 | Z coordinate of Rx (m)                     |
| Distance               | Distance between Tx and Rx (m)             |
| Elevation angle        | Elevation angle between Tx and Rx ($^{\circ}$) |
| Frequency              | Radio frequency (GHz)                      |
| LOS status             | LOS status (1:LOS, 0:nLOS)                 |
| Path loss              | Path loss (dB)                             |
