# RISC-V CPU (CHIP.v)
## Introduction:
My CPU supports single cylce instructions in the RISC-V instruction set including "auipc", "jal", "jalr", "beq", "lw", "sw", "addi", "slti", "slli", "srli", "add", "sub" and is also able to perform 32-bit multiplication in 33 cycles.
## How it works:
* I translated three different functions written in Python(.py) in "fact", "leaf" and "hw1" into RISC-V instructions(.s) and then translated RISC-V instructions into machine codes(.txt).
* Users could use 'Final_tb.v' to test the machine codes with my CPU:
<pre> ncverilog Final_tb.v +define+fact +access+r </pre>
P.S. The license for ncverilog is required.
