# Fictional-Processor-Design-And-Architecture
This project is a simulation of a fictional processor design and architecture.

## Technologies
- Java
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
- 
![image](https://user-images.githubusercontent.com/68354610/175125804-42fdad48-bc3b-480f-9601-c5f34f3775cd.png)
![image](https://user-images.githubusercontent.com/68354610/175125868-ad52e179-0d31-4d85-b030-52e83439e7b1.png)
- Instruction Count: 12
![image](https://user-images.githubusercontent.com/68354610/175104906-647def9a-7583-458b-ac2b-0cad6cddbfad.png)
## Datapath
### Stages: 3
- Instruction Fetch (IF)
- Instruction Decode (ID)
- Instruction Execute (IE)
### Pipeline 
- 3 instructions (maximum) running in parallel
- Data Hazards are NOT handled
- However, Control Hazards are handled
