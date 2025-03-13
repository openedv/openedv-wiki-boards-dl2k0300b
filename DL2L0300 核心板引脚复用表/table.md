---
title: '核心板复用表'
sidebar_position: 1
---

## A座

<div class="table1-0300">



| 核心板A座 | 底板J1座 | GPIO名称 | 主功能复用   | 第一复用     | 第二复用   | 电源域 | buildroot出厂固件默认配置 | LS2K0300开发板默认功能 |
| --------- | -------- | -------- | ------------ | ------------ | ---------- | ------ | ------------------------- | ---------------------- |
| 80        | 80       |          |              |              |            | --     | --                        | GND                    |
| 79        | 79       | GPIO4    | lcd_dat_b[0] |              | lioa[0]    | 3.3V   | 主功能复用                | CPU_LCD_DATA0          |
| 78        | 78       | GPIO5    | lcd_dat_b[1] |              | lioa[1]    | 3.3V   | 主功能复用                | CPU_LCD_DATA1          |
| 77        | 77       | GPIO6    | lcd_dat_b[2] |              | lioa[2]    | 3.3V   | 主功能复用                | CPU_LCD_DATA2          |
| 76        | 76       | GPIO7    | lcd_dat_b[3] |              | lioa[3]    | 3.3V   | 主功能复用                | CPU_LCD_DATA3          |
| 75        | 75       | GPIO8    | lcd_dat_b[4] |              | lioa[4]    | 3.3V   | 主功能复用                | CPU_LCD_DATA4          |
| 74        | 74       | GPIO9    | lcd_dat_b[5] |              | lioa[5]    | 3.3V   | 主功能复用                | CPU_LCD_DATA5          |
| 73        | 73       | GPIO10   | lcd_dat_b[6] |              | lioa[6]    | 3.3V   | 主功能复用                | CPU_LCD_DATA6          |
| 72        | 72       | GPIO11   | lcd_dat_b[7] |              | lioa[7]    | 3.3V   | 主功能复用                | CPU_LCD_DATA7          |
| 71        | 71       |          |              |              |            | --     | --                        | GND                    |
| 70        | 70       | GPIO12   | lcd_dat_g[0] |              | lioa[8]    | 3.3V   | 主功能复用                | CPU_LCD_DATA8          |
| 69        | 69       | GPIO13   | lcd_dat_g[1] |              | lioa[9]    | 3.3V   | 主功能复用                | CPU_LCD_DATA9          |
| 68        | 68       | GPIO14   | lcd_dat_g[2] |              | lioa[10]   | 3.3V   | 主功能复用                | CPU_LCD_DATA10         |
| 67        | 67       | GPIO15   | lcd_dat_g[3] |              | lioa[11]   | 3.3V   | 主功能复用                | CPU_LCD_DATA11         |
| 66        | 66       | GPIO16   | lcd_dat_g[4] |              | lioa[12]   | 3.3V   | 主功能复用                | CPU_LCD_DATA12         |
| 65        | 65       | GPIO17   | lcd_dat_g[5] |              | lioa[13]   | 3.3V   | 主功能复用                | CPU_LCD_DATA13         |
| 64        | 64       | GPIO18   | lcd_dat_g[6] |              | lioa[14]   | 3.3V   | 主功能复用                | CPU_LCD_DATA14         |
| 63        | 63       | GPIO19   | lcd_dat_g[7] |              | lioa[15]   | 3.3V   | 主功能复用                | CPU_LCD_DATA15         |
| 62        | 62       |          |              |              |            | --     | --                        | GND                    |
| 61        | 61       | GPIO20   | lcd_dat_r[0] |              | lioa[16]   | 3.3V   | 主功能复用                | CPU_LCD_DATA16         |
| 60        | 60       | GPIO21   | lcd_dat_r[1] |              | lioa[17]   | 3.3V   | 主功能复用                | CPU_LCD_DATA17         |
| 59        | 59       | GPIO22   | lcd_dat_r[2] |              | lioa[18]   | 3.3V   | 主功能复用                | CPU_LCD_DATA18         |
| 58        | 58       | GPIO23   | lcd_dat_r[3] |              | lioa[19]   | 3.3V   | 主功能复用                | CPU_LCD_DATA19         |
| 57        | 57       | GPIO24   | lcd_dat_r[4] |              | liocsn[0]  | 3.3V   | 主功能复用                | CPU_LCD_DATA20         |
| 56        | 56       | GPIO25   | lcd_dat_r[5] |              | liocsn[1]  | 3.3V   | 主功能复用                | CPU_LCD_DATA21         |
| 55        | 55       | GPIO26   | lcd_dat_r[6] |              | liowrn     | 3.3V   | 主功能复用                | CPU_LCD_DATA22         |
| 54        | 54       | GPIO27   | lcd_dat_r[7] |              | liordn     | 3.3V   | 主功能复用                | CPU_LCD_DATA23         |
| 53        | 53       |          |              |              |            | --     | --                        | GND                    |
| 52        | 52       | GPIO60   | spi1_clk     | i2c_scl[0]   | uart0_rts  | 3.3V   | GPIO                      | GPIO                   |
| 51        | 51       | GPIO63   | spi1_cs      | i2c_sda[1]   | uart0_dtr  | 3.3V   | GPIO                      | GPIO                   |
| 50        | 50       | GPIO61   | spi1_miso    | i2c_sda[0]   | uart0_cts  | 3.3V   | GPIO                      | GPIO                   |
| 49        | 49       | GPIO62   | spi1_mosi    | i2c_scl[1]   | uart0_dsr  | 3.3V   | GPIO                      | GPIO                   |
| 48        | 48       | GPIO64   | spi2_clk     | pwm[0]       | uart0_dcd  | 3.3V   | GPIO                      | GPIO                   |
| 47        | 47       | GPIO67   | spi2_cs      | pwm[3]       | uart1_cts  | 3.3V   | GPIO                      | GPIO                   |
| 46        | 46       | GPIO65   | spi2_miso    | pwm[1]       | uart0_ri   | 3.3V   | GPIO                      | GPIO                   |
| 45        | 45       | GPIO66   | spi2_mosi    | pwm[2]       | uart1_rts  | 3.3V   | GPIO                      | GPIO                   |
| 44        | 44       |          |              |              |            | --     | --                        | GND                    |
| 43        | 43       | GPIO57   | spi0_miso    |              | can_tx[2]  | 3.3V   | 主功能复用                | CPU_SPI0_MOSI          |
| 42        | 42       | GPIO58   | spi0_mosi    |              | can_rx[3]  | 3.3V   | 主功能复用                | CPU_SPI0_MISO          |
| 41        | 41       |          |              |              |            | --     | --                        | GND                    |
| 40        | 40       |          |              |              |            | --     | --                        | GND                    |
| 39        | 39       | GPIO56   | spi0_clk     |              | can_rx[2]  | 3.3V   | 主功能复用                | CPU_SPI0_CLK           |
| 38        | 38       | GPIO59   | spi0_cs[0]   |              | can_tx[3]  | 3.3V   | 主功能复用                | CPU_SPI0_CSN           |
| 37        | 37       |          |              |              |            | --     | --                        | GND                    |
| 36        | 36       |          |              |              |            | --     | --                        | GND                    |
| 35        | 35       |          |              |              |            | --     | --                        | CPU_JTAG_TMS           |
| 34        | 34       |          |              |              |            | --     | --                        | CPU_JTAG_TCK           |
| 33        | 33       |          |              |              |            | --     | --                        | CPU_JTAG_TRST          |
| 32        | 32       |          |              |              |            | --     | --                        | CPU_JTAG_TDI           |
| 31        | 31       |          |              |              |            | --     | --                        | CPU_JTAG_TDO           |
| 30        | 30       |          |              |              |            | --     | --                        | CPU_JTAG_SEL           |
| 29        | 29       |          |              |              |            | --     | --                        | GND                    |
| 28        | 28       | GPIO80   | i2s_datao    | tim1_breakin | spi1_cs[3] | 3.3V   | 主功能复用                | CPU_I2S_DO             |
| 27        | 27       | GPIO79   | i2s_datai    | gtim_etr     | spi1_cs[2] | 3.3V   | 主功能复用                | CPU_I2S_DI             |
| 26        | 26       | GPIO78   | i2s_lr       | atim_etr     | spi1_cs[1] | 3.3V   | 主功能复用                | CPU_I2S_LR             |
| 25        | 25       | GPIO77   | i2s_bclk     | tim2_ch4     |            | 3.3V   | 主功能复用                | CPU_I2S_BCLK           |
| 24        | 24       | GPIO76   | i2s_mclk     | tim1_ch4     |            | 3.3V   | 主功能复用                | CPU_I2S_MCLK           |
| 23        | 23       |          |              |              |            | --     | --                        | GND                    |
| 22        | 22       | GPIO84   | tim1_ch1n    | spi3_mosi    | i2c_scl[3] | 3.3V   | 第二复用                  | I2C3_SCL               |
| 21        | 21       | GPIO81   | tim1_ch1     |              |            | 3.3V   | GPIO                      | HP_DET_L               |
| 20        | 20       | GPIO86   | tim1_ch3n    | sdio1_d[4]   | pwm[0]     | 3.3V   | GPIO                      | SPK_CTL_H              |
| 19        | 19       | GPIO83   | tim1_ch3     | spi3_miso    | i2c_sda[2] | 3.3V   | 第二复用                  | I2C2_SDA               |
| 18        | 18       | GPIO85   | tim1_ch2n    | spi3_cs      | i2c_sda[3] | 3.3V   | 第二复用                  | I2C3_SDA               |
| 17        | 17       | GPIO82   | tim1_ch2     | spi3_clk     | i2c_scl[2] | 3.3V   | 第二复用                  | I2C2_SCL               |
| 16        | 16       | GPIO87   | tim2_ch1     | sdio1_d[5]   | pwm[1]     | 3.3V   | GPIO                      | PHONE_CTL              |
| 15        | 15       | GPIO88   | tim2_ch2     | sdio1_d[6]   | pwm[2]     | 3.3V   | 第二复用                  | LCD_PWM2               |
| 14        | 14       | GPIO89   | tim2_ch3     | sdio1_d[7]   | pwm[3]     | 3.3V   | GPIO                      | LED0                   |
| 13        | 13       |          |              |              |            | --     | --                        |                        |
| 12        | 12       | GPIO103  | sdio1_d[1]   | atim_etr     | pwm[1]     | 3.3V   | 主功能复用                | CPU_SDIO1_DATA1        |
| 11        | 11       | GPIO102  | sdio1_d[0]   | tim2_ch4     | pwm[0]     | --     | 主功能复用                | CPU_SDIO1_DATA0        |
| 10        | 10       | GPIO100  | sdio1_clk    |              |            | --     | 主功能复用                | CPU_SDIO1_CLK          |
| 9         | 9        | GPIO101  | sdio1_cmd    | tim1_ch4     |            | 3.3V   | 主功能复用                | CPU_SDIO1_CMD          |
| 8         | 8        | GPIO105  | sdio1_d[3]   | tim1_breakin | pwm[3]     | 3.3V   | 主功能复用                | CPU_SDIO1_DATA3        |
| 7         | 7        | GPIO104  | sdio1_d[2]   | gtim_etr     | pwm[2]     | 3.3V   | 主功能复用                | CPU_SDIO1_DATA2        |
| 6         | 6        |          |              |              |            | 3.3V   | --                        | GND                    |
| 5         | 5        | GPIO00   | lcd_clk      |              |            | 3.3V   | 主功能复用                | CPU_LCD_CLK            |
| 4         | 4        | GPIO01   | lcd_vsync    |              | lioa[0]    | 3.3V   | 主功能复用                | CPU_LCD_VSYNC          |
| 3         | 3        | GPIO02   | lcd_hsync    |              | lioa[1]    | 3.3V   | 主功能复用                | CPU_LCD_HSYNC          |
| 2         | 2        | GPIO03   | lcd_en       |              | lioa[2]    | 3.3V   | 主功能复用                | CPU_LCD_EN             |
| 1         | 1        |          |              |              |            | 3.3V   | --                        | GND                    |

