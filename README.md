# 3.5inch_LCD_PI

sudo apt-get update && sudo apt-get upgrade

sudo rm -rf LCD-show
git clone https://github.com/goodtft/LCD-show.git
chmod -R 755 LCD-show
cd LCD-show/

sudo ./LCD35-show

Ga naar: Menu > Preferences > Appearance Settings
Klik op het tabblad ‘Defaults' en selecteer de optie voor grootte, medium of kleine schermen.

sudo apt-get install matchbox-keyboard
Menu > Accessoires > Keyboard

sudo apt-get install -y xinput-calibrator
menubalk > Preferences > Calibrate Touchscreen

sudo reboot

sudo ./LCD-hdmi

