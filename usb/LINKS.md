# Links

A collection of USB related links.

## USB Overview

### Essential

["USB 101: An Introduction to Universal Serial Bus 2.0" by Robert Murphy](http://www.cypress.com/file/134171/download)

["USB in a NutShell" by Craig Peacock](http://www.beyondlogic.org/usbnutshell/usb1.shtml)

[2016: "Understand USB (in Linux)" by Opasiak Krzysztof](https://www.youtube.com/watch?v=JLhcE0O4bt0) [video] [[slides](http://events.linuxfoundation.org/sites/events/files/slides/Understand_USB_in_Linux_Opasiak_Krzysztof.pdf)]

### Specs

http://www.usb.org/developers

http://www.usb.org/developers/hidpage/HID1_11.pdf

http://www.usb.org/developers/docs/devclass_docs/usbmassbulk_10.pdf

### Attack surface

[2018: "Here's a List of 29 Different Types of USB Attacks" by Catalin Cimpanu](https://www.bleepingcomputer.com/news/security/heres-a-list-of-29-different-types-of-usb-attacks/) [article]

[Attacks via physical access to USB (DMA…?)](https://security.stackexchange.com/questions/118854/attacks-via-physical-access-to-usb-dma)

http://seclists.org/oss-sec/2017/q4/247

https://www.offensivecon.org/speakers/2018/markus-and-michele.html

### Connectors

http://www.usb.org/developers/onthego/london/OTG_mechanical.pdf

https://gct.co/usb-connector/micro-usb-connector-overview

### Hubs

[2017: "USB Snooping Made Easy: Crosstalk Leakage Attacks on USB Hubs" by Yang Su, Daniel Genkin, Damith Ranasinghe and Yuval Yarom](http://autoidlab.cs.adelaide.edu.au/sites/default/files/publications/papers/camera.pdf) [paper]

https://opensource.srlabs.de/projects/badusb/wiki/Hubs

https://github.com/mvp/uhubctl

https://github.com/codazoda/hub-ctrl.c

### Cameras

https://jscholarship.library.jhu.edu/bitstream/handle/1774.2/36569/camera.pdf?sequence=1&isAllowed=y

https://security.stackexchange.com/questions/6758/can-webcams-be-turned-on-without-the-indicator-light

https://raspberrypi.stackexchange.com/questions/43118/turning-off-the-blue-status-led-on-the-logitech-c920-usb-camera

https://github.com/cshorler/webcam-tools


## Linux USB stack

TODO: udev, usbfs, usbip, vhci

https://www.kernel.org/doc/Documentation/usb/

http://www.linux-usb.org/

[What actually happens when you plug in a USB device?](https://www.technovelty.org/linux/what-actually-happens-when-you-plug-in-a-usb-device.html) [article]

[2009: "Linux USB drivers" by Michael Opdenacker](https://bootlin.com/doc/legacy/linux-usb/linux-usb.pdf) [slides]

[2009: "USB Device Drivers A Stepping Stone into your Kernel" by Moritz Jodeit and Martin Johns](http://www.jodeit.org/research/DeepSec2009_USB_Device_Drivers.pdf) [slides]

http://processors.wiki.ti.com/index.php/USB_General_Guide_Linux_v3.8

https://www.kernel.org/doc/html/latest/driver-api/usb/index.html

[Bootstrap Yourself with Linux-USB Stack: Design, Develop, Debug, and Validate Embedded USB](http://index-of.es/OS/Linux-USB%20Stack.pdf) [book]

### usbmon

https://www.kernel.org/doc/Documentation/usb/usbmon.txt

https://wiki.ubuntu.com/Kernel/Debugging/USB

https://stackoverflow.com/questions/31054437/how-to-install-wireshak-on-linux-and-capture-usb-traffic

### Gadget subsystem

[Kernel USB Gadget Configfs Interface](http://events.linuxfoundation.org/sites/events/files/slides/USB%20Gadget%20Configfs%20API_0.pdf) [slides]

[Create your own USB gadget with GadgetFS](http://blog.soutade.fr/post/2016/07/create-your-own-usb-gadget-with-gadgetfs.html) [article]

[ConfigFS Gadget - An Introduction](https://www.slideshare.net/linaroorg/sfo15311-configfs-gadget-an-introduction) [slides]

https://github.com/gadgetd/gadgetd/wiki/Motivation

https://wiki.tizen.org/wiki/USB/Linux_USB_Layers/Configfs_Composite_Gadget/General_configuration

https://www.kernel.org/doc/htmldocs/gadget/

https://www.kernel.org/doc/Documentation/usb/functionfs.txt

https://www.kernel.org/doc/Documentation/usb/ (gadget: [testing.txt](https://www.kernel.org/doc/Documentation/usb/gadget_testing.txt), [configfs.txt](https://www.kernel.org/doc/Documentation/usb/gadget_configfs.txt), [hid.txt](https://www.kernel.org/doc/Documentation/usb/gadget_hid.txt), [multi.txt](https://www.kernel.org/doc/Documentation/usb/gadget_multi.txt), [printer.txt](https://www.kernel.org/doc/Documentation/usb/gadget_printer.txt), [serial.txt](https://www.kernel.org/doc/Documentation/usb/gadget_serial.txt))

http://www.linux-usb.org/usbtest/

http://www.linux-usb.org/gadget/ ([usb.c](http://www.linux-usb.org/gadget/usb.c) + [usbstring.c](http://www.linux-usb.org/gadget/usbstring.c) + [usbstring.h](http://www.linux-usb.org/gadget/usbstring.h))

https://sourceforge.net/p/hid-gadgetfs/code/ci/master/tree/

https://github.com/ueno/libusb-gadget

https://www.kernel.org/doc/Documentation/usb/gadget_hid.txt

https://github.com/qlyoung/keyboard-gadget


## Hardware

### Rubber Ducky

[Rubber Ducky](https://hakshop.com/products/usb-rubber-ducky-deluxe)

https://github.com/hak5darren/USB-Rubber-Ducky/wiki

### Bash Bunny

[Bash Bunny](https://hakshop.com/products/bash-bunny)

https://wiki.bashbunny.com/#!index.md

https://github.com/hak5/bashbunny-payloads

### Lan Turtle

[LAN Turtle](https://www.hak5.org/gear/lan-turtle)

https://www.hak5.org/gear/lan-turtle/docs

### Teensy

[Teensy 3.2](https://www.pjrc.com/store/teensy32.html)

[Teensy 2.0](https://www.pjrc.com/store/teensy.html)

[USB Serial](https://www.pjrc.com/teensy/td_serial.html), [USB Keyboard](https://www.pjrc.com/teensy/td_keyboard.html), [USB Mouse](https://www.pjrc.com/teensy/td_mouse.html), [USB Joystick](https://www.pjrc.com/teensy/td_joystick.html), [USB MIDI](https://www.pjrc.com/teensy/td_midi.html) and [USB Flight Sim](https://www.pjrc.com/teensy/td_flightsim.html)

[Getting started with Teensy](https://spuder.wordpress.com/2010/10/21/getting-started-with-teensy-usb-rubber-ducky/) [article]

https://github.com/PaulStoffregen/cores

#### TODO

https://github.com/ebursztein/malusb

https://github.com/samyk/usbdriveby

https://github.com/ihowson/Teensy-Raw-HID-in-Python

https://github.com/Screetsec/Pateensy

https://github.com/Screetsec/Brutal

https://github.com/samratashok/Kautilya

http://www.irongeek.com/i.php?page=security/programmable-hid-usb-keystroke-dongle

https://github.com/offensive-security/hid-backdoor-peensy

https://github.com/kbeflo/teensy-payloads

http://kevincuzner.com/2014/12/12/teensy-3-1-bare-metal-writing-a-usb-driver/

### ATtiny85 board

[AliExpress: ATtiny85 board](https://www.aliexpress.com/item/Free-shipping-1pcs-Digispark-kickstarter-development-board-ATTINY85-module-for-Arduino-usb/32697283942.html)

[1$ Rubber Ducky – Hack any PC within seconds MR.Robot style using Attiny85](http://www.khromozome.com/rubber-ducky-hack-pc-within-seconds-mr-robot-style-attiny85/)

https://github.com/toxydose/Duckyspark

https://github.com/micronucleus/micronucleus

### CJMCU BadUSB

[AliExpress: CJMCU BadUSB](https://www.aliexpress.com/item/CJMCU-virtual-Keyboard-Badusb-USB-TTF-memory-Keyboard-ATMEGA32U4-module/32817551271.html)

https://github.com/mharjac/bad_ducky

### Cactus WHID

[AliExpress: Cactus WHID](https://www.aliexpress.com/item/Cactus-Micro-compatible-board-plus-WIFI-chip-esp8266-for-atmega32u4/32318391529.html)

[AliExpress: Cactus Micro Rev2](https://www.aliexpress.com/item/Cactus-Micro-Rev2-Pro-Micro-atmega32u4-WIFI-ESP8266-module-ESP-11-ESP-03/32804236925.html)

https://github.com/whid-injector/WHID

### Raspberry Pi Zero

[Raspberry Pi Zero](https://www.raspberrypi.org/products/raspberry-pi-zero/)

[Turning your Raspberry PI Zero into a USB Gadget](https://learn.adafruit.com/turning-your-raspberry-pi-zero-into-a-usb-gadget) [article]

[Raspberry Pi Zero OTG Mode](https://gist.github.com/gbaman/50b6cca61dd1c3f88f41) [article]

https://github.com/mame82/P4wnP1 ([writeup](https://github.com/mame82/P4wnP1/blob/master/writeup_lockpicker.md))

https://twitter.com/_binkybear/status/919324503020150784

https://github.com/samyk/poisontap

https://github.com/darrylburke/RaspberryPiZero_HID_MultiTool/

https://github.com/theresalu/rspiducky

### BeagleBone Black

[BeagleBone Black](https://beagleboard.org/black)

https://github.com/dominicgs/USBProxy

[2014: "USB write blocking with USBProxy" by Dominic Spill](https://dominicspill.com/presentations/2014/Spill_BSidesLV_USBProxy_slides.pdf) [slides]

[2016: "USBiquitous: USB intrusion toolkit" by Benoit Camredon](https://www.sstic.org/media/SSTIC2016/SSTIC-actes/usb_toolkit/SSTIC2016-Article-usb_toolkit-camredon.pdf) [article]

http://beagleboard-usbsniffer.blogspot.de/

https://github.com/dominicgs/BeagleDancer

https://github.com/matlo/bb_usb_sniffer (beagleboard xM)

### USB armory

[USB Armory](https://inversepath.com/usbarmory)

[2015: "USB Armory as an Offensive Attack Platform"](https://raw.githubusercontent.com/wiki/inversepath/usbarmory/contrib/USB%20Armory%20as%20an%20Offensive%20Attack%20Platform%20Jeroen_van_Kessel-and-Nick_Triantafyllidis.pdf) [paper]

[2016: "Forging USB armory" by Andrea Barisani](https://dev.inversepath.com/download/usbarmory/forging_the_usb_armory.pdf) [slides] [[video]](https://www.youtube.com/watch?v=yG6eemBNyjM)

[2016: "Snagging creds from locked machines" by Rob Fuller](https://room362.com/post/2016/snagging-creds-from-locked-machines/) [article]

[2017: ARMORY SANDBOX – BUILDING A USB ANALYZER WITH USB ARMORY by Pedro Vilaca](https://www.sentinelone.com/blog/armory-sandbox-building-usb-analyzer-usb-armory/) [article]

### Android

https://github.com/pelya/android-keyboard-gadget

https://github.com/anbud/DroidDucky

https://github.com/anbud/DroidDucky

### Facedancer21

[Facedancer21](http://goodfet.sourceforge.net/hardware/facedancer21/)

[FaceDancer21 (USB Emulator/USB Fuzzer)](https://int3.cc/products/facedancer21)

[2012: "Emulating USB Devices with Python" by Travis Goodspeed](http://travisgoodspeed.blogspot.de/2012/07/emulating-usb-devices-with-python.html) [article]

[2012: "Emulating USB DFU to Capture Firmware" by Travis Goodspeed](http://travisgoodspeed.blogspot.de/2012/10/emulating-usb-dfu-to-capture-firmware.html) [article]

[2017: "FaceDancer 2.0" by Dominic Spill](https://www.youtube.com/watch?v=L3Ug9591Vag) [video]

https://github.com/ktemkin/Facedancer

https://github.com/travisgoodspeed/goodfet

https://github.com/nccgroup/umap

https://github.com/nccgroup/umap2

https://github.com/xairy/facedancer-utils

USB MitM with two Facedacer21 boards [1](https://github.com/withdk/badusb2-mitm-poc), [2](http://seclist.us/badusb-2-0-usb-mitm-poc.html)

### Other

[USB Kill](https://usbkill.com/)

http://wiki.yobi.be/wiki/Raspdancer

Beagle analyzers ([[1](https://www.totalphase.com/products/beagle-usb12/)], [[2](https://www.totalphase.com/products/beagle-usb480/)], [[3](https://www.totalphase.com/products/beagle-usb5000-v2-ultimate/)])

[OpenVizla](http://openvizsla.org/)

## Other

TODO: move to appropriate sections

[2017: "POTUS: Probing Off-The-Shelf USB Drivers with Symbolic Fault Injection" by James Patrick-Evans, Lorenzo Cavallaro, and Johannes Kinder](https://www.usenix.org/system/files/conference/woot17/woot17-paper-patrick-evans.pdf) [paper] [[slides](https://www.usenix.org/sites/default/files/conference/protected-files/woot17_slides_patrick-evans.pdf)]

[2017: "Exploiting USB/IP in Linux" by Ignat Korchagin](https://www.blackhat.com/docs/asia-17/materials/asia-17-Korchagin-Exploiting-USBIP-In-Linux.pdf) [slides]

[2015: "USB Attack to Decrypt Wi Fi Communications" by Jeremy Dorrough](https://media.defcon.org/DEF%20CON%2023/DEF%20CON%2023%20presentations/DEFCON-23-Jeremy-Dorrough-USB-Attack-to-Decrypt-Wi-Fi-Communications.pdf) [slides] [[video](https://www.youtube.com/watch?v=UWOxzfRUwis)]

[2015: "Introduction to USB and Fuzzing" by Matt DuHarte](https://www.youtube.com/watch?v=KWOTXypBt4E) [video] [[slides](https://github.com/CryptoMonkey/Conference-Presentations/blob/master/Defcon%2023%20(2015)%20-%20Introduction%20to%20USB%20and%20Fuzzing/Matt%20DuHarte%20-%20HHV%20-%20Introduction%20to%20USB%20and%20Fuzzing.pdf)]

[2015: "Don't Trust Your USB! How to Find Bugs in USB Device Drivers" by Sergej Schumilo, Ralf Spenneberg, and Hendrik Schwartke](https://www.blackhat.com/docs/eu-14/materials/eu-14-Schumilo-Dont-Trust-Your-USB-How-To-Find-Bugs-In-USB-Device-Drivers-wp.pdf) [paper] [[slides](https://www.blackhat.com/docs/eu-14/materials/eu-14-Schumilo-Dont-Trust-Your-USB-How-To-Find-Bugs-In-USB-Device-Drivers.pdf)] [[video](https://www.youtube.com/watch?v=OAbzN8k6Am4)]

[2014: "BadUSB - On Accessories that Turn Evil" by Karsten Nohl and Jakob Lell](https://srlabs.de/wp-content/uploads/2014/07/SRLabs-BadUSB-BlackHat-v1.pdf) [slides] [[video](https://www.youtube.com/watch?v=nuruzFqMgIw)]

[2014: "USB Attacks Need Physical Access Right? Not Any More…" by Andy Davis](https://www.blackhat.com/docs/asia-14/materials/Davis/Asia-14-Davis-USB-Attacks-Need-Physical-Access-Right-Not-Any-More.pdf) [slides] [[video](https://www.youtube.com/watch?v=90MIjgh5ESU)]

[2014: "USB for All!!1" by Jesse Michael and Mickey Shkatov](https://www.defcon.org/images/defcon-22/dc-22-presentations/Michael-Shkatov/DEFCON-22-Jesse-Michael-Mickey-Shkatov-USB-for-All!!-UPDATED.pdf) [slides]

[2012: "Fuzzing the USB in your devices" by Olle Segerdahl](https://olle.nxs.se/software/usbdevfuzz/fuzzing-usb-devices.pdf) [slides]

[2009: "USB Attacks: Fun with Plug and 0wn" by Rafael Dominguez Vega](https://www.defcon.org/images/defcon-17/dc-17-presentations/defcon-17-rafael_vega-usb_attacks.pdf) [slides]

[2014: "Lowering the USB Fuzzing Barrier by Transparent Two-Way Emulation" by Rijnard van Tonder and Herman Engelbrecht](https://www.usenix.org/system/files/conference/woot14/woot14-vantonder.pdf) [paper]

[2014: "Implementing an USB Host Driver Fuzzer" by Daniel Mende](https://www.troopers.de/media/filer_public/66/27/6627d987-0de1-4e1a-97a1-9acaa696253f/troopers14-implementing_an_usb_host_driver_fuzzer-daniel_mende.pdf) [slides]

[USB Complete: Everything You Need to Develop USB Peripherals](http://s.eeweb.com/members/mark_harrington/answers/1333179451-USB_Complete_3rdEdition.pdf) [book]

## Misc

https://github.com/ollseg/usb-device-fuzzing

[2017: "USBGuard: authorization for USB" by Nur Hussein](https://lwn.net/Articles/738306/) [article]

https://github.com/dkopecek/usbguard/

https://blog.lizzie.io/preventing-usb-attacks-with-grsecurity.html

https://github.com/errbufferoverfl/usb-canary

https://github.com/hephaest0s/usbkill

https://www.twitch.tv/ktemkin

https://greatscottgadgets.com/daisho/

https://github.com/sensepost/USaBUSe

https://opensource.srlabs.de/projects/badusb

https://github.com/RedBalloonShenanigans/MonitorDarkly

https://fail0verflow.com/blog/2014/hubcap-chromecast-root-pt1/

https://github.com/brandonlw/Psychson

https://vivibit.net/psychson2307final-en/

https://room362.com/post/2016/snagging-creds-from-locked-machines/

https://github.com/dbridges/logician

https://github.com/ondrejbudai/hidviz/

https://shop.malduino.com/

https://github.com/scanlime/vusb-analyzer

https://github.com/exploitagency/ESPloitV2

https://www.kitploit.com/2018/04/bad-ducky-rubber-ducky-compatible-clone.html

https://www.youtube.com/watch?v=QLEpwra_9o8

https://github.com/kkamagui/IRON-HID

https://github.com/bkerler/sahara_emulator

## Unsorted

http://www.usbmadesimple.co.uk/index.html

http://microchipdeveloper.com/usb:start

https://opensource.srlabs.de/projects/badusb

https://www.crowdsupply.com/sutajio-kosagi/tomu

https://github.com/basic4/USB-Rubber-Ducky-Clone-using-Arduino-Leonardo-Beetle

https://github.com/jerwuqu/ardoducky

https://github.com/Seytonic/Duckduino-microSD

https://github.com/golem445/bunny_payloads

http://www.keelog.com/hardware-keylogger/
