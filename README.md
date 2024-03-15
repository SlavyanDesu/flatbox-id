# Flatbox: Low profile hitbox-layout fightstick

Repository ini mencakup model 3D, file desain PCB, dan code yang diperlukan untuk membuat arcade controller seperti ini:

![Assembled Flatbox](hardware-rev2/images/Flatbox-rev2b-finished-product.jpg)

Terdapat lima versi utama Flatbox. Semuanya menggunakan switch Kailh low profile (choc v1). Tabel di bawah mencantumkan fitur-fitur utama masing-masing versi. Silakan lihat README setiap versi untuk penjelasan detail cara membuatnya.

versi | [rev1.1](hardware-rev1.1) | [rev2](hardware-rev2) | [rev3](hardware-rev3) | [rev4](hardware-rev4) | [rev5](hardware-rev5)
------- | ------------------------- | --------------------- | --------------------- | --------------------- | ---------------------
dimensi case | 218x128x10mm | 218x130x10mm | 218x130x10mm | 218x130x10mm | 218x126x10mm
kompatibilitas (menggunakan GP2040-CE) | PC, PS3 | PC, PS3 | PC, PS3, PS4 | PC, PS3, PS4, Switch | PC, PS3, PS4, Switch
add-on board | Arduino Pro Micro | - | [Brook PS3/PS4](https://www.brookaccessory.com/detail/58690501/) | - | [RP2040-Zero](https://www.waveshare.com/rp2040-zero.htm)
onboard chip | - | ATmega32U4 | - | RP2040 | -
port | micro USB | USB-C | USB-C | USB-C | USB-C
diperlukan SMT assembly | tidak | ya | ya | ya | tidak
firmware | [ATmega32U4](firmware-atmega32u4) | [ATmega32U4](firmware-atmega32u4) | [Brook](https://www.brookaccessory.com/download/PS3/) | [GP2040-CE](https://gp2040-ce.info/) | [GP2040-CE](https://gp2040-ce.info/)

