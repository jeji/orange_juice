# 版本信息 Release Note
2022/1/30: v0.6 Bate release version, passed function and 2 hours stable test.

# 开始之前 Before You Start 
- 我并不是专业的电子工程师，设计本项目只是为了好玩和方便DIY Voron 3D打印机
- 你将自行承担由此带来的所有风险
- 社区有诸多反馈香橙派zero的CPU温度过高，所以在使用中请加强散热
- 本项目为基于GPL3.0的开源项目，欢迎魔改。如果你有更好的改进也请务必与我分享 
- **(!) 请特别注意文章中加粗和带"(!)"部分的内容**

- I'm not prefesstional electronic engineer, I designed this for fun and convenience while DIY my Voron printer
- You will take it as your own risk for any potential damages
- Overheat issue is being reported for OrangePi Zero H2+ CPU, hence a proper cooling fan even with cooling fin is strongly recommended
- This project is based GPL3.0 license, you are free to modify it to yourown version. Please do share the joy with me if you did that
- **(!) Please pay attention for the bold and with "(!)" content**

# 代号：橙汁 BoardName：Orange Juice

![](images/orange_juice_board_front_v0.6.png)  

![](images/orange_juice_board_back_v0.6.png)  \

受全球芯片短缺情况影响，树莓派价格涨到了离谱的位置。
所以香橙派zero成了一个很好的替代品。120元左右的512MB版本可以满足做为klipper宿主的所有需求，甚至有点性能过剩。\

klipper有诸多独特的功能需要使用到gpio针脚，每次都用排母端子去连接非常的不方便。在使用扩展板后不仅方便了许多，且可以得到额外的功能：
- 一个专为[ADXL345](https://www.adafruit.com/product/1231) 设计的接口将香橙派SPI1总线引出
- 一个专为[Adafruit MAX31865 board](https://www.adafruit.com/product/3328) 及其克隆版本设计的接口，作为软SPI使用了4个gpio接口
- 两个从香橙派引出的USB2.0 TypeA接口
- 一个UART接口
- 三组gpio控制的PWM输出接口，插座输出电压与输入电压相同
- 两组恒定5v输出接口
- 一个香橙派专用散热3010风扇安装位
- 自带降压电路，将9~28V输入电压降压为5V供香橙派使用
- 扩展板大小及安装孔位与树莓派B系列保持一样
- DCIN供电接口防反设计，防止输入电源正负极反接

Due to current chipset shortage sitatuion, raspberry pi price increase to an unreasonable level. 
Hence OrangePi Zero become a good alternative. A 25 dollars 512MB ram version meets all the requirments I need as a klipper host for my Voron V0.1, and actually even little bit over kill. \

Klipper has some advance features which need connect to gpio pins, it's not that convenience to use a pin header to connect gpio pin every time. Instead of that, with this board, it provides easier connection and more useful features:
- A dedicate [ADXL345](https://www.adafruit.com/product/1231) port is extended from OrangePi zero SPI1 bus
- A dedicate MAX31865 port connect to 4 gpio pins as a SW SPI connection, for [Adafruit MAX31865 board](https://www.adafruit.com/product/3328) or its clone
- Two USB2.0 Type A ports are extended from orange pi function pin
- A UART port for UART communication with printer MCU board
- Three klipper controllable pwm output ports, voltage depends on input DC voltage
- Two channel persistent 5v output
- A build in 3010 chip cooling fan position
- A build in step-down buck converter to convert DC 9~24v input to DC 5v to supply pi and 5v output socket
- Raspberry Pi B Serials board size and mount hole position compatible 
- DC In reverse protetion circuit design

![](images/top.png)  

![](images/back.png)  

![](images/front.png)  

![](images/bottom.png)  

# 如何使用 How to use
## 硬件 Hardware
To be updated
## 软件 Software
To be updated

# 采购单 BOM
To be updated

