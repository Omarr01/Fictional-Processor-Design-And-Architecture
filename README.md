# Fictional-Processor-Design-And-Architecture
This project is a simulation of a fictional processor design and architecture.

## Architecture: Harvard
- Harvard Architecture is the digital computer architecture whose design is based on the concept
where there are separate storage and separate buses (signal path) for instruction and
data. It was basically developed to overcome the bottleneck of Von Neumann Architecture.
## Registers:
- 64 General-Purpose Registers (GPRS), Names: R0 to R63.
- 1 Status Register
- 1 Program Counter
## Instruction Set Architecture
- Instruction Size: 16 bits
- Instruction Types: 2 (R-Format and I-Format)
- Instruction Count: 12
ADD R1 R2 -- R1 = R1 + R2
SUB R1 R2 R1 = R1 - R2
Multiply MUL R MUL R1 R2 R1 = R1 * R2
Move Immediate MOVI I MOVI R1 IMM R1 = IMM
Branch if Equal Zero BEQZ I BEQZ R1 IMM IF(R1 == 0) {
PC = PC+1+IMM }
And Immediate ANDI I ANDI R1 IMM R1 = R1 & IMM
Exclusive Or EOR R EOR R1 R2 R1 = R1 ⊕ R2
Branch Register BR R BR R1 R2 PC = R1 || R2
Shift Arithmetic Left SAL I SAL R1 IMM R1 = R1 << IMM
Shift Arithmetic Right SAR I SAR R1 IMM R1 = R1 >> IMM
Load to Register LDR I LDR R1 ADDRESS R1 = MEM[ADDRESS]
Store from Register STR I STR R1 ADDRESS MEM[ADDRESS] = R1

