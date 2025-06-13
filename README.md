# ATmega16 Project
This project demonstrates how to integrate Assembly (ASM) and C code on the ATmega16 microcontroller using IAR Embedded Workbench for AVR. The main program is written in Assembly and performs hardware-level
initialization and register operations, while calling two external functions written in C. The calc function adds two unsigned short variables, and the par function checks if the result is even by computing the
remainder modulo 2. The project is structured to initialize two variables directly in ASM, pass them to the C function for computation, and then use the result for parity checking. To run the project, clone the
repository, open it in IAR Embedded Workbench, set the device to ATmega16, choose the Tiny memory model with no optimization, enable output listings and debugging files, build the project, and optionally upload the
generated HEX file to a real microcontroller using AVRDUDE or a USBasp programmer.







