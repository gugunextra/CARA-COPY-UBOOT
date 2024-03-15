# CARA-COPY-UBOOT

Masuk ke terminal sebagai super user, ketik : 
 - su
 - cd sdcard/Download
 - Ketik perintah:   dd if=uboot.bin of=/dev/block/bootloader
 - reboot update

Solusi jika tidak bisa boot ke linux, pake uboot milik HG680-P karena bootloader bawaan B860H tidak mengijinkan boot dari external.
