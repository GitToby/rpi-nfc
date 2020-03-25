Following [this](https://www.waveshare.com/wiki/PN532_NFC_HAT)

To make this work you need to execute the following on the rpi, which installs the correct python stuff:
```bash
sudo apt install python3-pip
sudo apt install python3-gpiozero
sudo pip3 install pyserial
sudo python3 example_get_uid.py
```