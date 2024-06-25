# VSDSquadron-Mini-Internship
An internship on RISC-V and VLSI using VSDSquadron Mini Board provided by Kunal Gosh in VLSI System Design (VSD).

## Overview of the internship

The internship is about the two main key take aways:

#### 1. Chip Design

To build the chip, there should be a code specification especially in C model for applications to run. 
In simpler terms,
making of the chip which needs RISC-V processor and it will start from the basic step of specification. 
Specification for RISC-V processor which is used in various applications like  embedded systems, automotive systems, artificial intelligence and many more. 

Note: The specifications can also be application specific, basically the SoC designs which made of ASSIC, microcontroller and microprocessor.

So, VSDSquadron Mini Board provided is the microcontroller which designed to apply for any applications.
The board will have the modelling specification in C which will check whether the application is working or not through testbench which are the test vectors to determine the accuracy and correctness of the model.

Basically, the process involes running simulation for c model and applicatios to present the output.

Therefore, this part is all about
- Running testbench in C language for C model Specifications
- Build processor application specification

#### 2. RTL Architecture

Soft copy of the hardware is written in Hardware Description Language .i.e., processor model is converted into the HDL because application can run faster in HDL compared with a software.

Therefore, this part explains the,
- Soft copy of the hardware using Verilog


And in the final step the output from chip design and RTL Architecture must be equal to show that the desired output from models are achieved.


## Task 1
The task 1 of the internship includes the following
- Installation of RISC-V toolchain using VDI.
- C Program for sum from one to n.
- Checking the result of C code
- RISC-V Simulator for compiling and running the code
- Assembly language

Overall, it is about writing the C code for sum from one to n followed by compiling and running by RISC-V Simulator.

 The steps to be followed are:
 
#### Step 1: Installation of Oracle VirtualBox.

The VirtualBox is an open source software and an operating system which runs as a physical computer inside the pc/laptop. 

![Screenshot (567)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/48ae5d97-0ce1-40bd-9403-e60d255d4758)

#### Step 2: Open the terminal inside the VirtualBox

![Terminal inside the VM](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/5e831292-ae27-4409-b6d4-dc98b50fb88a)

#### Step 3: To open the editor named leafpad for writing C code.

![Screenshot (568)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/baf5e27b-ee8b-42a9-b2c7-e40bb88c33d8)
 Note for the above command explanation:
 - command line cd is to check for home directory.
 - leafpad to open editor.
 - sum_one_to_one is the file name for C code to be written in editor.


#### Step 4: Write the C program for sum of one to n in the terminal 

The leafpad editor opened, write the simple c code for sum of 1 to n,

![Screenshot (570)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/6e565127-674e-47c4-8c48-f142e319ebce)

Save the file in the editor


![C Code for sum from one to n](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/37e5d37e-7b55-49ce-8aef-70d3d9f57d0e)


#### Step 5: To check the result of C code

- Type the below command line to ensure the file is saved.
  
![WhatsApp Image 2024-06-23 at 11 39 36 PM](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/c70488ff-78d7-4c14-910c-28feea698aca)

- This ./a.out command will generate the output 

![WhatsApp Image 2024-06-23 at 11 39 36 PM (1)](https://github.com/EkthaReddy/vsdsquadron-mini-internship/assets/152515939/093bd684-20dc-4a5d-bdbf-57e5aa9de063)



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





## Task 2
#### Change Dispense Wizard: Engineering a Vending Machine with Advanced Change System

Task 2 is about writing the c program for the selected project along with compiling and runing with gcc command. But, before that Let us first take a look on Vending Machine and it's functunality.


### What is Vending Machine?

A vending machine is a large self-service, often box-like device that sells small items like snacks, drinks, or other goods. You put money or a credit card into the machine, choose what you want to buy by pressing a button or touchscreen, and then the machine gives you the item you selected. It’s a convenient way to buy things quickly without needing to go to a store or interact with a cashier.

![image](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/e768dbd5-291a-4e52-841c-b0215eac0530)

This is what a vending machine looks like and we often find them at places like airport, metro stations or amusement parks.

### Project : Functions of my Vending Machine 
#### What does it do?

We now know that, vending machine sells the desired goods when the coins are inserted,
In this project we will be using 5, 10, 20 and 50 ruppee coins to purchase a five ruppee product.
In this, it will have five case to represent each transaction that are going to have ,i.e., the each case will represent the transaction to be made in the vending machine. 
Let us define the each state with it's money oriented 
- coin 5 represent the case 1.
- coin 10 represent the case 2.
- coin 20 represent the case 3.
- coin 50 represent the case 4.

Moreover, while purchasing goods, if extra money is inserted the vending machine will return back in 5, 10, 20 ruppee coins as they are readily available with almost everyone.

Now, we will look on each specific case with it's function to be performed.

Firstly, we have an idle state which shows no transaction that means the coins are not inserted yet. So, the change of goods will not happen. However, 
in case 1, the 5 ruppee coin is inserted to purchase five ruppee item, that means no coin will be returned and good is being purchased. Although,
five ruppee coin will be returned back in case 2 when the 10 ruppee coin is inserted and it will also mention that the good is being purchased. Likewise,
in case 3, the 20 ruppee coin is inserted which return back five ruppee coin and ten ruppee coin along with an indication that good is being purchased. Same way,
when 50 ruppee coin is inserted in case 4, five ruppee coin and twenty ruppee coin will be returned back and good is being purchased.

