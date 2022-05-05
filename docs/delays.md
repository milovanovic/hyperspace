
|  FFT  | Triger → Poslednji podatak (RSP) | Triger → Prvi podatak (LVDS) | Prvi podatak (LVDS) → Poslednji podatak (LVDS) | Poslednji podatak (LVDS) → Prvi podatak (RSP) | Prvi podatak (RSP) → Poslednji podatak (RSP) |
| :---: | :------------------------------: | :--------------------------: | :--------------------------------------------: | :-------------------------------------------: | :------------------------------------------- |
| 1024  |           246.3 $\mu$s           |         72.3 $\mu$s          |                  36.3 $\mu$s                   |                  70.3 $\mu$s                  | 68.3 $\mu$s                                  |
|  512  |           229.3 $\mu$s           |         73.3 $\mu$s          |                  18.3 $\mu$s                   |                  70.3 $\mu$s                  | 68.3 $\mu$s                                  |
|  256  |           222.3 $\mu$s           |         75.3 $\mu$s          |                   9.3 $\mu$s                   |                  69.3 $\mu$s                  | 69.3 $\mu$s                                  |


| FFT + Flush | Triger → Poslednji podatak (RSP) | Triger → Prvi podatak (LVDS) | Prvi podatak (LVDS) → Poslednji podatak (LVDS) | Poslednji podatak (LVDS) → Prvi podatak (RSP) | Prvi podatak (RSP) → Poslednji podatak (RSP) |
| :---------: | :------------------------------: | :--------------------------: | :--------------------------------------------: | :-------------------------------------------: | :------------------------------------------- |
|    1024     |          129.72 $\mu$s           |         71.72 $\mu$s         |                  36.52 $\mu$s                  |                 10.92 $\mu$s                  | 10.52 $\mu$s                                 |
|     512     |          101.78 $\mu$s           |         72.26 $\mu$s         |                  18.26 $\mu$s                  |                  6.34 $\mu$s                  | 5.06 $\mu$s                                  |
|     256     |           89.98 $\mu$s           |         74.38 $\mu$s         |                  9.18 $\mu$s                   |                  3.42 $\mu$s                  | 2.78 $\mu$s                                  |
