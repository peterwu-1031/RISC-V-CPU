# Implementing a CPU using Verilog(CHIP.v)
## Introduction to my CPU:
#### My CPU supports single cylce instructions defined in the RISC-V instruction set including "auipc", "jal", "jalr", "beq", "lw", "sw", "addi", "slti", "slli", "srli", "add", "sub" and is also able to perform 32-bits multiplication in 33 cycles.
## How it works:
#### In folders named fact, leaf and hw1, I translated three different functions written in Python(.py file) into RISC-V instructions(.s file). Then, I translated these RISC-V instructions into machine codes(.txt file) by Jupiter and they would executed by my CPU.
