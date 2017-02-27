# Computer-Systems-2

Tasks and activities performed in the module Comp2215 on a La Fortuna board
Designed by Professor Steve R Gunn.

Micro-controller Board with - ATMEL AVR AT90USB1286

    1.  8-bit AVR controller
    2.  Color Display
    3.  Rotary encoder
    4.  5 Buttons
    5.  Micro SD card
    6.  Audio & USB connector
    7.  Digital I/O, Analogue I
    8.  Serial port, JTAG
    9.  8 MHz, VCC=3.3 V
    10. 8 KB RAM
    11. 128 KB Flash
    12. 4 KB EEPROM
    13. 4 Timer
    14. 8 ch. 10 bit ADC
    15. 320×240 TFT
    16. 18 bit Color

##Task 1

The objective for the 1st task was to program the rotary encoder and adjust the
frequency of the flashing led light according to the input received.
The code uses Dr Klaus Peter Zauner's adaptation of Peter Dannegger's code for
scanning input received by the rotary encoder

##Task 2

The objective for this task was to make our own minimal printf function using
the lcd library on the laFortuna board.The program uses the lcd.h and lcd.c
libraries made for laFortuna board made by Professor Steve Gunn and the code for
the printf function is inspired by tiny printf that can be found on
http://www.sparetimelabs.com/printfrevisited/printfrevisited.php


##Task3

The objective for this task was to understand scheduling in CPU processed and program the LED of the Fortuna hardware to turn on every time the CPU was idle(all processes were preparing to get executed or were on a delay). The second part of the task was to harmonically sync all the processes and see the behavior of the CPU on different task number, task period, and task duration.
Some of the code used in the task is Dr. Klaus Peter Zauner's adaptation of RIOS version 1.2 by Frank Vahid, Tony Givargis, and Bailey Miller from Univ. of California, Riverside and Irvine adapted for the AVR hardware.
