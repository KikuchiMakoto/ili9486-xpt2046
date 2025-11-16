# OrangePi3

Overlay, screen ili9486 + xpt2046 (3.5inch rpi lcd)  
"armbian-add-overlay ili9486-xpt2046/orangepi3.dts"  

## <font color="red"><b>IMPORTANT</b></font>  
On the OrangePi3, the original TP_IRQ pin does not support interrupts.  
Therefore, you need to connect it to a pin outside of Port D, which has very few interrupt-capable pins.  
However, as you can see from the table, only the PL pins are available, so TP_IRQ has been reassigned to PL10.  
When verifying operation, you cannot connect the board socket directly, so you will need to find a way to reconnect the wiring yourself.

## Pin Table
| OrangePi3 | IRQ | Pin# | 3.5 inch TouchPanel |
|-------------------------- |:-----------:|------|--------------------|
| 3.3V                      | ---         | 1    | -                  |
| 5V                        | ---         | 2    | -                  |
| PD26 (I2C0-SDA)           | no          | 3    | -                  |
| 5V                        | ---         | 4    | -                  |
| PD25 (I2C0-SCL)           | no          | 5    | -                  |
| GND                       | ---         | 6    | -                  |
| PD22 (PWM0)               | no          | 7    | -                  |
| PL2 (S-UART1-TX)          | no          | 8    | -                  |
| GND                       | ---         | 9    | -                  |
| PL3 (S-UART-RX)           | no          | 10   | -                  |
| PD24 (UART3_RX)           | no          | 11   | (TP_IRQ but no IRQ)|
| PD18                      | no          | 12   | -                  |
| PD23 (UART3_TX)           | no          | 13   | -                  |
| GND                       | ---         | 14   | -                  |
| PL10                      | yes         | 15   | TP_IRQ             |
| PD15                      | no          | 16   | LCD_RS             |
| 3.3V                      | ---         | 17   | -                  |
| PD16                      | no          | 18   | LCD_RS             |
| PH5 (SPI1_MOSI)           | yes         | 19   | LCD_SI/TP_SI       |
| GND                       | ---         | 20   | -                  |
| PH6 (SPI1_MISO)           | yes         | 21   | TP_SO              |
| PD21                      | no          | 22   | RESET              |
| PH4 (SPI1_CLK)            | yes         | 23   | LCD_SCK/TP_SCK     |
| PH3 (SPI1_CS)             | yes         | 24   | LCD_CS             |
| GND                       | ---         | 25   | -                  |
| PL8                       | yes         | 26   | TP_CS              |
