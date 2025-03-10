---
title: '1.1 ATK-DL2K0300B开发板底板资源'
sidebar_position: 1
---

# 1.1 ATK-DL2K0300B开发板底板资源

&emsp;&emsp;该开发板采用底板和核心板相结合的设计，采用邮票孔的形式进行连接。核心板占用空间小，具有出色的稳定性。开发板由12V/1A电源适配器进行供电。在现实接口方面，开发板具有RGB屏幕接口，板载两个千兆网口、板载WIFI&BT接口、一路485和一路CAN FD接口等，非常适合在工业场景中使用。

&emsp;&emsp;ATK-DL2K0300B开发板的底板资源图，如图所示：

<center>
![](./img/1.1.1.png)<br />
图 1.1.1 ATK-DL2K0300B开发板底板资料图
</center>

&emsp;&emsp;从上图可以看出，ATK-DL2K0300B开发板底板资源十分丰富，扩充了丰富的接口和功能模块。开发板的外形尺寸为 180mm*100mm 大小，板子的设计充分考虑了人性化设计，便于开发使用。

&emsp;&emsp;下面详细介绍ATK-DL2K0300B 开发板底板的各部分硬件资源，便于用户详细了解底板硬件资料情况，按顺时针顺序依次介绍：

&emsp;&emsp;**1、DC12V电源输入**<br />
&emsp;&emsp;开发板1 个外部电源输入口（DC_IN），采用标准的直流电源插座。开发板板载了 DC-DC 芯片，用于给开发板提供高效、稳定的 3.3V 电源。由于采用了 DC-DC 芯片，所以开发板的供电范围十分宽，大家可以很方便地找到合适的电源（只要输出范围在 DC 6~16V 的基本都可以）来给开发板供电。

&emsp;&emsp;**2、电源开关**<br />
&emsp;&emsp;开发板板载 1 个电源开关（S1）。该开关用于控制整个开发板的供电。这是一个两段式拨动开关，拨到左边打开开发板电源，整个板子开始供电，电源指示灯(PWR)点亮。拨到右边关闭开发板电源，整个开发板都将断电，电源指示灯（PWR）会随之熄灭。

&emsp;&emsp;**3、ATK-CL2K0300B核心板**<br />
&emsp;&emsp;这是开发板底板上面的核心板，外形尺寸为42.00mm*37.00mm大小，并采用板对板接口，共 160PIN。板载1GB DDR4内存、8GB EMMC存储器，采用8层板沉金设计，单独底层、电源层。

&emsp;&emsp;**4、引出电源3.3V/5V/GND**<br />
&emsp;&emsp;开发板板载1组5V电源输出排针(2×3P)和1组3.3V电源输出排针(2×3P)，这两组排针用于给外部提供电源，方便调试。

&emsp;&emsp;**5、RTC纽扣电池座**<br />
&emsp;&emsp;开发板板载 1 个 RTC 纽扣电池座，用于给 RTC 实时时钟芯片供电，可在开发板断电后能够维持 RTC 时钟芯片计时。

&emsp;&emsp;**6、复位按键**<br />
&emsp;&emsp;开发板板载1个复位按键(KEY1)，用于复位核心板。

&emsp;&emsp;**7、用户按键**<br />
&emsp;&emsp;开发板板载1个输入按键(KEY2)，用户可以用作普通按键输入使用。

&emsp;&emsp;**8、底板LED**<br />
&emsp;&emsp;开发板板载1个蓝色电源指示灯，当开发板3.3V供电正常时此灯就会常亮。如果此灯不亮的话就说明开发板供电有问题(排除 LED 灯本身损坏的情况)。

&emsp;&emsp;**9、用户LED**<br />
&emsp;&emsp;开发板板载1个红色状态指示灯和1个黄色状态指示灯，用户可以作为普通LED输出使用。

&emsp;&emsp;**10、可调电位器**<br />
&emsp;&emsp;开发板板载 1 个阻值 10K 的可调电位器，连接到了 2K0300 的 CPU_ADC_IN1引脚上，可以用来测试 ADC 电压采集。

&emsp;&emsp;**11、用户扩展IO**<br />
&emsp;&emsp;开发板IO引出端口JP7，采用2×7P排针组，总共引出14个IO口。

&emsp;&emsp;**12、TF卡槽**<br />
&emsp;&emsp;开发板板载 1 个标准 TF 卡接口（TF_CARD），采用小型的 TF 卡接口，SDIO 方式驱动。有了这个 TF 卡接口，就可以满足大容量数据存储需求。

&emsp;&emsp;**13、SIM卡槽**<br />
&emsp;&emsp;开发板板载 1 个 Nano SIM 卡接口，如果需要使用 4G/5G 模块进行无线数据传输，就需要在此接口插入 Nano SIM 卡。

