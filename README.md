![ESP32C3-1 44-01-250](https://github.com/jblance/ESP32C3_1.44inch/assets/1266998/493165fc-655c-428d-be0b-3ff0d213c4b2)


# Overview
- ESP32 C3 desktop trinket Mini TV Portable Pendant LVGL 1.44inch LCD ST7735
- Part Number： ESP32C3-1.44
- Brand： Spotpear
- SKU： 0601026
## Features
- Power supply: 5V
- Display driver interface: SPI
- Screen driver IC: ST7735S
- Screen resolution: 128×128
- Compatible battery type: 3.7V lithium battery with 1.27mm plug
- Main control: ESP32 C3 with WiFi and Bluetooth capability.

# Links
- [orginal document](https://spotpear.com/index/study/detail/id/1121.html?spm=a2g0o.detail.1000023.1.40cbUudqUudq6A)
- [schematic diagram](https://cdn.static.spotpear.com/uploads/picture/product/esp32/ESP32C3-1.44/Schematic/ESP32-C3-1.44inch.pdf)
- [original code repo](https://github.com/Spotpear/ESP32C3_1.44inch)

# Dev Environment
- Build the dev environment [instructions](https://www.spotpear.com/index.php/index/study/detail/id/992.html)
- Third party library file configuration:
  - Enter the mainapp project, change to your own WIFI name and password within
  - Adjust dev environment configuration parameters ![parameters](https://github.com/jblance/ESP32C3_1.44inch/assets/1266998/07dbf861-c322-45f4-bb34-e12ba6668b6d)
  - After the modifications are completed, you can configure parameter compilation ![6-config](https://github.com/jblance/ESP32C3_1.44inch/assets/1266998/e2f2d99e-cb23-4475-b650-ee6ff8f753f5)

# Replacing Middle Rotation Symbols
- Crop corresponding GIF pixels
  - Online website： https://ezgif.com/resize
  - Crop to 30 * 31 pixels
  - Convert GIF files to. c files
  - Online Image Converter Website： https://lvgl.io/tools/imageconverter
  - Enter the website to configure the corresponding settings ![resize](https://github.com/jblance/ESP32C3_1.44inch/assets/1266998/fc4fc438-4b4f-4b18-8242-7168b4766c99)
  - Copy the obtained xm.c file to the miniapp folder
  - Change the TKR_A in the miniapp. ino code to xm (change to your own name), there are two TKR_A instances in the project ![codeg](https://github.com/jblance/ESP32C3_1.44inch/assets/1266998/bde41fbb-75a3-4756-a493-6224fd191ae7)
  - Click to upload
