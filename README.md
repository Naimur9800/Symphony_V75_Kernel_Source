> This is 3.18.19+ MT6580 kernel source which is Fully stable for Symphony V75

## Known information
| Subsystem | Driver name | Availability | Working |
|-----------|-------------|--------------|---------|
| LCM driver #1 | `hx8394d_dsi_vdo_hlt_hsd_hd720` | Yes | Yes |
| Touch panel | `GT9XX (i2c 1-005D)` | Yes | Yes |
| Charge | `BQ24158 (i2c 1-006A)` | Yes | Yes |
| GPU | `Mali-400 MP` | Yes | Yes |
| Camera #1 | `ov5670_mipi_raw` | Yes | Yes |
| Camera #2 | `sp2508_mipi_raw` | Yes | Yes |
| Accelerometer | `BMA222 (i2c 2-0018)` | Yes | Yes |
| ALS/PS | `ltr553` | Yes | Yes |
| Flash | `H8G1e` | Yes | Yes |
| Lens #4 | `MAINAF,GAF001AF,FM50AF,GAF002AF` | Yes | Yes |
| RAM | `1GB` | Yes | Yes |
| Sound | `mtsndcard` | Yes | Yes |
| Accdet | `mt6580-accdet` | Yes | Yes |
| Other | `kd_camera_hw (i2c 0-0010)` | Yes | Yes |
| Other | `kd_camera_hw_bus2 (i2c 0-0036)` | Yes | Yes |


> Bugs :

>> * Touch not responding in Twrp {Working on it...}

** Config name for V75_mt6580 --$   v2800_defconfig

## Acknowledgements

(Credit)

 * [Parthib Rkr](https://github.com/parthibx24)
