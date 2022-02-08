# Mediklik_Assignment

A 16 MHz internal RC oscillator is used as a clock.

UART1_TX  PB6 pin
UART1_RX  PB7 pin

Timer4 for toggling GPIO output in mode 2
Timer4 prescaler value is 1000.
Timer4 counter period auto reload register is set to 4000 in up counter mode

PB5 -GPIO output
Timer3 for PWM generation PB4 pin as channel 1
Timer3 prescaler value is 0.
Timer3 counter period auto reload register is set to 516 in up counter mode
Timer 3 PWM duty cycle is 50%

PA13 GPIO ADC input
PA14 GPIO ADC input
PA15 GPIO ADC input

Interrupts enabled for Timer4 and USART


