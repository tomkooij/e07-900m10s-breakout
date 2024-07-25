# e07-900m10s-breakout

Breakout board for [ebyte e07-900m10s CC1101 module](https://www.ebyte.com/en/product-view-news.html?id=1567)

Breakout board vs well-known (but usually not working) CC1101 module for size:
![breakout board vs cc1101 module](breakout.png)

Connected to waveshare ESP32 s3 mini (ramses_esp clone)
![ramses_esp with esp32s3](breakout_esp32s3mini.png)

 - The header is a standard .1" (2.54mm) PCB header.
 - C1 and C2 are 1206 SMD size
 - C1 = 100nF
 - C2 = 4.7uF
 - C2 is probably not needed, it is used as a buffer for large currents while sending.
 - Antenna connector is [PCB SMA female](https://nl.aliexpress.com/item/1005005708712726.html) (use standard 1.8mm board thickness)
 - The IPEX stamp antenna on the module should also be useable (not tested)

This is my first KiCad/PCB. I'm happy it works!

This repo contains the KiCad 8 files as well as the gerbers to produce the PCB.
I used JLPCB for my board. Just upload the zip-file in the gerber folder to JLPCB.
