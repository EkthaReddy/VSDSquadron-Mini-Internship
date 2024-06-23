# VSDSquadron-Mini-Internship
An internship on RISC-V and VLSI using VSDSquadron Miniboard provided by VLSI System Design(VSD). 

## Overview of the internship
The internship provides the Code Specification through C modelling.
It involves two process

Chip Modelling

- Running testbench in C language for C model Specifications
- Build processor application specification

RTL Archietecture


- Soft copy of the hardware using Verilog

## Task 1
The task 1 includes the following
- Installation of RISC-V toolchain using VDI.
- C Program for sum from one to n.
- Checking the result of C code
- RISC-V Simulator for compiling and running the code
- Assembly language


 The steps to be followed are:
 
#### Step 1: Installation of Oracle VirtualBox, which is an open source virtualization software. The virtual machine have an operating system and used as a physical computer inside your laptop.


![Screenshot (567)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/48ae5d97-0ce1-40bd-9403-e60d255d4758)

#### Step 2: Open the terminal inside the VirtualBox


![Terminal inside the VM](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/5e831292-ae27-4409-b6d4-dc98b50fb88a)

#### Step 3: Write the command below to open the editor named leafpad to write C code

![Screenshot (568)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/baf5e27b-ee8b-42a9-b2c7-e40bb88c33d8)
 Note for the above command explanation:
 - command line cd is to check for home directory
 - leafpad to open editor 
 - sum_one_to_one is the file name C code in editor


#### Step 4: Write the C program for sum of one to n in the terminal 
![Screenshot (570)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/6e565127-674e-47c4-8c48-f142e319ebce)


![C Code for sum from one to n](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/37e5d37e-7b55-49ce-8aef-70d3d9f57d0e)

Save the file in the editor

#### Step 5: To check the result of C code

- Type the below command line to ensure the fle is saved.
![WhatsApp Image 2024-06-23 at 11 39 36 PM](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/c70488ff-78d7-4c14-910c-28feea698aca)

![WhatsApp Image 2024-06-23 at 11 39 36 PM (1)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/093bd684-20dc-4a5d-bdbf-57e5aa9de063)

- This ./a.out command will generate the output 


- The sum for 1 to 5 is 15 which is also verified using calculator


![with cc](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/42492408-96b8-4275-95ae-c7966b65854a)

#### Step 6: Compile and run the C code using RISC-V Simulator 

- Compile the code with RISC-V compiler by using the command line
  
![Screenshot (572)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/db9d65fc-a0bd-4104-9d12-d77d19614d07)

- Run the C code by RISC-V Simulator using below

![Screenshot (573)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/cd4c2428-a270-4d1e-a75c-0b09c212ecd2)



![compile riscv with gcc![Uploading Screenshot (572).png…]()
 ](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/dbf0af7d-fe05-4547-a280-7b710e39f924)


#### Step 7: Assembly code 
- Command line for generating the assembly code is:

![WhatsApp Image 2024-06-24 at 12 08 16 AM](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/0850193a-d680-4772-a4b8-52e08c05c943)

- The Assembly codes:

![assembly code of C code](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/0ce26ef8-3b1e-41dd-8830-217cddd2d7fc)


- After that type out this line;

![WhatsApp Image 2024-06-24 at 12 08 16 AM (1)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/2cc69a0e-c167-4320-bf89-a7910f76ac37)

#### Step 8: Search the main() 

![main section of assembly code](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/053a0a17-79c8-48af-8227-f59f7dd6786e)



