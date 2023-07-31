# Design of a Simple General-Purpose Processor in VHDL using Quartus Simulator

## Objective
The main objective of the laboratory experiment is to design and build an ALU using VHDL. The ALU will be composed of five components: 2 gated D Latches, 1 Moore Finite State Machine (FSM), 1 4-to-16 decoder, and 1 ALU core. The ALU's functions will be implemented using VHDL code, and a final design block diagram will be created for each problem set.

## Components
# Gated D Latch (D flip-flop): A storage element that copies input to output based on a clock signal. When the clock is high-active, the latch copies the input to the output, and when the clock is low-active, it remains in its previous state.
# Moore Finite State Machine (FSM): A finite state machine where output values depend only on the current state. It operates with inputs such as Clock, data input, and reset, and produces outputs like student number ID digits and the current state.
# 4-to-16 Decoder: A circuit element that decodes a 4-bit input into a 16-bit output with the help of an Enable signal. Only one bit can be active (high) at a time for each valuation.
# ALU Core: The main block responsible for allowing a change in operations so that all 9 functions can be performed.

## ALU Problem Sets
# ALU_1: Performs operations like addition, subtraction, AND, OR, NAND, NOR, XOR, XNOR, and NOT logical operators. All nine functions are arranged in a specific order and executed one at a time with rising edges of the Clock input.
# ALU_2: Similar to ALU_1 but with a new list of operations to execute.
# ALU_3: Responsible for a single operation, but for all 9 valuations. It checks whether any of the two digits of number "B" or 44 are greater than the student ID output at each valuation.
# Synchronization: The ALUs for all problem sets are synchronous, meaning all blocks requiring the Clock input work together with the same Clock input.

## Conclusion
The lab experiment proved to be lengthy, interesting, and challenging. Despite some issues with read-only waveforms, the functions were successfully implemented using VHDL code and schematic design. The conclusion is that different types of ALUs can be implemented using VHDL and CAD design and can be successfully implemented on an FPGA (Field-Programmable Gate Array) board.
