# Lab 3 - Datapath Control Unit
## Test Case Descriptions
Test case 1 is testing for the and instruction. A = 0xFFFFFFFF, B = 0x0001, Result: 0x0001 <br>
Test case 2 is testing for the or instruction. A = 0xFFFFFFFF, B = 0x0001, Result: 0xFFFFFFFF <br>
Test case 3 is testing for the add instruction. A = 0xFFFFFFFF, B = 0x0001, Result: 0x0000 <br>
Test case 4 is testing for the sub instruction. A = 0xFFFFFFFF, B = 0x0001, Result: 0xFFFFFFFE <br>
Test case 5 is testing for the slt instruction. A = 0xFFFFFFFF, B = 0x0001, Result: 0x0001 <br>
Test case 6 is testing for the nor instruction. A = 0xFFFFFFFF, B = 0x0001, Result: 0x0000 <br>
Test case 7 is testing for the addi instruction. A = 0xFFFFFFFF, Immediate = 0x0004, Result: 0xFFFFFFFF <br>
Test case 8 is testing for the lw instruction. Base = 0x000000FF, Offset = 0x0020, Address: 0x011F <br>
Test case 9 is testing for the sw instruction. Base = 0x000000FF, Offset = 0x0064, Address: 0x0163 <br>
Test case 10 is testing for the beq instruction. A = 0x000000FF, B = 0x0025, Branch not taken <br>

## add vs. addi
Add is an R type instruction with no immediate field. It takes the RegDst, RegWrite, and ALUOp1 signals in the datapath. Addi is an I type instruction that takes the ALUSrc and RegWrite signals in the datapath.
