# pi-gba
A simple, easy to assemble, DIY retro gaming handheld.

The pi-gba was designed to be pretty easy to build. Order the pcb, parts, and 3d print the case, and assembly is straightforward. The pi, battery board, and usbc breakout are placed on top of and soldered directly to the main board.

### images
![Shell](images/shell.png)
![PCB](images/pcb.png)

### software
Flash the latest image of [retropie](https://retropie.org.uk/download/) using the raspberry pi imager. Make sure SSH is enabled and ssh into the pi from another computer (instructions [here](https://retropie.org.uk/docs/SSH/)). 
I recommend installing the [fbcp-ili9341](https://github.com/juj/fbcp-ili9341) driver, clone the git repository and follow the instructions to build from source make sure to pass the flag `-DILI9488=ON` when compiling, as that is the driver that this project's screen uses. 
For keyboard controls I would use [retrogame](https://github.com/adafruit/Adafruit-Retrogame/tree/master), follow their instructions for install and then you should be able to use the `retrogame.cfg` from this repository.
Note this software has not been tested yet with this project.

| Item                  | Qty. | Price(USD) | Link                                                                                                                     |
|-----------------------|------|------------|--------------------------------------------------------------------------------------------------------------------------|
| ER-TFTM035-6          | 1    | 13.43      | https://www.buydisplay.com/lcd-3-5-inch-320x480-tft-display-module-optl-touch-screen-w-breakout-board                    |
| PowerBoost 1000       | 1    | 19.95      | https://www.adafruit.com/product/2465                                                                                    |
| USB-C Breakout        | 1    | 2.95       | https://www.adafruit.com/product/4090                                                                                    |
| TS04-66-55-BK-100-SMT | 15   | 0.143      | https://www.mouser.com/ProductDetail/Same-Sky/TS04-66-55-BK-100-SMT?qs=A6eO%252BMLsxmSPFjiYrrF3HQ%3D%3D                  |
| LTL-307E              | 1    | 0.14       | https://www.mouser.com/ProductDetail/LITEON/LTL-307E?qs=LJdOdOP975wJHAxE1%2Fv4ZA%3D%3D                                   |
| CFM14JT100R           | 1    | 0.10       | https://www.mouser.com/ProductDetail/SEI-Stackpole/CFM14JT100R?qs=sGAEpiMZZMtlubZbdhIBIA%252B43obPAL0tpqzY%252BkHSDUg%3D |
| EG1206                | 1    | 0.74       | https://www.mouser.com/ProductDetail/E-Switch/EG1206?qs=HKd%2Fp3M7KlUkIGmXpAWCMA%3D%3D                                   |
| 2500mAh battery       | 1    | 14.95      | https://www.adafruit.com/product/328                                                                                     |
| Raspberry Pi Zero 2 W | 1    | 19.05      | https://www.adafruit.com/product/5291                                                                                    |
