Name: Jaxon Coward

EID: jsc3536

Team Number: 14

## Questions

1. Why does your program need a setup and a loop?

    To have some code that won't repeat and a continuous routine to run.

2. What is the downside to putting all your code in a loop?

    It never stops running and may repeat things it shouldn't if you make a mistake.

3. Why does your code need to be compiled?

    To convert it into binary that can be executed by the machine.

4. When lowering the frequency in procedure A, step 8, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    At 30 Hz severe flickering appears. I would guess this is because its too close to the speed at which our eyes refresh. Don't go below 40 Hz

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    So that they have a common reference.

6. What is the difference between synchronous and asynchronous communication?

    Synchronous signals share a clock, asynchronous have to send special signals to synchronize themselves

7. Profile of UART: Sent X bytes in Y time

    3 bytes in 3.07 ms

8. Profile of SPI: Sent X bytes in Y time

    3 bytes in 66.63 us

9. Why is SPI so much faster than UART?

    Because the common clock allows the signal transfer speed to be drastically increased.

10. list one pro and one con of UART

    Easy to interface device to device. Slower than other methods.

11. list one pro and one con of SPI

    Fast but uses more pins.

12. list one pro and one con of I2C

    Easy to interface many peripheral devices. Slow and doesn't interface well over distance due to poor noise immunity.

13. Why does I2C need external resistors to work?

    A pull-up resistor is necessary to pull the line high when no devices are pulling it low.

## Screenshots

Procedure A, step 3:
![Put path to your image here ->](img\Blinking.PNG)

Procedure A, step 7:
![Put path to your image here ->](img\Dimming.PNG)

Procedure B, UART:
![Put path to your image here ->](img\UART.PNG)

Procedure B, SPI:
![Put path to your image here ->](img\SPI.PNG)
