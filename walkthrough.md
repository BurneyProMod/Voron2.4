#Setting up BTTpi on FreshOS
The U2C bridge must use USB2
installed kiauh
installed klipper, moonraker, mainsail, klipperscreen, crowsnext
Following this guide: https://canbus.esoterical.online/
Installed Katapult
Flashed main board
mainboardID: 
/dev/serial/by-id/usb-katapult_stm32h723xx_14002C001751313434373135-if00
toolhead UUID: bfa24e600d1c
Plugged U2C into pi with usb cable
Set up makemenu config in ~/katapult: https://github.com/Esoterical/voron_canbus/assets/124253477/e9850f4a-d4d9-438b-8b95-3fd21cd790d8
make clean
make
Put Octopus v1.1 in DFU mode
Ran lsusb on pi and confirmed: STMicroelectronics STM Device in DFU mode