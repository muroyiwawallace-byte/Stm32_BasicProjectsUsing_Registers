# Stm32_BasicProjectsUsing_Registers
This Concept is about how to blink an LED using Timers as delay instead of software delays
APPARATUS
1.2 LEDS
2.STM32F401RE MCU Board
3.2 Resistors
4.Power Supply
5.BreadBoard
6.Programmer(ST LINK)
THEORY
A Timer is hardware  counter that counts clock pulses.The timer works independent of the CPU.The Oveflow method involves starting the counter and when  the timer reaches its maximum value it overflows .Once it overflows this enables an interrupt that stops the CPU from working.A timer consist of the following of the following things 
CLOCK->PRESCALER->COUNTER->FLAG/INTERRUPT
Prescaler is used to slow down the Clock  that is if the clock frequency is 16MHz(16Mticks per second) if the prescaler is set to a value of 1600-1 then that would mean it would mean the timer tick is now(16MHz/1600-1)
TIMER OVERFLOW TIME = PRESCALER*(MAX COUNT-INITIAL VALUE)
                            CLOCK FREQUENCY
CONFIGUATION DETAILS
 Clock frequency                                         16MHz
 Timer used (Timer0, Timer1, etc.)          TIMER 3
 Prescaler value                                            16000-1
 Initial counter value                                    0
Mode used (Normal mode)                        Normal Mode

