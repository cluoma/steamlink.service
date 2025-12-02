**This repo is extremely outdated and unlikely to work as intended.**

# steamlink.service
A systemd service file for Steam Link on Raspberry Pi

## How to install
```
git clone https://github.com/cluoma/steamlink.service
cd steamlink.service
sudo cp steamlink.service /etc/systemd/system/steamlink.service
sudo systemctl daemon-reload
sudo systemctl enable steamlink.service
```
Reboot your Pi and it should boot directly into Steam Link.

If you would like to disable the service, run:
```
sudo systemctl disable steamlink.service
```
