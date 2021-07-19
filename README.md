# dhrystone_score

Dhrystone score of some MCUs

    MCU                Opt                Compiler                       Freq/MHz   Time/ms   DMIPS       DMIPS/MHz
    AMD R5-3600X       O3                 gcc 5.1.0                     4350      0.02    24322.73         5.59
    AMD R5-3600X       Os                 gcc 5.1.0                     4350      0.05    11383.04         2.62
    GD32FFPRTGU6       O3                 arm-none-eabi-gcc 4.9.3        280      1.76      323.38         1.15
    GD32F350CBT6       O3                 arm-none-eabi-gcc 4.9.3        280      1.80      316.20         1.13
    STM32F407VET6      O3                 arm-none-eabi-gcc 4.9.3        168      2.59      219.75         1.31
    GD32FFPRTGU6       O3                 arm-none-eabi-gcc 4.9.3        168      2.93      194.25         1.16
    GD32F350CBT6       O3                 arm-none-eabi-gcc 4.9.3        108      4.57      124.54         1.15
    STM32F407VET6      Os                 arm-none-eabi-gcc 4.9.3        168      4.84      117.59         0.70
    STM32F401RET6      O3                 arm-none-eabi-gcc 4.9.3         84      5.21      109.24         1.30
    STM32F103VET6      O3                 arm-none-eabi-gcc 4.9.3         72      8.71       65.34         0.91
    STM32F401RET6      Os                 arm-none-eabi-gcc 4.9.3         84      9.19       61.93         0.74
    STM32F070CBT6      O3                 arm-none-eabi-gcc 4.9.3         48     14.90       38.20         0.80
    STM32F103VET6      Os                 arm-none-eabi-gcc 4.9.3         72     18.33       31.05         0.43
    STM32F407VET6      O3                 arm-none-eabi-gcc 4.9.3         16     27.00       21.08         1.32
    STM32F401RET6      O3                 arm-none-eabi-gcc 4.9.3         16     27.23       20.90         1.31
    STM32F070CBT6      Os                 arm-none-eabi-gcc 4.9.3         48     27.52       20.68         0.43
    STM32F103VET6      O3                 arm-none-eabi-gcc 4.9.3          8     59.00        9.65         1.21
    GD32FFPRTGU6       O3                 arm-none-eabi-gcc 4.9.3          8     61.50        9.25         1.16
    GD32F350CBT6       O3                 arm-none-eabi-gcc 4.9.3          8     61.55        9.25         1.16
    ATMEGA328P         O3                 avr-gcc 7.3.0                   16     71.90        7.92         0.49
    ATMEGA328P         Os                 avr-gcc 7.3.0                   16     74.00        7.69         0.48
    STM32F070CBT6      O3                 arm-none-eabi-gcc 4.9.3          8     80.00        7.11         0.89
    STM8L151G6U6       fast               cosmic c 4.4.12                 16    107.10        5.31         0.33
    STM8S003F3U6       fast               cosmic c 4.4.12                 16    107.20        5.31         0.33
    STM8S003F3U6       compact            cosmic c 4.4.12                 16    108.10        5.27         0.33
    STM8L151G6U6       compact            cosmic c 4.4.12                 16    121.00        4.70         0.29
    STC8A8K64S4A       opt-code-speed     sdcc 3.8.0                      24    254.00        2.24         0.09
    NRF24LE1           opt-code-size      sdcc 3.8.0                      16    883.00        0.64         0.04
    NRF24LE1           opt-code-speed     sdcc 3.8.0                      16    884.00        0.64         0.04

