# OrangePi3

Overlay, screen ili9486 + xpt2046 (3.5inch rpi lcd)  
"armbian-add-overlay ili9486-xpt2046/orangepi3.dts"  
Works on Amrbian v25.8.2 Noble kernel 6.12.47-sunxi64  

| OrangePi3 (Function)       | Pin# | 3.5 inch LCD       |
|---------------------------|------|--------------------|
| 3.3V                      | 1    | -                  |
| 5V                        | 2    | -                  |
| PD12 (I2C0_SDA)           | 3    | -                  |
| 5V                        | 4    | -                  |
| PD11 (I2C0_SCL)           | 5    | -                  |
| GND                       | 6    | -                  |
| PD13 (GPIO_GCLK)          | 7    | -                  |
| PD8 (UART1_TX)            | 8    | -                  |
| GND                       | 9    | -                  |
| PD9 (UART1_RX)            | 10   | -                  |
| PD24 (UART3_RX)           | 11   | TP_IRQ             |
| PD15 (PWM0)               | 12   | -                  |
| PD14 (PWM1)               | 13   | -                  |
| GND                       | 14   | -                  |
| PD18 (GPIO3)              | 15   | -                  |
| PD16 (LCD_RS)             | 16   | LCD_RS             |
| 3.3V                      | 17   | -                  |
| PD16 (LCD_RS)             | 18   | LCD_RS             |
| PH5 (SPI1_MOSI)           | 19   | LCD_SI/TP_SI       |
| GND                       | 20   | -                  |
| PH6 (SPI1_MISO)           | 21   | TP_SO              |
| PD21 (RESET)              | 22   | RESET              |
| PH4 (SPI1_CLK)            | 23   | LCD_SCK/TP_SCK     |
| PH3 (SPI1_CS)             | 24   | LCD_CS             |
| GND                       | 25   | -                  |
| PL8 (TP_CS)               | 26   | TP_CS              |
| PD17 (GPIO2)              | 27   | -                  |
| PD10 (GPIO0)              | 28   | -                  |
| PD19 (GPIO4)              | 29   | -                  |
| GND                       | 30   | -                  |
| PD20 (GPIO5)              | 31   | -                  |
| PD22 (GPIO6)              | 32   | -                  |
| PD23 (GPIO7)              | 33   | -                  |
| GND                       | 34   | -                  |
| PL7 (GPIO8)               | 35   | -                  |
| PL10 (GPIO20)             | 36   | -                  |
| PL9 (GPIO16)              | 37   | -                  |
| PL11 (GPIO21)             | 38   | -                  |
| GND                       | 39   | -                  |
| PL12 (GPIO22)             | 40   | -                  |

※ LCDと直接繋ぐピンは「3.5 inch LCD」列に記載。それ以外は「-」で未接続です。  
※ OrangePi3のピン名称・機能は公式画像を参照しています。  
※ LCD端子名は機種によって若干異なる場合があります。

# Raspberry Pi 
