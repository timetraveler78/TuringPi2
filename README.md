# TURING PI 2 Q & A

## DEVICE

### What are the TPI2 specifications?
Detailed specifications can be found at https://turingpi.com/

### Easier to use
We've changed the product so that it's much easier to use!

### Which compute modules does TPI2 support?
TPI2 currently supports Raspberry Pi CM4, Nvidia Jetson Nano version B01, Nvidia Jetson TX2 NX, Nvidia Jetson Xavier NX. You can find detailed information about the support in their respective FAQ category.

### What storage options are supported on TPI2?
TPI2 has a built in support for USB storage, SATA storage and NVMe storage. The specific support depends on the compute module used, as not all nodes have acces to all these options and some, like CM4, don't have PCIe lanes for the NVMe support. For detailed breakdown, please refer to this blogpost https://www.kickstarter.com/projects/turingpi/turing-pi-cluster-board/posts/3526884

### How is the TPI2 powered?
TPI2 uses the ATX standard. The maximum power output is 60W. Since a lot off standard power supplies are >500W, please make sure it can suport low loads, as some of them have undercurrent protection, which might be triggered with TPI2. PicoPSU is a recommended slution.

### Does TPI2 have any IPMI?
TPI2 uses an Allwinner T113-s3 to manage itself, like firmware and fan headers, as well as with which you can manage your nodes.

### What case do I need for TPI2?
TPI2 has a standard mini ITX size. Hight wise, you can use a 1.5U or 2U case or 68mm case hight.

### Can I plug SO-DIMM RAM stick into TPI2?
No.

### Can I hotplug Compute Modules into TPI2?
Yes

### Can I use the nvme slot with a Raspberry Pi Compute Module 4?
No, the compute module does not support the nvme slot, a jetson Nano B01, jetson tx2 NX or a Xavier NX does support it

### Can I run Turing RK1, Raspberry Pi and Nvidia Jetson modules at the same time?
You can run any combination of all supported compute modules.

## FIRMWARE

### Is the TPI2 firmware open source?
Not currently but it will be open sourced once the firmware is finalized.

### Where can I find the TPI2 firmware?
The firmware is currently not publicly available.

### How can I manage the connected fans through TPI2?
TBD

### Can I use a keyboard and mouse to access TPI2 itself?
Yes. Details can be found here https://www.kickstarter.com/projects/turingpi/turing-pi-cluster-board/posts/3514333

### Can I use a keyboard and mouse to access one of my nodes?
Yes. Details can be found here https://www.kickstarter.com/projects/turingpi/turing-pi-cluster-board/posts/3514333

### What can I do with TPI2 BMC?
With the BMC (baseboard management controller) the Turing Pi 2 firmware offers a set of remote management functions such as serial console over LAN, remote OS image flashing, authentication, self-testing, and Over-The-Air management

## DOCUMENTATION

### Where can I find the documentation for TPI2?
Documentation can be found at https://help.turingpi.com/. The documentation is currently a work in progess.

### When will be the documentation for TPI2 available?
Limited documentation is currently available and is currently being improved.

### Will the documentation for TPI2 include the documentation for RK1 as well?
TBD

### I've found the documentation for Turing Pi. Can I use that with TPI2?
No. Turing Pi V1 is a different device.

## LOGISTICAL

### When will TPI2 ship?
The turing Pi has been shipped to initial backers.

### When can I order TPI2?
The Turing Pi 2 can be ordered now from https://turingpi.com/.

### I need to make changes to my existing order. How?
TBD

### When will RK1 ship?
TBD

### When can I order RK1?
TBD

### When will RK1S ship?
TBD

### When can I order RK1S?
TBD

### Can I order just individual CM4 adapters?
TBD

### Where do you ship?
TBD

## RASPBERRY PI

## Whch Raspberry Pi Compute Modules are supported?
TPI2 supports all the regular CM4 and CM4 Lite variants.

## Do I need an adapter for CM4?
Yes.

## Can I use older CM3 in TPI2?
No.

## Does TPI2 support CM5?
CM5 has not been announced by the Raspberry Pi. We can't support what does not exist.

## Can I use the microSD slot on the CM4 adapter on CM4 with eMMC?
No. This is not possible, due to how the CM4 boards with eMMC are designed.

## Can I use the TPI2 to flash the eMMC on my CM4?
Yes.

## What coolers/heatsinks can I use with CM4 on TPI2?
TBD

## Does TPI2 come with CM4?
No

## Does the Raspberry Pi Compute Module support the NVMe slot?
No, you need to use a RK Compute Module or a jetson tx2 NX or a Xavier NX does support it.

## NVIDIA JETSON

### Which compute modules are supported?
Jetson Nano (version B01 only),  Jetson TX2 NX, Jetson Xavier NX


### Which coolers/heatsink can I with Nvidia Jetson on TPI2?
TBD

## TURING RK1

### Whats a Turing RK1?
TBD

### Does the Turing RK1 support the NVMe slot?
Yes.

## MISC

### Misc question 1?
TBD
