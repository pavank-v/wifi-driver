RTL8188FU driver for Linux kernel 4.15.x ~ 6.7.x (Linux Mint, Ubuntu or Debian Derivatives)

info: rtl8188fu support added to rtl8xxxu module of Linux kernel with version 6.2. 

------------------

## How to install

`sudo apt-get install build-essential git dkms linux-headers-$(uname -r)`

`git clone https://github.com/pavank-v/wifi-driver/`

`sudo dkms install ./wifi-driver`

`sudo cp ./wifi-driver/firmware/rtl8188fufw.bin /lib/firmware/rtlwifi/`

