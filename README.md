# dhrystone_score

## Dhrystone score of some MCUs

    MCU                    Opt         Freq/MHz     Time/ms    DMIPS    DMIPS/MHz
    AMD R5-3600X           O3              4350       0.02    24323          5.59
    AMD R5-3600X           Os              4350       0.05    11383          2.62
    BCM2835(RPi Zero)      O3               800       0.33     1730          2.16
    BCM2835(RPi Zero)      Os               800       0.68      833          1.04
    GD32E503CET6(oc)       O3               272       1.40      407          1.49
    GD32VF103CBT6          O3               192       1.49      382          1.99
    GD32EPRTVDT6(oc)       O3               240       1.59      358          1.49
    GD32FFPRTGU6(oc)       O3               280       1.76      323          1.15
    GD32F350CBT6(oc)       O3               280       1.80      316          1.13
    GD32E503CET6           O3               176       2.15      265          1.50
    STM32F407VET6          O3               168       2.59      220          1.31
    GD32VF103CBT6          O3               108       2.66      214          1.98
    GD32FFPRTGU6           O3               168       2.93      194          1.16
    GD32E103CBT6           O3               120       3.77      151          1.26
    GD32E503CET6           Os               176       4.19      136          0.77
    GD32F350CBT6           O3               108       4.57      125          1.15
    STM32F407VET6          Os               168       4.84      118          0.70
    STM32F401RET6          O3                84       5.21      109          1.30
    GD32VF103CBT6          Os               108       6.00     94.9          0.88
    ESP8266                O3                80       6.38     89.2          1.12
    GD32E103CBT6           Os               120       8.11     70.2          0.58
    STM32F103VET6          O3                72       8.71     65.3          0.91
    STM32F401RET6          Os                84       9.19     61.9          0.74
    GD32E230C8T6           O3                72       10.4     54.5          0.76
    ESP8266                Os                80       12.2     46.7          0.58
    STM32F070CBT6          O3                48       14.9     38.2          0.80
    STM32F103VET6          Os                72       18.3     31.1          0.43
    GD32E230C8T6           Os                72       19.0     29.9          0.42
    STM32L051C8T6          O3                32       25.3     22.5          0.70
    STM32F407VET6          O3                16       27.0     21.1          1.32
    STM32F401RET6          O3                16       27.2     20.9          1.31
    STM32F070CBT6          Os                48       27.5     20.7          0.43
    STM32L051C8T6          O3                16       36.8     15.5          0.97
    STM32L051C8T6          Os                32       42.9     13.3          0.41
    GD32E103CBT6           O3                 8       55.1     10.3          1.29
    STM32F103VET6          O3                 8       59.0     9.65          1.21
    GD32FFPRTGU6           O3                 8       61.5     9.25          1.16
    GD32F350CBT6           O3                 8       61.6     9.25          1.16
    STM32L051C8T6          Os                16       62.1     9.17          0.57
    ATMEGA328P             O3                16       71.9     7.92          0.49
    ATMEGA328P             Os                16       74.0     7.69          0.48
    STM32F070CBT6          O3                 8       80.0     7.11          0.89
    GD32E103CBT6           Os                 8       96.0     5.93          0.74
    STM8L151G6U6           fast              16        107     5.31          0.33
    STM8S003F3U6           fast              16        107     5.31          0.33
    STM8S003F3U6           compact           16        108     5.27          0.33
    STM8L151G6U6           compact           16        121     4.70          0.29
    STC8A8K64S4A           opt-code-speed    24        254     2.24          0.09
    CH552E                 opt-code-speed    24        440     1.29          0.05
    NRF24LE1               opt-code-size     16        883     0.64          0.04
    NRF24LE1               opt-code-speed    16        884     0.64          0.04

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
