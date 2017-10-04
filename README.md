# dd-bootable-usb
A better way to create bootable USB drives using dd command.

## `dd-bootable-usb` vs `dd`
1- This script will make sure everything is safe before copying data to your USB drive. You don't have to worry about copying data to your hard drive instead of your USB drive because USB devices only are accepted.

2- This script uses `pv` to show a progress bar.

## How to use
Read `dd-bootable-usb.sh`, make sure all options are good for your own use case and finally run:
```bash
./dd-bootable-usb.sh FILE_NAME USB_DEVICE
```
