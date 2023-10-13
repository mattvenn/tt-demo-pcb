# TinyTapeout Demo Board

## Documentation

## RP2040 Pinout

| TT Pin    | RP2040 Pin | I2C      | SPI      | UART     |
| --------- | ---------- | -------- | -------- | -------- |
| ui_in[0]  | GPIO9      |          | SPI1.cs  |          |
| ui_in[1]  | GPIO10     |          | SPI1.sck |          |
| ui_in[2]  | GPIO11     |          | SPI1.tx  |          |
| ui_in[3]  | GPIO12     |          |          | UART0.tx |
| ui_in[4]  | GPIO17     |          | SPI0.cs  |          |
| ui_in[5]  | GPIO18     |          | SPI0.sck |          |
| ui_in[6]  | GPIO19     |          | SPI0.tx  |          |
| ui_in[7]  | GPIO20     |          |          |          |
| uo_out[0] | GPIO3 \*   |          |          |          |
| uo_out[1] | GPIO4 \*   |          |          |          |
| uo_out[2] | GPIO7 \*   |          |          |          |
| uo_out[3] | GPIO8 \*   |          | SPI1.rx  |          |
| uo_out[4] | GPIO13     |          |          | UART0.rx |
| uo_out[5] | GPIO14     |          |          |          |
| uo_out[6] | GPIO15     |          |          |          |
| uo_out[7] | GPIO16     |          | SPI0.rx  |          |
| uio[0]    | GPIO21     |          |          |          |
| uio[1]    | GPIO22     | I2C1.scl |          |          |
| uio[2]    | GPIO23     | I2C1.sda |          |          |
| uio[3]    | GPIO24     |          |          |          |
| uio[4]    | GPIO25     |          |          |          |
| uio[5]    | GPIO26     |          |          |          |
| uio[6]    | GPIO27     |          |          |          |
| uio[7]    | GPIO28     |          |          |          |

\* These pins are multiplexed. They are connected to the RP2040 when GPIO1 is high.
