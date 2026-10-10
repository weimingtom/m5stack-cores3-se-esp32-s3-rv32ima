esptool.py --chip esp32s3 -b 921600 write_flash 0x200000 main/Image
idf.py build flash monitor
