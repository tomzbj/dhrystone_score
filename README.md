# dhrystone_score

## Dhrystone score of some MCUs


    MCU                 Opt           Freq/MHz     Time/ms     DMIPS  DMIPS/MHz
    AMD R5-3600X        O3             4350        0.02   24322.73     5.59
    AMD R5-3600X        Os             4350        0.05   11383.04     2.62
    BCM2835(RPi Zero)   O3              800        0.33    1729.95     2.16
    BCM2835(RPi Zero)   Os              800        0.68     833.31     1.04
    GD32F450ZET6(oc)    O3              400        1.08     526.99     1.32
    GD32E503CET6(oc)    O3              272        1.40     406.54     1.49
    GD32VF103CBT6(oc)   O3              192        1.49     381.98     1.99
    GD32EPRTVDT6(oc)    O3              240        1.59     357.96     1.49
    GD32FFPRTGU6(oc)    O3              280        1.76     323.38     1.15
    GD32F350CBT6(oc)    O3              280        1.80     316.20     1.13
    GD32E503CET6        O3              176        2.15     264.72     1.50
    GD32F450ZET6        O3              200        2.16     263.50     1.32
    STM32F407VET6       O3              168        2.59     219.75     1.31
    GD32VF103CBT6       O3              108        2.66     213.97     1.98
    GD32F103RCT6(oc)    O3              192        2.82     201.83     1.05
    GD32FFPRTGU6        O3              168        2.93     194.25     1.16
    GD32E103CBT6        O3              120        3.77     150.97     1.26
    GD32E503CET6        Os              176        4.19     135.84     0.77
    GD32F103RCT6(oc)    Os              192        4.43     128.48     0.67
    GD32F350CBT6        O3              108        4.57     124.54     1.15
    STM32F407VET6       Os              168        4.84     117.59     0.70
    STM32F401RET6       O3               84        5.21     109.24     1.30
    GD32VF103CBT6       Os              108        6.00      94.86     0.88
    ESP8266             O3               80        6.38      89.21     1.12
    GD32F103RCT6        O3               72        7.54      75.48     1.05
    GD32E103CBT6        Os              120        8.11      70.18     0.58
    STM32F103VET6       O3               72        8.71      65.34     0.91
    STM32F401RET6       Os               84        9.19      61.93     0.74
    GD32E230C8T6        O3               72       10.44      54.52     0.76
    GD32F103RCT6        Os               72       11.83      48.11     0.67
    ESP8266             Os               80       12.20      46.65     0.58
    STM32F070CBT6       O3               48       14.90      38.20     0.80
    STM32F103VET6       Os               72       18.33      31.05     0.43
    GD32E230C8T6        Os               72       19.02      29.92     0.42
    STM32L051C8T6       O3               32       25.30      22.50     0.70
    STM32F407VET6       O3               16       27.00      21.08     1.32
    GD32F450ZET6        O3               16       27.21      20.92     1.31
    STM32F401RET6       O3               16       27.23      20.90     1.31
    STM32F070CBT6       Os               48       27.52      20.68     0.43
    STM32L051C8T6       O3               16       36.80      15.47     0.97
    STM32L051C8T6       Os               32       42.90      13.27     0.41
    GD32E103CBT6        O3                8       55.10      10.33     1.29
    STM32F103VET6       O3                8       59.00       9.65     1.21
    GD32FFPRTGU6        O3                8       61.50       9.25     1.16
    GD32F350CBT6        O3                8       61.55       9.25     1.16
    STM32L051C8T6       Os               16       62.10       9.17     0.57
    ATMEGA328P          O3               16       71.90       7.92     0.49
    ATMEGA328P          Os               16       74.00       7.69     0.48
    STM32F070CBT6       O3                8       80.00       7.11     0.89
    GD32E103CBT6        Os                8       96.00       5.93     0.74
    STM8L151G6U6        fast             16      107.10       5.31     0.33
    STM8S003F3U6        fast             16      107.20       5.31     0.33
    STM8S003F3U6        compact          16      108.10       5.27     0.33
    STM8L151G6U6        compact          16      121.00       4.70     0.29
    STC8A8K64S4A        opt-code-speed   24      254.00       2.24     0.09
    NRF24LE1            opt-code-size    16      883.00       0.64     0.04
    NRF24LE1            opt-code-speed   16      884.00       0.64     0.04

    GD32F303CCT6 = GD32FFPRTGU6  
    STM32F401CET6 = STM32F401RET6  
    STM32F103C8T6 = STM32F103VET6  
    GD32EPRTVDT6 ~= GD32E503CET6

| MCU Core | Compiler |
|---|---|
|Cortex M0/M3/M4|  arm-none-eabi-gcc 4.9.3  |
|Cortex M23/M33|   arm-none-eabi-gcc 10.2.1  |
|AVR| avr-gcc 7.3.0  |
|STM8| cosmic c 4.4.12  |
|8051| sdcc 3.8.0  |
|BCM2835| gcc 10.2.1  |
|RISCV| riscv-none-embed-gcc 7.2.0  |
|X86| gcc 5.1.0  |
|ESP8266| xtensa-lx106-elf-gcc 8.4.0  |
