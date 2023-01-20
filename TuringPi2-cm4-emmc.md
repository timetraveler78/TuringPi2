# Installing linux on the CM4 with eMMC

The CM4 platform has a design limitation of a single PCI lane for storage. So if you have a CM4 with eMMC, you can't use the SD-card or the NVMe expansion slot at the back of the motherboard.
This also means you can't put an SD card in with pre-installed linux to image the eMMC. You have to use another matter of installation. This document provides the installation steps.

## Prerequisits

- Please have the rpiboot application installed on your desktop or laptop. 
  - Installation steps are excellently provided by Jeff Geerling on his blog: https://www.jeffgeerling.com/blog/2020/how-flash-raspberry-pi-os-compute-module-4-emmc-usbboot
  - Follow the steps for MAC / Linux / Windows up to installation of the product.
- Own a USB-A to USB-A cable to connect to your laptop. The writer of this document has success using this cable from Amazon: [USB-A to USB-A male cable]([https://www.amazon.nl/dp/B004TJ574C?&linkCode=sl2&tag=basthout-21&linkId=8036820d6df87ae1ba8ef957dfb32d40&language=nl_NL&ref_=as_li_ss_tl](https://www.amazon.nl/dp/B004TJ574C?&linkCode=sl2&linkId=8036820d6df87ae1ba8ef957dfb32d40&language=nl_NL&ref_=as_li_ss_tl))
- Make sure the node is powered off.
- Know how to login to the BMC webinterface

## Steps on the board:
1. Go to the web interface of the BMC module
2. Select the **USB** tab
3. select mode **DEVICE**
4. Select the node you want to modify
5. click **SUBMIT**
6. Select the **POWER** tab
7. Select the node you want to start
8. click **SUBMIT**

## Next on your laptop or desktop
1. Connect the cable to your laptop or desktop
2. start the application as described by blog and you should see the board connect and shortly after mounted to your laptop or desktop as an external drive
3. Now continue with the Raspberry Pi Installer to install your favorite flavour of Operating System

## After imaging the CM4 device
1. Make sure the drive is unmounted (Should have been done automatically by the imaging tool)
2. Disconnect the USB cable
3. Go to the BMC Web Interface
4. Select the **POWER** tab
5. Power off the node from the BMC Web interface
6. Select the **USB** tab
7. select mode **HOST**
8. Select the node you just finished imaging
9. click **SUBMIT**
10. Select the **POWER** tab
11. Select the node you want to start
12. click **SUBMIT**