</div>

## B座



<div class="table2-0300">

| 核心板B座 | 底板J2座 | GPIO名称 | 主功能复用   | 第一复用       | 第二复用     | 电源域 | buildroot出厂固件默认配置 | LS2K0300开发板默认功能 |
| --------- | -------- | -------- | ------------ | -------------- | ------------ | ------ | ------------------------- | ---------------------- |
| 80        | 80       |          |              |                |              | --     | --                        |                        |
| 79        | 79       |          |              |                |              | --     | --                        |                        |
| 78        | 78       |          |              |                |              | --     | --                        |                        |
| 77        | 77       |          |              |                |              | --     | --                        |                        |
| 76        | 76       |          |              |                |              | --     | --                        |                        |
| 75        | 75       |          |              |                |              | --     | --                        |                        |
| 74        | 74       |          |              |                |              | --     | --                        |                        |
| 73        | 73       | GPIO40   | uart0_rx     | gmac0_ptp_trig | lio_data[0]  | 3.3V   | 主功能复用                | CPU_UART0_RXD          |
| 72        | 72       | GPIO41   | uart0_tx     | gmac0_ptp_pps  | lio_data[1]  | 3.3V   | 主功能复用                | CPU_UART0_TXD          |
| 71        | 71       | GPIO42   | uart1_rx     | gmac1_ptp_trig | lio_data[2]  | 3.3V   | 主功能复用                | CPU_UART1_RXD          |
| 70        | 70       | GPIO43   | uart1_tx     | gmac1_ptp_pps  | lio_data[3]  | 3.3V   | 主功能复用                | CPU_UART1_TXD          |
| 69        | 69       |          |              |                |              | --     | --                        | GND                    |
| 68        | 68       | GPIO45   | uart2_rx     | gmac1_rx[0]    | lio_data[5]  | 3.3V   | 第一复用                  | CPU_GMAC1_RXD0         |
| 67        | 67       | GPIO44   | uart2_tx     | gmac1_rx_ctl   | lio_data[4]  | 3.3V   | 第一复用                  | CPU_GMAC1_RCTL         |
| 66        | 66       | GPIO47   | uart3_rx     | gmac1_rx[2]    | lio_data[7]  | 3.3V   | 第一复用                  | CPU_GMAC1_RXD2         |
| 65        | 65       | GPIO46   | uart3_tx     | gmac1_rx[1]    | lio_data[6]  | 3.3V   | 第一复用                  | CPU_GMAC1_RXD1         |
| 64        | 64       |          |              |                |              | --     | --                        | CPU_GMAC1_RXCLK        |
| 63        | 63       | GPIO48   | i2c_scl[0]   | gmac1_rx[3]    | lio_data[8]  | 3.3V   | 第一复用                  | CPU_GMAC1_RXD3         |
| 62        | 62       |          |              |                |              | --     | --                        | GND                    |
| 61        | 61       | GPIO49   | i2c_sda[0]   | gmac1_tx_ctl   | lio_data[9]  | 3.3V   | 第一复用                  | CPU_GMAC1_TCTL         |
| 60        | 60       | GPIO50   | i2c_scl[1]   | gmac1_tx[0]    | lio_data[10] | 3.3V   | 第一复用                  | CPU_GMAC1_TXD0         |
| 59        | 59       | GPIO51   | i2c_sda[1]   | gmac1_tx[1]    | lio_data[11] | 3.3V   | 第一复用                  | CPU_GMAC1_TXD1         |
| 58        | 58       | GPIO53   | i2c_sda[2]   | gmac1_tx[3]    | lio_data[13] | 3.3V   | 第一复用                  | CPU_GMAC1_TXD3         |
| 57        | 57       | GPIO52   | i2c_scl[2]   | gmac1_tx[2]    | lio_data[12] | 3.3V   | 第一复用                  | CPU_GMAC1_TXD2         |
| 56        | 56       |          |              |                |              | --     | --                        | CPU_GMAC1_TXCLK_O      |
| 55        | 55       |          |              |                |              | --     | --                        | CPU_GMAC1_TXCLK_I      |
| 54        | 54       |          |              |                |              | --     | --                        | GND                    |
| 53        | 53       |          |              |                |              | --     | --                        | CPU_GMAC1_MDCK         |
| 52        | 52       |          |              |                |              | --     | --                        | CPU_GMAC1_MDIO         |
| 51        | 51       |          |              |                |              | --     | --                        | GND                    |
| 50        | 50       |          |              |                |              | --     | --                        | CPU_USB0_DRVBUS        |
| 49        | 49       |          |              |                |              | --     | --                        | CPU_USB0_ID            |
| 48        | 48       |          |              |                |              | --     | --                        | CPU_USB0_DP            |
| 47        | 47       |          |              |                |              | --     | --                        | CPU_USB0_DM            |
| 46        | 46       |          |              |                |              | --     | --                        | GND                    |
| 45        | 45       |          |              |                |              | --     | --                        | CPU_USB1_OC            |
| 44        | 44       |          |              |                |              | --     | --                        | CPU_USB1_DP            |
| 43        | 43       |          |              |                |              | --     | --                        | CPU_USB1_DM            |
| 42        | 42       |          |              |                |              | --     | --                        | PLTRESETN              |
| 41        | 41       |          |              |                |              | --     | --                        |                        |
| 40        | 40       |          |              |                |              | --     | --                        | CPU_ADC_IN7            |
| 39        | 39       |          |              |                |              | --     | --                        | CPU_ADC_IN6            |
| 38        | 38       |          |              |                |              | --     | --                        | CPU_ADC_IN5            |
| 37        | 37       |          |              |                |              | --     | --                        | CPU_ADC_IN4            |
| 36        | 36       |          |              |                |              | --     | --                        | CPU_ADC_IN3            |
| 35        | 35       |          |              |                |              | --     | --                        | CPU_ADC_IN2            |
| 34        | 34       |          |              |                |              | --     | --                        | CPU_ADC_IN1            |
| 33        | 33       |          |              |                |              | --     | --                        | ADC_IN0_HP_HOOK        |
| 32        | 32       |          |              |                |              | --     | --                        | GND                    |
| 31        | 31       |          |              |                |              | --     | --                        | CPU_GMAC0_RXCLK        |
| 30        | 30       | GPIO28   | gmac0_rx_ctl |                | tim1_ch1     | 3.3V   | 主功能复用                | CPU_GMAC0_RCTL         |
| 29        | 29       | GPIO29   | gmac0_rx[0]  |                | tim1_ch2     | 3.3V   | 主功能复用                | CPU_GMAC0_RXD0         |
| 28        | 28       | GPIO30   | gmac0_rx[1]  |                | tim1_ch3     | 3.3V   | 主功能复用                | CPU_GMAC0_RXD1         |
| 27        | 27       | GPIO31   | gmac0_rx[2]  |                | tim1_ch1n    | 3.3V   | 主功能复用                | CPU_GMAC0_RXD2         |
| 26        | 26       | GPIO32   | gmac0_rx[3]  |                | tim1_ch2n    | 3.3V   | 主功能复用                | CPU_GMAC0_RXD3         |
| 25        | 25       |          |              |                |              | --     | --                        | GND                    |
| 24        | 24       | GPIO33   | gmac0_tx_ctl |                | tim1_ch3n    | 3.3V   | 主功能复用                | CPU_GMAC0_TCTL         |
| 23        | 23       |          |              |                |              | --     | --                        | CPU_GMAC0_TXCLK_I      |
| 22        | 22       |          |              |                |              | --     | --                        | CPU_GMAC0_TXCLK_O      |
| 21        | 21       | GPIO34   | gmac0_tx[0]  |                | tim2_ch1     | 3.3V   | 主功能复用                | CPU_GMAC0_TXD0         |
| 20        | 20       | GPIO35   | gmac0_tx[1]  |                | tim2_ch2     | 3.3V   | 主功能复用                | CPU_GMAC0_TXD1         |
| 19        | 19       | GPIO36   | gmac0_tx[2]  | can_rx[0]      | tim2_ch3     | 3.3V   | 主功能复用                | CPU_GMAC0_TXD2         |
| 18        | 18       | GPIO37   | gmac0_tx[3]  | can_tx[0]      |              | 3.3V   | 主功能复用                | CPU_GMAC0_TXD3         |
| 17        | 17       |          |              |                |              | 3.3V   | --                        | GND                    |
| 16        | 16       | GPIO38   | gmac0_mdck   | can_rx[1]      |              | 3.3V   | 主功能复用                | CPU_GMAC0_MDCK         |
| 15        | 15       | GPIO39   | gmac0_mdio   | can_tx[1]      |              | 3.3V   | 主功能复用                | CPU_GMAC0_MDIO         |
| 14        | 14       |          |              |                |              | --     | --                        | CPU_DOTESTN            |
| 13        | 13       | GPIO68   | can_rx[0]    | spi0_cs[1]     | uart1_dsr    | 3.3V   | 主功能复用                | CPU_CAN0_RX            |
| 12        | 12       | GPIO69   | can_tx[0]    | spi0_cs[2]     | uart1_dtr    | 3.3V   | 主功能复用                | CPU_CAN0_TX            |
| 11        | 11       | GPIO70   | can_rx[1]    | spi0_cs[3]     | uart1_dcd    | --     | GPIO                      | LED1                   |
| 10        | 10       | GPIO71   | can_tx[1]    |                | uart1_ri     | --     | GPIO                      | KEY0                   |
| 9         | 9        | GPIO72   | can_rx[2]    | sdio1_d[4]     | gmac0_col    | 3.3V   | GPIO                      | PHY0_RESETn            |
| 8         | 8        | GPIO73   | can_tx[2]    | sdio1_d[5]     | gmac0_crs    | 3.3V   | GPIO                      | PHY1_RESETn            |
| 7         | 7        | GPIO74   | can_rx[3]    | sdio1_d[6]     | gmac1_col    | 3.3V   | GPIO                      | CT_INT                 |
| 6         | 6        | GPIO75   | can_tx[3]    | sdio1_d[7]     | gmac1_crs    | 3.3V   | GPIO                      | CT_RST                 |
| 5         | 5        |          |              |                |              | 3.3V   | 主功能复用                | MRESET#                |
| 4         | 4        |          |              |                |              | 3.3V   | 主功能复用                | MB_PWREN               |
| 3         | 3        |          |              |                |              | 3.3V   | 主功能复用                | GND                    |
| 2         | 2        |          |              |                |              | 3.3V   | 主功能复用                | GND                    |
| 1         | 1        |          |              |                |              | 3.3V   | --                        | GND                    |

</div>
