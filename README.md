## comandos para queimar o NodeMCU
```
esptool.py -p /dev/ttyUSB1 -b 9600 write_flash 0x00000 ../nodemcu-master-9-modules-2017-06-18-20-10-42-float.bin
esptool.py -p /dev/ttyUSB1 -b 9600 write_flash 0x3fc000 ../esp_init_data_default-1.bin 
```

