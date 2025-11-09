# OrangePi3

Overlay, screen ili9486 + xpt2046 (3.5inch rpi lcd)  
"armbian-add-overlay ili9486-xpt2046/orangepi3.dts"  
Works on Amrbian v25.8.2 Noble kernel 6.12.47-sunxi64  

|Pin#|3.5 inch LCD| OrangePi3 |
| ---- | ---- | ---- |
|11|TP_IRQ|PD24(alt:UART3_RX)|
|18|LCD_RS|PD16|
|19|LCD_SI/TP_SI|PH5(SPI1_MOSI)|
|21|TP_SO|PH6(SPI1_MISO)|
|22|RESET|PD21|
|23|LCD_SCK/TP_SCK|PH4(SPI1_CLK)|
|24|LCD_CS|PH3(SPI1_CS)|
|26|TP_CS|PL8|

# Raspberry Pi 
