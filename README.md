# INTRODUCTION TO ASSEMBLY CODING FOR COMPUTER ARCHITECHTURE - COURSE

## ABOUT MIPS

"In this repo, I focus on MIP with R-format

### R-FORMAT

For the R-format instruction, there're 6 components:

- Operation code (op) - 6 bits [ 31 -> 26] # Always 000000
- First source register (rs) - 5 bits [ 21 -> 25]
- Second source register (rt) - 5 bits [ 16 -> 20]
- Destination register (rd) d - 5 bits [ 11 -> 15]
- Shift amount (shamt) - 5 bits [ 6 -> 10] # Use for sll, srl, sra, else: 00000
- Function bits (funct) - 6 bits [ 0->5] 

Some types of function bits

- 100000 (0x20)  : ADD
- 100001 (): ADDU
- 100010  : SUB
- 100100  : AND
- 100101  : OR
- 100111  : NOR
- 101010  : SLT (set on less than)
- 000000  : SLL (shift left)
- 000010  : SRL (shift right)
- 001000  : JR









