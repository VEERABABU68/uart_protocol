# uart_protocol
📘 Overview

This project implements a UART (Universal Asynchronous Receiver Transmitter) protocol in Verilog HDL.
It provides a modular design with separate Transmitter (TX) and Receiver (RX) blocks, integrated in a top-level module.
The UART enables asynchronous serial communication between digital systems — typically between a processor and peripheral or between FPGA boards.

⚙️ Key Features

Parameterized clock frequency and baud rate

Modular structure: uarttx, uartrx, and uart_top

Start and stop bit handling

Simple finite state machine (FSM) based control

Works with 8-bit data frames

Includes a SystemVerilog interface (uart_if) for verification
