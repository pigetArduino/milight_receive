Receive milight codes using an Arduino
----------------------------------------
More information at http://github.com/pigetArduino/milightONOFF   

# Components
* 1 Arduino nano : 2.50€	   
* 1 nrf24l01+ (radio module) : 1€	   

# Wiring
**nrf modules use 3.3V not 5V**

![nrf_pinout](https://github.com/pigetArduino/milightONOFF/raw/master/doc/nrf_pinout.png)

![touchsensor](https://github.com/pigetArduino/milightONOFF/raw/master/doc/touchsensor.png)

```
NRF
D9	: orange
D10	: yellow
D11	: blue
D12	: purple
D13	: green
3.3V: red

SWITCHS
D4	OFF SIG
D5	ON SIG
5V: VCC
```

# Get the radio codes (milight_receive.ino)
* Download http://milightreceive.madnerd.org
* Open **milight_receive/milight_receive.ino** sketches and upload it.
* Open the **serial monitor**
* **Turn on** your lamp
* **Turn off** your lamp 
* Copy the received code.
```
Press a button on your smartphone to receive radiocodes

0xD8 0x34 0x4A 0x00 0x01 0x04 0x2C .......
0xD8 0x34 0x4A 0x00 0x01 0x03 0x2D .......
```
