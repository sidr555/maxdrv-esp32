# wi-frost-firmware

### Install espruino with command
python ../../esptool/esptool.py --port /dev/ttyUSB0 --baud 115200 write_flash   --flash_freq 80m --flash_mode qio --flash_size 4MB-c1   0x0000 "boot_v1.6.bin" 0x1000 espruino_esp8266_user1.bin   0x3FC000  esp_init_data_default.bin 0x3FE000 blank.bin

### Update API server params in config var

### Upload flash with Espruino Web IDE




