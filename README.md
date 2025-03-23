# RISCV core
A 32-bit RISC-V processor architecture.  
This project was devoloped as the final deliverable for the "Design of integrated systems" course during my Master's degree.  
The core's functionality has been validated through various applications that included interfacing with GPIO, I2C, timer and digital filter (with hardware acceleration) modules. 

## Features
RV32I implemented instructions:  
* I-type: JALR, LW, ADDI, SLTI, XORI, ORI, ANDI, SLLI, SRLI, SRAI;
* R-type: ADD, SUB, SLL, XOR, SRL, SRA, OR, AND
* B-type: BEQ, BNE, BLT, BGE, BLTU, BGEU
* S-type: SW
* J-type: JAL

5-stages pipeline:  
* Data forwarding  
* Branch handling  
* Pipeline stall  
