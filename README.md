# Chthonia

Pronounced "Though-knee-ya", named after Chthonian planets, a hypothetical class
of planets that are the remnant cores of gas giants.

This will be a basic 5-stage pipelined RISC-V core, created purely for my own
learning. It will support the RV32I ISA.

# Pipeline structure

1. Fetch

Fetch the instruction from memory

2. Decode

Derive the operation and operands

3. Execute

Based on the instruction values, carry it out

4. Memory Access

Data memory is accessed if the instruction requires it

5. Writeback

Results are written back to the register file (if there are any)

# Instructions to support

The goal of the CPU core is to support the complete RV32I ISA

## I Type
- [ ] lb
- [ ] lh
- [ ] lw
- [ ] lbu
- [ ] lhu
- [ ] addi
- [ ] slli
- [ ] slti
- [ ] sltiu
- [ ] xori
- [ ] srli
- [ ] srai
- [ ] ori
- [ ] andi
- [ ] jalr

## U Type
- [ ] auipc
- [ ] lui

## S Type
- [ ] sb
- [ ] sh
- [ ] sw

## R Type
- [ ] add
- [ ] sub
- [ ] sll
- [ ] slt
- [ ] sltu
- [ ] xor
- [ ] srl
- [ ] sra
- [ ] or
- [ ] and

## B Type
- [ ] beq
- [ ] bne
- [ ] blt
- [ ] bge
- [ ] bltu
- [ ] bgeu

## J Type
- [ ] jal
