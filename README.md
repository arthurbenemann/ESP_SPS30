# ESP SPS30

## BOM
* Sensirion SPS30 sensor - [Amazon link](https://www.amazon.com/gp/product/B07M6RBLGL/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1) ([Datasheet](https://cdn.sparkfun.com/assets/4/e/e/f/8/Sensirion_PM_Sensors_Datasheet_SPS30.pdf),
[Mechanical design guide](https://cdn.sparkfun.com/assets/4/6/0/6/1/SPS30_Mechanical_Design_and_Assembly_Guidelines_v1.0_D1.pdf))

* ESP32-WROM devkit - [Amazon link](https://www.amazon.com/gp/product/B09XDMVS9N/ref=ppx_yo_dt_b_asin_title_o06_s00?ie=UTF8&psc=1)
* ESP_SPS30 3D printed case

# Wiring
|SPS30-PIN|Wire Color|NET|ESP-PIN|
|---------|----------|---|-------|
|1|Red    |VDD|VIN|
|2|White  |SDA|D21|
|3|Pur    |SCL|D22|
|4|Green  |SEL|GND|
|5|Black  |GND|GND|
