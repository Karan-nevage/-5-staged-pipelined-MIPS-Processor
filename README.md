# -5-staged-pipelined-MIPS-Processor

A 5-stage pipelined MIPS processor is a type of Reduced Instruction Set Computing (RISC) processor designed to execute instructions efficiently by dividing the process into five distinct stages. Each stage handles a specific part of the instruction execution process, allowing multiple instructions to be processed simultaneously1. The five stages are:

# Instruction Fetch (IF): 
The processor fetches the instruction from memory.

# Instruction Decode (ID): 
The fetched instruction is decoded to determine the required actions.

# Execution (EX): 
The processor performs the operation specified by the instruction.

# Memory Access (MEM): 
The processor accesses memory if the instruction requires it.

# Write Back (WB): 
The result of the instruction is written back to the register file.

This pipelining technique improves the overall performance by overlapping the execution of multiple instructions, reducing the time needed to complete each instruction.
