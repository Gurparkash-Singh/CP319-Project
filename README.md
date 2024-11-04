# CP319-Project

For this Project we need to create a RISC-V simulator in VHDL.
The simulator must be able to execute at least 10 RV32i instructions.

The system will be broken down into the following components:
    1. Registers
    2. Decoder
    3. Control
    4. ALU

The following instructions will be added:
    1. Load Immediate
    2. Move
    3. Add
    4. Subtract
    5. And
    6. Or
    7. Nor
    8. Logical Shift Left
    9. Logical Shift Right
    10. Set Less Than

These instructions were chosen as they do not require memory, only registers.
This will decrease the complexity of the circuit.