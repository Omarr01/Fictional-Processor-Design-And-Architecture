# Fictional-Processor-Design-And-Architecture
This project is a simulation of a fictional processor design and architecture.

## Architecture: Harvard
- Harvard Architecture is the digital computer architecture whose design is based on the concept
where there are separate storage and separate buses (signal path) for instruction and
data. It was basically developed to overcome the bottleneck of Von Neumann Architecture.
## Registers
- 64 General-Purpose Registers (GPRS), Names: R0 to R63
- 1 Status Register
- 1 Program Counter
## Instruction Set Architecture
- Instruction Size: 16 bits
- Instruction Types: 2 (R-Format and I-Format)
- Instruction Count: 12
## Datapath
### Stages: 3
- Instruction Fetch (IF)
- Instruction Decode (ID)
- Instruction Execute (IE)
### Pipeline 
- 3 instructions (maximum) running in parallel
- Data Hazards are NOT handled
- However, Control Hazards are handled
## Technologies
- Java
