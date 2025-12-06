<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The NAND gate is the opposite of an AND gate, meaning it produces the inverse of the AND function. Its symbol looks like an AND gate with a small circle at the output to represent inversion. The logic of a NAND gate can be understood by first performing an AND operation and then inverting the result.

In Verilog HDL, we begin by declaring a module, which is the basic building block used to describe a digital circuit. The keyword module is used to define the module name, and in this case, NAND_2 is the module identifier. The list inside the parentheses is called the port list and defines the input and output signals for the module. After defining the ports, any internal data types needed for the design are declared.

The signal Yd is declared as a wire, which represents an internal electrical connection in the circuit and is not included in the port list. An AND operation is then performed on inputs A and B, and the result is stored in Yd. This intermediate signal is passed through a NOT gate, producing the final output Y. Verilog understands logical operations such as AND and NOT in the same way they are implemented in hardware. Finally, the endmodule statement is used to end and complete the module definition.

## How to test

Refer to the truth table for a NAND gate

## External hardware

None
