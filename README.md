# NRF24L01 library for STM32

This Arduino library is for NRF24L01 modules and STM32 ARM MCU's

It is based on the TMRh20 library: https://tmrh20.github.io/RF24/

It's coming from: http://www.stm32duino.com/viewtopic.php?f=15&t=317&start=40

It appears to work fine in my STM32 based "Micro RC 2" prototype. The radio connection even works from Atmega to ARM and vice versa. But I don't recommend to use it for critical applications at the moment. I will have to do more tests before.

STM32 Module used for the test: https://www.ebay.com/itm/STM32F103C8T6-ARM-STM32-Minimum-System-Development-Board-Module-For-Arduino-/311156408508?rsta=de_CH(en_CH)&cnac=CH&mail=sys&e=op&unp_tpcid=email-receipt-auction-payment&ppid=PPX000608&calf=495fcc1c68f6c&calc=495fcc1c68f6c&pgrp=main:email&unptid=307cc924-d286-11e7-aa75-3cd92bee8ddc&mchn=em&t=&s=ci&page=main:email&cal=495fcc1c68f6c&cust=07W96197D7008364U

Please note, that "printf" does not work!

It can be installed in parallel with the original RF24 library, because it was renamed to RF24_STM:
#include <RF24_STM32.h> // This is for an STM32 MPU
#include <RF24.h> // This is for an Atmega 328 MPU

How to use: http://tmrh20.github.io/RF24/classRF24.html

Changelog:
-- Added keywords.txt for some syntax coloring
