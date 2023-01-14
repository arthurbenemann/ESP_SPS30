# ESP SPS30
![badge](https://github.com/arthurbenemann/ESP_SPS30/actions/workflows/ci.yml/badge.svg)

![PXL_20230114_184521038](https://user-images.githubusercontent.com/3289118/212491039-22c0bac6-4a43-45bc-b150-8a6c6f622340.jpg)

## BOM
* Sensirion SPS30 sensor - [Amazon link](https://www.amazon.com/gp/product/B07M6RBLGL/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1) ([Datasheet](https://cdn.sparkfun.com/assets/4/e/e/f/8/Sensirion_PM_Sensors_Datasheet_SPS30.pdf),
[Mechanical design guide](https://cdn.sparkfun.com/assets/4/6/0/6/1/SPS30_Mechanical_Design_and_Assembly_Guidelines_v1.0_D1.pdf))

* ESP32-WROM devkit - [Amazon link](https://www.amazon.com/gp/product/B09XDMVS9N/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1)
* ESP_SPS30 3D printed case

## Wiring
|SPS30-PIN|NET|ESP-PIN|
|---------|---|-------|
|1|VDD|VIN|
|2|SDA|D21|
|3|SCL|D22|
|4|SEL|GND|
|5|GND|GND|

![image](https://user-images.githubusercontent.com/3289118/212481728-9b806b40-0661-4293-aa94-51444974d3bb.png)

## Assembly
![PXL_20230114_183640578](https://user-images.githubusercontent.com/3289118/212491030-e100f6b7-35f0-45c1-a577-6c32d60a4a9e.jpg)
![PXL_20230114_183928563](https://user-images.githubusercontent.com/3289118/212491033-a07ae055-dce1-4241-9aac-1da28500173e.jpg)



## Home assistant
Add via ESPHome integration. Screenshot of dashboard:

![image](https://user-images.githubusercontent.com/3289118/212489890-bc62a2ff-fa65-45c3-ad43-9f0d2ca8f727.png)


