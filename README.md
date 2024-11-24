# Motorcycle-Brake-Light
A DIY brake light to add on a backpack to add extra visibilty and therefore safety while riding a motorcycle.
  
  
## Planning
### Components:
Right at the moment, the plan is to use the following:
- [ESP32-C6 By Seeed Studio](https://www.seeedstudio.com/Seeed-Studio-XIAO-ESP32C6-p-5884.html?srsltid=AfmBOoo6o02956hQTR9vnu1pgjvEA7_m28dqDyM4UgxMEgan_cpJ9a7k) (I just had this laying around)
- [3700mAh LiPo Battery](https://www.amazon.com/EEMB-3700mAh-Rechargeable-Connector-Certified/dp/B08215B4KK/ref=sr_1_1?crid=36859B1WBF5JJ&dib=eyJ2IjoiMSJ9.3Ww9yavLP8peVeDO_ag3TLgOy3EiX6JaPd0S89gt8oE.TS4QPSwMl5L7xDZ7w91JsimSg3LtFT5jgYOKAox2kPY&dib_tag=se&keywords=LP103395&qid=1732074148&sprefix=lp103395%2Caps%2C111&sr=8-1&th=1)
- [Lipo Rider Plus By Seeed Studio](https://www.seeedstudio.com/Lipo-Rider-Plus-p-4204.html)
- Accelerometer (I used [this](https://www.amazon.com/dp/B01DK83ZYQ/ref=twister_B078SS8NQV?_encoding=UTF8&psc=1) one
- 5v Red LED Strip Lighting (I used [this](https://www.amazon.com/KXZM-Powered-640LEDs-Brightness-Flexible/dp/B09XDHNKV3/ref=sr_1_6?crid=E4GKPUCCLMRU&dib=eyJ2IjoiMSJ9.HOIYbfqLYxU7CZV7Qv9pgD0V4UM_TjQf_GenN3G5rfs1kOopobVctOeV6N_1BXCOYPPkIW2Mlujch_vqALLMqlvXoP-30vtrzwFmymmjCoONKgcZDJlmVLPx5OSrmP4uFTd8PfyKMfI0A1pAf-15mcR7Sxol4aKSqhp2jzAfErkUwUQ21UvDCZ_XA4gfJcl1GVDtDO3b0tNGHjQ7C4ob5sstlhmNT0rDQObxYDXu7ADd720OD3TtuJDyYYCeOI7dinGKxfLRXPC585qV4McxOQQaZJTHbWZZc2SSkhXFnQU._tqigCIHi1PuJCQHl69XDPyfjVwFZuA9ErXhOKhVhrM&dib_tag=se&keywords=red%2Bstrip%2Bleds%2Bkxzm&qid=1732074740&sprefix=red%2Bstrip%2Bleds%2Bkxzm%2Caps%2C138&sr=8-6&th=1))
- An adequate transitor (I used [this](https://www.mouser.com/datasheet/2/149/SS8050-117753.pdf?srsltid=AfmBOoorqu-bw4KbcArd56MowXUMRYe-p6QwGt4TR1D0hBtsJHZYhA3X) one)
- 100ohm resistor or other properly calculated value
  
  
### Functionality:
The idea is to have a low power circut that will turn on red lights (or flash them) when you decelerate at a ceritan rate. The circut will be battery powered and safe for rainfall. I would also like to have the ability to make it go to sleep when it is not being used, that way you can always leave it on. I will need to learn how to do low power programming with the ESP32 here to accomplish this.  
  
### Resources:
- [Programming with the ESP32-C6](https://wiki.seeedstudio.com/xiao_esp32c6_getting_started/)
- [Low power programming with the ESP32](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-guides/low-power-mode/index.html)
- [ESP32 Low Power Modes](https://www.arrow.com/en/research-and-events/articles/esp32-power-consumption-can-be-reduced-with-sleep-modes)
