# e2d-hi3798mv200
STB Hisilicon SoC Hi3798Mv200 running Debian Buster with Enigma2 v6.4 + KODI v19-alpha with (HW Video Decoding) + RetroArch v1.8.5

## Kernel Download
***Download:*** [uImage](uImage_hi3798mv200_v4.4.35)

***Warning:*** To compile Kernel you can check [WIKI](../../wiki).


## SDCard Image Download
This image is compatible with both SoC Hi3798Cv200 and Hi3798Mv200.

***Download:*** [e2d-armhf-pixel.img_20210226.tar.bz2](https://leandro.azsat.org/2021-02-26/e2d-armhf-pixel.img_20210226.tar.bz2)

***Warning:*** To Extract ROOTFS from IMG file you can check [WIKI](../../wiki).

## Write SDCard Image
***Windows:*** [Win32DiskImager](https://sourceforge.net/projects/win32diskimager/)

***Linux:***
```shell
# Warning: Change /dev/mmcblk1 to you SDCard Device example: /dev/sda
dd if=/media/sda1/e2d-armhf-pixel.img of=/dev/mmcblk1
```