&emsp;&emsp;**14、烧录接口**<br />
&emsp;&emsp;SPI烧录接口，把U-Boot的镜像烧录到ATK-CL2K0300B核心板上的SPI FLASH存储芯片上。

&emsp;&emsp;**15、录音咪头**<br />
&emsp;&emsp;开发板板载 1 个驻极体麦克风，即录音输入口（MIC），可以用来实现录音功能。

&emsp;&emsp;**16、耳机接口**<br />
&emsp;&emsp;开发板板载 1 个耳机接口。该接口可以插 3 段式 3.5mm 的耳机，支持录音与放音。放音时，支持耳机热插拔；录音时，支持耳机录音和板载麦克风 MIC两种方式进行录音。

&emsp;&emsp;**17、外接喇叭接口**<br />
&emsp;&emsp;开发板板载 2 路扬声器外接接口，其中一路扬声器接口 SPKR 已在开发板接入一个小扬声器，方便用户进行音频播放测试。

&emsp;&emsp;**18、4G通讯模块插座**<br />
&emsp;&emsp;开发板板载 1 个 Mini PCIE 座，本质上走的是 USB 协议，连接到 USB1 的 HUB 芯片上。此接口可以连接 4G 或 5G 模组，比如高新兴物联 ME3630 4G 模组、移远 EC20 4G 模组、广和通 5G RedCap FG132 模组。

&emsp;&emsp;**19、RGB屏幕接口**<br />
&emsp;&emsp;开发板板载一个RGB输出接口，0.5mm 40P 的 FPC 座，可适配正点原子店铺RGB 7寸1024×600电容屏。

&emsp;&emsp;**20、调试串口(Type-c)**<br />
&emsp;&emsp;开发板板载 1 路 USB_TTL 调试串口，为 USB Type-C 接口，用于 USB 连接 CH340C 芯片，从而实现 USB 转串口功能，作为系统调试串口。

&emsp;&emsp;**21、WIFI/BT模组**<br />
&emsp;&emsp;这是开发板上的 WIFI 天线接口，开发板板载的一个 WIFI 模组(WIFI&蓝牙一体模组)，为USB 接口，连接到了 2K0300的 USB1接口上。模组为 RTL8733，这个模组 WIFI 和蓝牙天线分开的。

&emsp;&emsp;**22、USB OTG接口(Type-c)**<br />
&emsp;&emsp;开发板板载 1 路 USB OTG 接口，为 USB2.0 Type-C 接口。此接口连接处理器2K0300的USB0总线，用于实现 OTG 功能。

&emsp;&emsp;**23、蓝牙和WIFI天线接口**<br />
&emsp;&emsp;开发板板载 1 个 WIFI 和1个蓝牙天线接口。

&emsp;&emsp;**24、USB 2.0 HOST×2**<br />
&emsp;&emsp;开发板通过USB HUB芯片将2K0300的USB1扩展为4路USB HOST，其中1路用于连接4G/5G模块，1路用于WIFI/BT模组，另外2路作为USB HOST，用户可以通过这2路USB HOST接口连接USB鼠标、USB键盘、U盘等设备。

&emsp;&emsp;**25、RS-485**<br />
&emsp;&emsp;这是开发板板载的 RS485 总线接口（RS485），通过 2 个端口和外部 485 设备连接。这里提醒大家，RS485 通信的时候，必须 A 接 A，B 接 B。否则可能通信不正常。在使用的时候需要将 JP5 的跳线帽U1_TX接485_R，U1_RX接485_T(RS485与RS232只能二选一)。

&emsp;&emsp;**26、CAN FD**<br />
&emsp;&emsp;这是开发板板载的 CAN 总线接口（CAN FD），通过 2 个端口和外部 CAN 总线连接，即 CANH和 CANL。这里提醒大家：CAN 通信的时候，必须 CANH 接 CANH，CANL 接 CANL，否则可能通信不正常！客户在设计底板CAN FD电路时可找技术支持进行沟通。

&emsp;&emsp;**27、RS-232(母)**<br />
&emsp;&emsp;这是开发板板载的一个 RS232 接口（COM1），通过一个标准的 DB9 母头和外部的串口连接。通过这个接口，我们可以连接带有串口的电脑或者其他设备，实现串口通信。在使用的时候需要将 JP5 的跳线帽U1_TX接232_R，U1_RX接232_T(RS485与RS232只能二选一)。

&emsp;&emsp;**28、千兆网口×2**<br />
&emsp;&emsp;这是开发板板载的2个 1000M 以太网接口，可以进行 10/100/1000M 网络通信。2K0300内部含有2个10/100/1000M以太网MAC外设，通过外接1000M网络PHY芯片，可以实现1000M有线网络。
















