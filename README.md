長程通訊之OFDM信號特徵資料
===
我們使用光線追蹤模擬國立陽明交通大學校園的無線通訊環境，其緯度範圍為 24.78254 至 24.79097，經度範圍為 120.99236 至 121.00261。並根據根據3GPP TR38.901文件中所述的 Urban Macro(UMa)場景進行模擬。模擬參數如下表所示。所有通訊均假設為點對點，每筆資料僅包含一個發射端(Tx)和一個接收端(Rx)的資訊。

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


下表描述了資料集內容，包括Tx和Rx的座標、距離、仰角、頻率、Line-of-Sight狀態以及路徑損耗等資訊。
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
