# ASUS-h81m-k
Hackintosh OpenCore-0.9.0 EFI for ASUS h81m-k i7-4790 rx570


## Device list
- [Motherboard](https://www.asus.com/ru/motherboards-components/motherboards/business/h81mk/) - ASUS h81m-k
- [CPU](https://ark.intel.com/content/www/ru/ru/ark/products/80806/intel-core-i74790-processor-8m-cache-up-to-4-00-ghz.html) - Intel® Core™ i7-4790
- [GPU](https://www.sapphiretech.com/ru-ru/consumer/nitro-rx-570-4g-g5-oc) - Sapphire Radeon RX 570 Nitro+ 4gb
- Memory - ddr3 4x2 8gb 1600mhz
- [HDD](https://shop.kz/offer/zhestkiy-disk-hdd-1000-gb-western-digital-wd10ezex-3-5-64mb-sata-iii-blue/) - WD Blue 1tb
- [SSD](https://www.kingspec.com/product/2-5-inch-p3-ssd.html) - SATA  256 GB KingSpec P3-256, SATA 6Gb/s


## The list of devices I will change and connect
- [WiFi and Bluetooth](https://aliexpress.ru/item/32746786692.html?spm=a2g2w.orderdetail.0.0.51534aa6BlpgDm&sku_id=12000029914879486) - FENVI T919 BCM94360
- [Memory](https://shop.kz/offer/ddr-3-dimm-8gb-1600mhz-pc12800-apacer-box/) - ddr3 8x2 16gb 1600mhz


## My BIOS Settings
- Advanced>SATA Configuration>SATA Mode Selection = AHCI
- Advanced>System Agent Configuration>VT-d = Enabled
- Boot>Fast Boot = Disabled
- Boot>CSM = Disabled
- Boot>Secure Boot>OS Tyoe = OtherOS
### WOL Settings
- Advanced>Onboard Devices Configuration>Realtek PXE Ontion ROM = Enabled
- Advanced>APM>Power On By PCI-E = Enabled

 
## Experience
> Я не специалист и не знаю как проверить все устройство и на скаолько я правильно завел все что у меня подключено

### Installation problems
Из начально пробовал установить через `Macrecovery` не получилось в логах были ошибки что то связано с Bluetooth перезаписовал все несколько раз на флешку результат такой же 

### Solution gaps
> Решил записать образ формата rdr на 16gb флешку и подсунуть свой EFI 

Список ресурсов или откуда я скачал Soft and Images(rdr)
- [Telegram channel](https://t.me/MacWin21) - Тут я нашел образ
- [Monterey image](https://drive.google.com/drive/folders/1R8CjFun9307mMlhkHwkEvKyfEMm95w-W) - Тут образ rdr
- [R-Drive Image для Windows](https://www.softportal.com/software-39233-r-drive-image.html) - R-Drive пробной версий хватит с гловой

## List of useful URL
- [Aleksey_Konovalov](https://www.youtube.com/@Aleksey_Konovalov) - Нудный канал но есть полезные видосы типа как записать на флешку образ, как работает OpenCore и т.д
- [Boronenkov](https://www.youtube.com/@Boronenkov) - У этого канала полезные видосы по Hachintosh, kext, aml и т.д
