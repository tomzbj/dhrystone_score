# dhrystone_score

## Dhrystone score of some MCUs

    MCU                        Opt      Arch          Freq/MHz    Time/ms    DMIPS   DMIPS/MHz
    AMD R5-3600X               O3       X86-64            4350       0.02  24323          5.59
    AMD R5-3600X               Os       X86-64            4350       0.05  11383          2.62
    BCM2835(RPi Zero)          O3       ARM11              800       0.33   1730          2.16
    STM32H750VBT6              O3       Cortex-M7          480       0.40   1412          2.94
    STM32H750VBT6              Os       Cortex-M7          480       0.61    933          1.94
    BCM2835(RPi Zero)          Os       ARM11              800       0.68    833          1.04
    GD32F450ZET6(oc)           O3       Cortex-M4          400       1.08    527          1.32
    AT32F435CMT7(oc)           O3       Cortex-M4          368       1.15    495          1.34
    GD32F470VIT6(oc)           O3       Cortex-M4          360       1.21    470          1.31
    GD32W515PIQ6(oc)           O3       Cortex-M33         320       1.23    462          1.44
    GD32E503CET6(oc)           O3       Cortex-M33         272       1.40    407          1.49
    GD32VF103CBT6(oc)          O3       RISC-V             192       1.49    382          1.99
    AT32F435CMT7               O3       Cortex-M4          288       1.54    370          1.28
    GD32EPRTVDT6(oc)           O3       Cortex-M33         240       1.59    358          1.49
    GD32FFPRTGU6(oc)           O3       Cortex-M4          280       1.76    323          1.15
    GD32F350CBT6(oc)           O3       Cortex-M4          280       1.80    316          1.13
    GD32F470VIT6               O3       Cortex-M4          240       1.81    314          1.31
    CH32V305RB(oc)             O3       RISC-V             208       1.85    308          1.48
    AT32F435CMT7(oc)           Os       Cortex-M4          368       2.07    275          0.75
    GD32E503CET6               O3       Cortex-M33         176       2.15    265          1.50
    GD32F450ZET6               O3       Cortex-M4          200       2.16    263          1.32
    GD32W515PIQ6               O3       Cortex-M33         180       2.19    260          1.45
    STM32F407VET6              O3       Cortex-M4          168       2.59    220          1.31
    GD32VF103CBT6              O3       RISC-V             108       2.66    214          1.98
    CH32V305RB                 O3       RISC-V             144       2.69    212          1.47
    AT32F435CMT7               Os       Cortex-M4          288       2.79    204          0.71
    GD32F103RCT6(oc)           O3       Cortex-M3          192       2.82    202          1.05
    GD32FFPRTGU6               O3       Cortex-M4          168       2.93    194          1.16
    GD32F470VIT6               Os       Cortex-M4          240       3.08    185          0.77
    GD32E103CBT6               O3       Cortex-M4          120       3.77    151          1.26
    GD32W515PIQ6               Os       Cortex-M33         180       3.83    149          0.83
    GD32E503CET6               Os       Cortex-M33         176       4.19    136          0.77
    STM32L431CCT6(oc)          O3       Cortex-M4          136       4.40    129          0.95
    GD32F103RCT6(oc)           Os       Cortex-M3          192       4.43    128          0.67
    GD32F350CBT6               O3       Cortex-M4          108       4.57    125          1.15
    STM32F303CCT6(oc)          O3       Cortex-M4          128       4.71    121          0.94
    STM32F407VET6              Os       Cortex-M4          168       4.84    118          0.70
    CH32V305RB(oc)             Os       RISC-V             192       5.02    113          0.59
    GD32E230C8T6(oc)           O3       Cortex-M23         144       5.05    113          0.78
    STM32F401RET6              O3       Cortex-M4           84       5.21    109          1.30
    STM32L431CCT6              O3       Cortex-M4           80       5.32    107          1.34
    STM32L431CCT6(oc)          Os       Cortex-M4          136       5.57    102          0.75
    GD32VF103CBT6              Os       RISC-V             108       6.00     95          0.88
    ESP8266                    O3       Xtensa L106         80       6.38     89          1.12
    CH32V305RB                 Os       RISC-V             144       6.69     85          0.59
    GD32F103RCT6               O3       Cortex-M3           72       7.54     75          1.05
    GD32E103CBT6               Os       Cortex-M4          120       8.11     70          0.58
    STM32F303CCT6              O3       Cortex-M4           72       8.49     67          0.93
    STM32F103VET6              O3       Cortex-M3           72       8.71     65          0.91
    STM32F401RET6              Os       Cortex-M4           84       9.19     62          0.74
    STM32L431CCT6              Os       Cortex-M4           80       9.28     61          0.77
    GD32E230C8T6(oc)           Os       Cortex-M23         144       9.41     60          0.42
    STM32F303CCT6(oc)          Os       Cortex-M4          128       9.49     60          0.47
    GD32E230C8T6               O3       Cortex-M23          72      10.44     55          0.76
    GD32F103RCT6               Os       Cortex-M3           72      11.83     48          0.67
    ESP8266                    Os       Xtensa L106         80      12.20     47          0.58
    STM32F070CBT6              O3       Cortex-M0           48      14.90     38          0.80
    STM32F303CCT6              Os       Cortex-M4           72      16.80     34          0.47
    STM32F103VET6              Os       Cortex-M3           72      18.33     31          0.43
    GD32E230C8T6               Os       Cortex-M23          72      19.02     30          0.42
    STM32L051C8T6              O3       Cortex-M0           32      25.30     22          0.70
    STM32F070CBT6              Os       Cortex-M0           48      27.52     21          0.43
    XL2409                     O3       Cortex-M0+          24      33.00     17          0.72
    STM32L051C8T6              Os       Cortex-M0           32      42.90     13          0.41
    XL2409                     Os       Cortex-M0+          24      53.40     11          0.44
    ATMEGA16                   O3       AVR                 16      67.00    8.5          0.53
    ATMEGA328P                 O3       AVR                 16      71.90    7.9          0.49
    CH573                      O3       RISC-V              60      73.60    7.7          0.13
    ATMEGA328P                 Os       AVR                16       74.00    7.7          0.48
    CH573                      O3       RISC-V             20       78.00    7.3          0.36
    CH592                      O3       RISC-V             60       79.10    7.2          0.12
    CH592                      O3       RISC-V             20       82.40    6.9          0.35
    CH573                      Os       RISC-V             60       85.50    6.7          0.11
    ATMEGA16                   Os       AVR                16       93.50    6.1          0.38
    STM8L151G6U6               fast     STM8               16      107.10    5.3          0.33
    STM8S003F3U6               fast     STM8               16      107.20    5.3          0.33
    STM8S003F3U6               compact  STM8               16      108.10    5.3          0.33
    STM8L151G6U6               compact  STM8               16      121.00    4.7          0.29
    CH592                      Os       RISC-V             20      124.80    4.6          0.23
    CH592                      Os       RISC-V             60      124.60    4.6          0.08
    STC8A8K64S4A               speed    8051               24      254.00    2.2          0.09
    NRF24LE1                   size     8051                16     883.00    0.6          0.04
    NRF24LE1                   speed    8051                16     884.00    0.6          0.04


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

## ChangeLog

**2025.4.12**

Added CH32V305RB

**2025.3.10**

Added STM32F303CC

**2025.2.9** 

Added CH592 & AT32F435


**2025.1.16** 

Added GD32E230C8T6 @ 144MHz (oc)
