# ili9486
Overlay for OrangePi3 screen ili9486 + xpt2046 (3.5inch rpi lcd)

"armbian-add-overlay ili9486-xpt2046/screen.dts"

Works on Amrbian v25.8.2 Noble kernel 6.12.47-sunxi64

With xinput, get pointer name : "DISPLAY=:0.0 xinput list"
then apply matrix to modify coordinates:
"DISPLAY=:0.0 xinput --set-prop 'ADS7846 Touchscreen' 'Coordinate Transformation Matrix' 0 -1 1 1 0 0 0 0 1"
