# Before you start
- I'm not a prefesstional electronic engineer, I designed this for fun and convenience while diy Voron 3d printer
- You will take it as your own risk for any potential damages
- **(!) Please pay attention for the bold font and description with !"(!)"**

# Board Name: Orange Juice
Due to current chipset shortage sitatuion, raspberry pi price increase to an unreasonable level. 
Hence I'm using OrangePi Zero as a good alternative. A 20 dollar 512MB ram version meets all the requirments I need as a klipper host, and even little bit over kill.

Due to Klipper has some advance features which need connect to gpio, it's not that convenience to use a pin header and connect to gpio pin every time. Instead of that, with this board it provides easier connection and more useful features:

- A dedicate ADXL345 port from SPI1 
- A dedicate MAX31865 port from via SW SPI connection, compatible with adafruit MAX31865 design
- Two USB port from orange pi function pin
- A UART port for communicate with MCU board
- A step-down buck converter to convert DC 9~24v input to DC 5v to supply pi and 5v output socket
- Three gpio pin controlled channel pwm output, voltage depends on input DC voltage
- Two channel persistent 5v output
- A build in 3010 chip cooling fan position
- Raspberry Pi 3B/4B board size and mount hole position compatible 

- ![](images/top.png)  

- ![](images/front.png)  

- ![](images/bottom.png)  


