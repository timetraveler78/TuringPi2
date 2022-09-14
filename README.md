============================================================
===================TURING PI 2 DEVICE=======================
============================================================

#1
Q: What are the TPI2 specifications?
A: Detailed specifications can be found at https://turingpi.com/

#2
Q: Which compute modules does TPI2 support?
A: TPI2 currently supports Raspberry Pi CM4, Nvidia Jetson Nano version B01, Nvidia Jetson TX2 NX, Nvidia Jetson Xavier NX. You can find detailed information about the support in their respective FAQ category.

#3
Q: What storage options are supported on TPI2?
A: TPI2 has a built in support for USB storage, SATA storage and NVMe storage. The specific support depends on the compute module used, as not all nodes have acces to all these options and some, like CM4, don't have PCIe lanes for the NVMe support. For detailed breakdown, please refer to this blogpost https://www.kickstarter.com/projects/turingpi/turing-pi-cluster-board/posts/3526884

#4
Q: How is the TPI2 powered?
A: TPI2 uses the ATX standard. The maximum power output is 60W. Since a lot off standard power supplies are >500W, please make sure it can suport low loads, as some of them have undercurrent protection, which might be triggered with TPI2. PicoPSU is a recommended slution.

#5
Q: Does TPI2 have any IPMI?
A: TPI2 uses an Allwinner T113-s3 to manage itself, like firmware and fan headers, as well as with which you can manage your nodes.

#6
Q: What case do I need for TPI2?
A: TPI2 has a standard mini ITX size. Hight wise, you can use a 1.5U or 2U case or 68mm case hight.

#7
Q: Can I plug SO-DIMM RAM stick into TPI2?
A: No.

#8
Q: Can I hotplug Compute Modules into TPI2?
A: Yes

#9
Q: Can I run Turing RK1, Raspberry Pi and Nvidia Jetson modules at the same time?
A: You can run any combination of all supported compute modules.

============================================================
=======================FIRMWARE=============================
============================================================

#1
Q: Is the TPI2 firmware open source?
A: Not currently but it will be open sourced once the firmware is finalized.

#2
Q: Where can I find the TPI2 firmware?
A: The firmware is currently not publicly available.

#3
Q: How can I manage the connected fans through TPI2?
A: TBD

#4
Q: Can I use a keyboard and mouse to access TPI2 itself?
A: Yes. Details can be found here https://www.kickstarter.com/projects/turingpi/turing-pi-cluster-board/posts/3514333

#5
Q: Can I use a keyboard and mouse to access one of my nodes?
A: Yes. Details can be found here https://www.kickstarter.com/projects/turingpi/turing-pi-cluster-board/posts/3514333

#6
Q: What can I do with TPI2 BMC?
A: TBD

#7
Q:
A:

#8
Q:
A:

#9
Q:
A:

============================================================
====================DOCUMENTATION===========================
============================================================

#1
Q: Where can I find the documentation for TPI2?
A: The documentation is not yet available.

#2
Q: When will be the documentation for TPI2 available?
A: TBD

#3
Q: Will the documentation for TPI2 include the documentation for RK1 as well?
A: TBD

#4
Q: I've found the documentation for Turing Pi. Can I use that with TPI2?
A: No. Turing Pi V1 is a different device.

#5
Q:
A:

#6
Q:
A:

#7
Q:
A:

#8
Q:
A:

#9
Q:
A:

============================================================
======================LOGISTICAL============================
============================================================

#1
Q: When will TPI2 ship?
A: TBD

#2
Q: When can I order TPI2?
A: TBD

#3
Q: I need to make changes to my existing order. How?
A: TBD

#4
Q: When will RK1 ship?
A: TBD

#5
Q: When can I order RK1?
A: TBD

#6
Q: When will RK1S ship?
A: TBD

#7
Q: When can I order RK1S?
A: TBD

#8
Q: Can I order just individual CM4 adapters?
A: TBD

#9
Q: Where do you ship?
A: TBD

============================================================
====================RASPBERRY PI============================
============================================================

#1
Q: Whch Raspberry Pi Compute Modules are supported?
A: TPI2 supports all the regular CM4 and CM4 Lite variants.

#2
Q: Do I need an adapter for CM4?
A: Yes.

#3
Q: Can I use older CM3 in TPI2?
A: No.

#4
Q: Does TPI2 support CM5?
A: CM5 has not been announced by the Raspberry Pi. We can't support what does not exist.

#5
Q: Can I use the microSD slot on the CM4 adapter on CM4 eith eMMC?
A: No. This is not possible, due to how the CM4 boards with eMMC are designed.

#6
Q: Can I use the TPI2 to flash the eMMC on my CM4?
A: Yes.

#7
Q: What coolers/heatsinks can I use with CM4 on TPI2?
A: TBD

#8
Q: Does TPI2 come with CM4?
A: No

#9
Q:
A:

============================================================
====================NVIDIA JETSON===========================
============================================================

#1
Q: Which compute modules are supported?
A: TBD

#2
Q: Which coolers/heatsink can I with Nvidia Jetson on TPI2?
A: TBD

#3
Q:
A:

#4
Q:
A:

#5
Q:
A:

#6
Q:
A:

#7
Q:
A:

#8
Q:
A:

#9
Q:
A:

============================================================
=====================TURING RK1=============================
============================================================

#1
Q: Whats a Turing RK1?
A: TBD

#2
Q: 
A:

#3
Q:
A:

#4
Q:
A:

#5
Q:
A:

#6
Q:
A:

#7
Q:
A:

#8
Q:
A:

#9
Q:
A:

============================================================
========================MISC================================
============================================================

#1
Q: 
A:

#2
Q:
A:

#3
Q:
A:

#4
Q:
A:

#5
Q:
A:

#6
Q:
A:

#7
Q:
A:

#8
Q:
A:

#9
Q:
A:
