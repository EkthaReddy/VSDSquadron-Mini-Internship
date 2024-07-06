# VSDSquadron-Mini-Internship
An internship on RISC-V and VLSI using VSDSquadron Mini Board provided by Kunal Gosh in VLSI System Design (VSD).

<details>
<summary><h3>Overview of the internship</h3></summary>


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
</details>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<details>

<summary><h3>Task 1: </h3> Installation of RISC-V toolchain using VDI. Uploading the snapshot of compiled C code and RISC-V Objdmp on the GitHub repo</summary>

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

</details>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<details>

<summary><h3>Task 2: </h3> Write a C program for your project and compile with RISC-V GCC</summary>
 
**Change Dispense Wizard: Engineering a Vending Machine with Advanced Change System**

Task 2 is about writing the c program for the selected project along with compiling and runing with gcc command. But, before that Let us first take a look on Vending Machine and it's functunality.


#### What is Vending Machine?

A vending machine is a large self-service, often box-like device that sells small items like snacks, drinks, or other goods. You put money or a credit card into the machine, choose what you want to buy by pressing a button or touchscreen, and then the machine gives you the item you selected. It’s a convenient way to buy things quickly without needing to go to a store or interact with a cashier.

![image](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/e768dbd5-291a-4e52-841c-b0215eac0530)

This is what a vending machine looks like and we often find them at places like airport, metro stations or amusement parks.

#### Project : Vending Machine Functionality in my project

##### What does it do?

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
five ruppee coin will be returned back in case 2 when the 10 ruppee coin is inserted and it will also mention that the good is sold out. Likewise,
in case 3, the 20 ruppee coin is inserted which return back five ruppee coin and ten ruppee coin along with an indication that item is purchased. Same way,
when 50 ruppee coin is inserted in case 4, five ruppee coin and twenty ruppee coin will be returned back.

##### What is new in this project?

Earlier, most of the vending machine do not give the change when purchased a good and in some cases the items will not be dispenced as the extra money is inserted which makes the machines unable to identify it.

So, in this project of Vending Machine, the change will be return back when purchased by the customer with extra money. The 5, 10 and 20 rupppee coins are used to pay back the customer when inserted the coins. 
This method is beneficial in India, as the foods which is being sold in market are having range of products to purchase from simple five ruppee to more than hundred, and sometimes the store can get a little crowdy to buy just a 20 ruppee edibles. 

Therefore, the change mechanism system is introduced in vending machine for faster transaction. Which works in series of steps.

Firstly, when a customer inserts money into the machine, the coin mechanism validates the coins or notes. Accepted coins are directed to a storage area.
then the machine calculates the total amount inserted and compares it with the cost of the selected item.
If the amount inserted exceeds the item’s cost, the machine calculates the required change.
and at last the machine then dispenses the change using coins stored in its coin dispenser.
As a result, the project introduces the change despense mechanism for faster, reliable and convient purchase without the interaction with store keeper.


#### C code for Vending Machine

We have now understood the functionality of Vending Machine, the next task is to write the C program for the project in VirtualBox Terminal.

The C program of vending machine is given below,

------------------------------------------------------------------------------------------------------------------------------------------
#include <stdio.h>

// Define states

typedef enum { S0, S5, S10, S20, S50 } State;

// Function prototype

void vending_machine(State *state, int coin, int *nw_pa, int *ret5, int *ret10, int *ret20);

// Function to handle state transitions and actions

void vending_machine(State *state, int coin, int *nw_pa, int *ret5, int *ret10, int *ret20) {
    *nw_pa = 0;
    *ret5 = 0;
    *ret10 = 0;
    *ret20 = 0;

    switch (*state) {
        case S0:
            if (coin == 1) *state = S5;
            else if (coin == 2) *state = S10;
            else if (coin == 3) *state = S20;
            else if (coin == 4) *state = S50;
            break;
        case S5:
            *nw_pa = 1;
            if (coin == 2) *ret5 = 1;
            else if (coin == 3) {
                *ret5 = 1;
                *ret10 = 1;
            } else if (coin == 4) {
                *ret5 = 1;
                *ret20 = 1;
            }
            break;
        case S10:
            *nw_pa = 1;
            if (coin == 3) *ret10 = 1;
            break;
        case S20:
            *nw_pa = 1;
            break;
        case S50:
            *nw_pa = 1;
            if (coin == 4) *ret20 = 1;
            break;
        default:
            *state = S0;
            break;
    }
}

int main() {
    State state = S0;
    int coin;
    int nw_pa = 0, ret5 = 0, ret10 = 0, ret20 = 0;

    while (1) {
        printf("Enter coin value (1: 5, 2: 10, 3: 20, 4: 50, 0 to exit): ");
        scanf("%d", &coin);

        if (coin == 0) {
            break;
        }

        vending_machine(&state, coin, &nw_pa, &ret5, &ret10, &ret20);

        printf("State: %d, nw_pa: %d, ret5: %d, ret10: %d, ret20: %d\n", state, nw_pa, ret5, ret10, ret20);
    }

    return 0;
}

-----------------------------------------------------------------------------------------------

**Explanation to code**:

- **State Definition**:
```c
typedef enum {
    S0, S5, S10, S20, S50
} State;
```
- **State Enum**: Defines the possible states of the vending machine using an enumeration. These states correspond to the initial state (`S0`) and states for different coin values (`S5`, `S10`, `S20`, `S50`).

**Vending Machine Function**
```c
void vending_machine(State *state, int coin, int *nw_pa, int *ret5, int *ret10, int *ret20) {
    *nw_pa = 0;
    *ret5 = 0;
    *ret10 = 0;
    *ret20 = 0;

    switch (*state) {
        case S0:
            if (coin == 1) *state = S5;
            else if (coin == 2) *state = S10;
            else if (coin == 3) *state = S20;
            else if (coin == 4) *state = S50;
            break;
        case S5:
            *nw_pa = 1;
            if (coin == 2) *ret5 = 1;
            else if (coin == 3) {
                *ret5 = 1;
                *ret10 = 1;
            } else if (coin == 4) {
                *ret5 = 1;
                *ret20 = 1;
            }
            break;
        case S10:
            *nw_pa = 1;
            if (coin == 3) *ret10 = 1;
            break;
        case S20:
            *nw_pa = 1;
            break;
        case S50:
            *nw_pa = 1;
            if (coin == 4) *ret20 = 1;
            break;
        default:
            *state = S0;
            break;
    }
}
```
- **Function Purpose**: The `vending_machine` function updates the state of the vending machine and sets the output signals (`nw_pa`, `ret5`, `ret10`, `ret20`) based on the current state and coin input.
- **Parameter Explanation**:
  - `state`: Pointer to the current state of the vending machine.
  - `coin`: The value of the inserted coin (1 for 5, 2 for 10, 3 for 20, 4 for 50).
  - `nw_pa`, `ret5`, `ret10`, `ret20`: Pointers to the output signals.
- **State Transitions**:
  - In each case block, the function checks the coin value and updates the state accordingly.
  - Depending on the state, it may also set the output signals to indicate if a product is dispensed (`nw_pa`) or if change is returned (`ret5`, `ret10`, `ret20`).

**Main Function**
```c
int main() {
    State state = S0;
    int coin;
    int nw_pa = 0, ret5 = 0, ret10 = 0, ret20 = 0;

    while (1) {
        printf("Enter coin value (1: 5, 2: 10, 3: 20, 4: 50, 0 to exit): ");
        scanf("%d", &coin);

        if (coin == 0) {
            break;
        }

        vending_machine(&state, coin, &nw_pa, &ret5, &ret10, &ret20);

        printf("State: %d, nw_pa: %d, ret5: %d, ret10: %d, ret20: %d\n", state, nw_pa, ret5, ret10, ret20);
    }

    return 0;
}
```
- **State Initialization**: Initializes the state to `S0` (initial state).

- If the coin value is `0`, the loop breaks, ending the program.


#### Compiling the C code with RISC-V gcc

In the last step of task 2, the code written in leafpad ediotr will be checked for any errors by using the command line (`gcc file_name`). Therefore, for my project I have used (`gcc vending_machine`) and if the code is right, then give command (`ls -ltr`) for compiling the code in RISC-V. 

To check the output of  C code, run the code by using (`./a.out`).


![vending machine result](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/9f5484cd-6c58-4879-894d-c95b99e5b41e)


**Explanation to output**:
The output shows the state transitions and actions of the vending machine based on coin inputs. Each entry updates the state and outputs whether a product is dispensed (`nw_pa = 1`) and if any change is returned (`ret5`, `ret10`, `ret20`). The session ends when `0` is inputted.

</details>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<details>

<summary><h3>Task 3: </h3> Do SPIKE Simulation and verification with -O1 and -Ofast along with running the RISC-V Objdmp. </summary>

In this task, we have to perform Spike Simulation and observe with (`-o1`) and (`-ofast`) command.

#### With `-o1` command :

##### Verification with `-o1`:

At first, we will verify the code for `-o1` , to do that, the output we got from the `gcc` command should be equal to the spike simulation.

This command ` riscv64-unknown-elf-gcc -o1 -mabi=lp64 -march=rv64i -o vending_machine.o vending_machine.c ` will run the C code to give the output in C by using `./a.out` and for RISC-V processor we must use `spike pk vending_machine`

The output got from `gcc` is for state `2` for 10 ruppee coin and the if press `0` it get exited. The same way the output got from `spike` is `2` for state 2 which represent the 10 ruppee coin, and by pressing 0 it terminated for next command line instruction to be performed.



Hence, the verification for command `-o1` is done.


![verification for spike for o1 command](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/8298625e-68ea-4ac4-bf77-c43664ba96ed)

##### Debugging the RISC-V Processor for `-o1` using Spike simulation :

Now we will debugg the assembly code instruction we got from from ` riscv64-unknown-elf-objdump -d vending_machine.o | less `

![assembly code vending machine](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/c0092cc5-6ad2-49b1-b823-5f45e30027d9)

In this, we will debugg by using the instruction `spike -d pk vending_machine` 
which will allow us to spike any instruction we want.

Now, we spike for the initial address we see on the assembly code `100b0` so that we can see starting address to any point manually by using program counter

To do so, `until pc 0 100b0`, this means that it will debugg all the instruction after 100b0 and also shows the previous instructions to `100b0` is already being debugged. 

Type for `reg 0 a2`, it will show the register value at zero core for a2 operand.

To see next instruction, press `Enter` and it will show the starting address and if pressed again it will go to `100b4` which is the next instruction.

`reg 0 sp` shows the stack pointer of the instruction of 100b4

and if we want to see the next instruction(`100b8`) stack pointer just subtract the value we got from `reg 0 sp` of `100b4` from `16` as it is a hexadecimal value. It will give the `100b8` instruction stack pointer.


We can verify it by using `until pc 0 100b8` the program counter poites at instruction `100b8`, before that quit from the previous operation by pressing `q`.

Type `reg 0 sp`

Hence it is verified and debugged now.

![debugging for o1](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/85ba39df-3da9-4029-92d0-16546e5233f8)

![continue o1](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/1abe08ab-89e4-4550-b763-ccba5e638a5a)

![cotinue debugging o1](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/fa44ce12-9549-44ea-bfba-d137c3faaab9)

#### With `-ofast` command :

##### Verification with `-ofast` :
In the same way, now we have to do for `-ofast` command

Step 1: C Code compilation using command ` riscv64-unknown-elf-gcc -ofast -mabi=lp64 -march=rv64i -o vending_machine.o vending_machine.c `.
Check the output by running `gcc file_name` which is `gcc vending_machine.c`
The output can be verified by using `./a.out`

Step 2: RISC-V Processor compilation is by using again ` riscv64-unknown-elf-gcc -ofast -mabi=lp64 -march=rv64i -o vending_machine.o vending_machine.c `.
Check and verified the output by `spike pk vending_machine.o`.

- Note: If the ouput from Step 1 and Step 2 is matched, then the verification with `-ofast` is over.

![spike command for verification](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/a3b66d97-c636-4926-9313-69b3a14bd17e)


Step 3: Now, we have to run the compiled C code for RISC-V processor.

By using the command ` riscv64-unknown-elf-objdump -d vending_machine.o | less `, it will give the assembly code instruction.

##### Debugging the RISC-V Processor for `-ofast` using Spike simulation :

The starting address of the assembly code is `100b0`, with help of program counter, we can see the next instruction manually by performing debugging.

![assembly code vending machine](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/c0092cc5-6ad2-49b1-b823-5f45e30027d9)

Step 4: We have to debugg the RISC-V Processor by using command `spike -d pk vending_machine.o`.

Step 5: Use `until pc0 100b0` , it says that it will debugg all the instructions after 100b0 and the previous instructions are already debugged.

Step 6: To see the next instruction.

- `reg 0 a2` it will define the register value at zero core for a2 operand.
- Hit `Enter` to get the first instruction, after that give command ` reg 0 a0` followed by ` reg 0 sp`.
- Quit the operation by giving `q`
- To check the next instruction, give `until pc 0 100b8` for debugging the instruction `100b8` and type `reg 0 sp` for getting the stack pointer value.

Step 7: To check the next instruction manually, calculate by subtracting the stack pointer value with `16` to see the next instruction sp.

![debugging the spike](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/8d29cefb-2686-4810-8b35-0604461f78f4)

![continue debugging](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/0a021676-be5a-4687-892d-125475f01ee2)

![knowing the difference by using  stack pointer](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/02085887-fdb8-4419-8ed1-028aeb3b8569)


**Objective of Task 3:** 

The task 2 was to perform the spike simulation for,

- Verifying the C code and RISC-V Processor compilation.
- Debugg the RISC-V Processor using the spike simulation.

</details>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<details>

<summary><h3>Task 4 : </h3> RISC-V Instruction Formats and 32-bit Patterns</summary>


Reffered ChatGPT in the task 4 as an extra resource.

#### Introduction to RISC-V
RISC-V is an open-source instruction set architecture (ISA) based on reduced instruction set computer (RISC) principles. It allows for the development of processors without requiring a license, making it a popular choice for custom and academic use. RISC-V instructions are organized into several formats, each suited for different types of operations.



#### RISC-V Instruction Formats
RISC-V uses six main instruction formats: R, I, S, B, U, and J. Each format has a specific structure that dictates how the bits in a 32-bit instruction are organized. Here's a breakdown of each format and their subtypes:

![image](https://github.com/EkthaReddy/VSDSquadron-Mini-Internship/assets/152515939/42c543e4-4d14-4ca0-a862-657c24ef5b6b)



1. **R-type (Register) Instructions**
    - **Description**: R-type instructions are used for arithmetic and logical operations where both operands and the result are in registers.
    - **Structure**:
        - **func7**: 7 bits (function code)
        - **rs2**: 5 bits (second source register)
        - **rs1**: 5 bits (first source register)
        - **func3**: 3 bits (function code)
        - **rd**: 5 bits (destination register)
        - **opcode**: 7 bits (operation code)
    - **Subtypes and Examples**:
        - **Arithmetic Operations**: ADD, SUB
        - **Logical Operations**: AND, OR, XOR
        - **Shift Operations**: SLL, SRL

---

2. **I-type (Immediate) Instructions**
    - **Description**: I-type instructions are used for operations that involve an immediate value (constant) and a register. They are also used for load operations.
    - **Structure**:
        - **imm[11:0]**: 12 bits (immediate value)
        - **rs1**: 5 bits (source register)
        - **func3**: 3 bits (function code)
        - **rd**: 5 bits (destination register)
        - **opcode**: 7 bits (operation code)
    - **Subtypes and Examples**:
        - **Arithmetic Operations with Immediate**: ADDI
        - **Load Operations**: LW

---

3. **S-type (Store) Instructions**
    - **Description**: S-type instructions are used for store operations, where data from a register is stored into memory.
    - **Structure**:
        - **imm[11:5]**: 7 bits (immediate value)
        - **rs2**: 5 bits (source register 2)
        - **rs1**: 5 bits (source register 1)
        - **func3**: 3 bits (function code)
        - **imm[4:0]**: 5 bits (immediate value)
        - **opcode**: 7 bits (operation code)
    - **Subtypes and Examples**:
        - **Store Operations**: SW

---

4. **B-type (Branch) Instructions**
    - **Description**: B-type instructions are used for conditional branch operations, where the execution flow changes based on a condition.
    - **Structure**:
        - **imm[12]**: 1 bit (immediate value)
        - **imm[10:5]**: 6 bits (immediate value)
        - **rs2**: 5 bits (second source register)
        - **rs1**: 5 bits (first source register)
        - **func3**: 3 bits (function code)
        - **imm[4:1]**: 4 bits (immediate value)
        - **imm[11]**: 1 bit (immediate value)
        - **opcode**: 7 bits (operation code)
    - **Subtypes and Examples**:
        - **Branch Operations**: BEQ, BNE

---

5. **U-type (Upper Immediate) Instructions**
    - **Description**: U-type instructions are used for operations involving large immediate values that need to be loaded into the upper 20 bits of a register.
    - **Structure**:
        - **imm[31:12]**: 20 bits (immediate value)
        - **rd**: 5 bits (destination register)
        - **opcode**: 7 bits (operation code)
    - **Subtypes and Examples**:
        - **Upper Immediate Operations**: LUI, AUIPC

---

6. **J-type (Jump) Instructions**
    - **Description**: J-type instructions are used for jump operations, where the execution flow is changed to a specified address.
    - **Structure**:
        - **imm[20]**: 1 bit (immediate value)
        - **imm[10:1]**: 10 bits (immediate value)
        - **imm[11]**: 1 bit (immediate value)
        - **imm[19:12]**: 8 bits (immediate value)
        - **rd**: 5 bits (destination register)
        - **opcode**: 7 bits (operation code)
    - **Subtypes and Examples**:
        - **Jump Operations**: JAL, JALR

---

#### Instructions and Their Formats

1. **ADD r1, r2, r3**
   - **Type**: R
   - **Operation**: Performs the addition of the contents of registers r2 and r3 and stores the result in register r1.
   - **Format**:
     ```
     func7   rs2    rs1    func3  rd     opcode
     0000000 00011  00010  000    00001  0110011
     ```
   - **32-bit Instruction**: `0000000_00011_00010_000_00001_0110011`

     **Explanation**: 
     - **func7**: 7-bit function code. For ADD, it is `0000000`.
     - **rs2**: 5-bit source register 2. Here it is r3 (register 3) represented as `00011`.
     - **rs1**: 5-bit source register 1. Here it is r2 (register 2) represented as `00010`.
     - **func3**: 3-bit function code. For ADD, it is `000`.
     - **rd**: 5-bit destination register. Here it is r1 (register 1) represented as `00001`.
     - **opcode**: 7-bit opcode for the R-type format. For arithmetic operations, it is `0110011`.

2. **SUB r3, r1, r2**
   - **Type**: R
   - **Operation**: Subtracts the contents of register r2 from register r1 and stores the result in register r3.
   - **Format**:
     ```
     func7   rs2    rs1    func3  rd     opcode
     0100000 00010  00001  000    00011  0110011
     ```
   - **32-bit Instruction**: `0100000_00010_00001_000_00011_0110011`

     **Explanation**: 
     - **func7**: 7-bit function code. For SUB, it is `0100000`.
     - **rs2**: 5-bit source register 2. Here it is r2 (register 2) represented as `00010`.
     - **rs1**: 5-bit source register 1. Here it is r1 (register 1) represented as `00001`.
     - **func3**: 3-bit function code. For SUB, it is `000`.
     - **rd**: 5-bit destination register. Here it is r3 (register 3) represented as `00011`.
     - **opcode**: 7-bit opcode for the R-type format. For arithmetic operations, it is `0110011`.

3. **AND r2, r1, r3**
   - **Type**: R
   - **Operation**: Performs a bitwise AND between the contents of registers r1 and r3, and stores the result in register r2.
   - **Format**:
     ```
     func7   rs2    rs1    func3  rd     opcode
     0000000 00011  00001  111    00010  0110011
     ```
   - **32-bit Instruction**: `0000000_00011_00001_111_00010_0110011`

     **Explanation**: 
     - **func7**: 7-bit function code. For AND, it is `0000000`.
     - **rs2**: 5-bit source register 2. Here it is r3 (register 3) represented as `00011`.
     - **rs1**: 5-bit source register 1. Here it is r1 (register 1) represented as `00001`.
     - **func3**: 3-bit function code. For AND, it is `111`.
     - **rd**: 5-bit destination register. Here it is r2 (register 2) represented as `00010`.
     - **opcode**: 7-bit opcode for the R-type format. For logical operations, it is `0110011`.

4. **OR r8, r2, r5**
   - **Type**: R
   - **Operation**: Performs a bitwise OR between the contents of registers r2 and r5, and stores the result in register r8.
   - **Format**:
     ```
     func7   rs2    rs1    func3  rd     opcode
     0000000 00101  00010  110    01000  0110011
     ```
   - **32-bit Instruction**: `0000000_00101_00010_110_01000_0110011`

     **Explanation**: 
     - **func7**: 7-bit function code. For OR, it is `0000000`.
     - **rs2**: 5-bit source register 2. Here it is r5 (register 5) represented as `00101`.
     - **rs1**: 5-bit source register 1. Here it is r2 (register 2) represented as `00010`.
     - **func3**: 3-bit function code. For OR, it is `110`.
     - **rd**: 5-bit destination register. Here it is r8 (register 8) represented as `01000`.
     - **opcode**: 7-bit opcode for the R-type format. For logical operations, it is `0110011`.

5. **XOR r8, r1, r4**
   - **Type**: R
   - **Operation**: Performs a bitwise XOR between the contents of registers r1 and r4, and stores the result in register r8.
   - **Format**:
     ```
     func7   rs2    rs1    func3  rd     opcode
     0000000 00100  00001  100    01000  0110011
     ```
   - **32-bit Instruction**: `0000000_00100_00001_100_01000_0110011`

     **Explanation**: 
     - **func7**: 7-bit function code. For XOR, it is `0000000`.
     - **rs2**: 5-bit source register 2. Here it is r4 (register 4) represented as `00100`.
     - **rs1**: 5-bit source register 1. Here it is r1 (register 1) represented as `00001`.
     - **func3**: 3-bit function code. For XOR, it is `100`.
     - **rd**: 5-bit destination register. Here it is r8 (register 8) represented as `01000`.
     - **opcode**: 7-bit opcode for the R-type format. For logical operations, it is `0110011`.

6. **SLT r10, r2, r4**
   - **Type**: R
   - **Operation**: Sets register r10 to 1 if the contents of register r2 are less than the contents of register r4, otherwise sets it to 0.
   - **Format**:
     ```
     func7   rs2    rs1    func3  rd     opcode
     0000000 00100  00010  010    01010  0110011
     ```
   - **32-bit Instruction**: `0000000_00100_00010_010_01010_0110011`

     **Explanation**: 
     - **func7**: 7-bit function code. For SLT, it is `0000000`.
     - **rs2**: 5-bit source register 2. Here it is r4 (register 4) represented as `00100`.
     - **rs1**: 5-bit

 source register 1. Here it is r2 (register 2) represented as `00010`.
     - **func3**: 3-bit function code. For SLT, it is `010`.
     - **rd**: 5-bit destination register. Here it is r10 (register 10) represented as `01010`.
     - **opcode**: 7-bit opcode for the R-type format. For comparison operations, it is `0110011`.

7. **ADDI r12, r3, 5**
   - **Type**: I
   - **Operation**: Adds the immediate value 5 to the contents of register r3 and stores the result in register r12.
   - **Format**:
     ```
     imm[11:0]   rs1    func3  rd     opcode
     000000000101 00011  000    01100  0010011
     ```
   - **32-bit Instruction**: `000000000101_00011_000_01100_0010011`

     **Explanation**: 
     - **imm[11:0]**: 12-bit immediate value. Here it is `000000000101` representing the value 5.
     - **rs1**: 5-bit source register. Here it is r3 (register 3) represented as `00011`.
     - **func3**: 3-bit function code. For ADDI, it is `000`.
     - **rd**: 5-bit destination register. Here it is r12 (register 12) represented as `01100`.
     - **opcode**: 7-bit opcode for the I-type format. For arithmetic operations with immediate, it is `0010011`.

8. **SW r3, r1, 4**
   - **Type**: S
   - **Operation**: Stores the contents of register r3 into memory at the address calculated by adding 4 to the contents of register r1.
   - **Format**:
     ```
     imm[11:5]  rs2   rs1    func3  imm[4:0] opcode
     0000000    00011 00001  010    00100    0100011
     ```
   - **32-bit Instruction**: `0000000_00011_00001_010_00100_0100011`

     **Explanation**: 
     - **imm[11:5]**: 7-bit immediate value (upper 7 bits). Here it is `0000000`.
     - **rs2**: 5-bit source register 2. Here it is r3 (register 3) represented as `00011`.
     - **rs1**: 5-bit source register 1. Here it is r1 (register 1) represented as `00001`.
     - **func3**: 3-bit function code. For SW, it is `010`.
     - **imm[4:0]**: 5-bit immediate value (lower 5 bits). Here it is `00100` representing the value 4.
     - **opcode**: 7-bit opcode for the S-type format. For store operations, it is `0100011`.

9. **SRL r16, r11, r2**
   - **Type**: R
   - **Operation**: Performs a logical right shift on the contents of register r11 by the number of bits specified in register r2, and stores the result in register r16.
   - **Format**:
     ```
     func7   rs2    rs1    func3  rd     opcode
     0000000 00010  01011  101    10000  0110011
     ```
   - **32-bit Instruction**: `0000000_00010_01011_101_10000_0110011`

     **Explanation**: 
     - **func7**: 7-bit function code. For SRL, it is `0000000`.
     - **rs2**: 5-bit source register 2. Here it is r2 (register 2) represented as `00010`.
     - **rs1**: 5-bit source register 1. Here it is r11 (register 11) represented as `01011`.
     - **func3**: 3-bit function code. For SRL, it is `101`.
     - **rd**: 5-bit destination register. Here it is r16 (register 16) represented as `10000`.
     - **opcode**: 7-bit opcode for the R-type format. For shift operations, it is `0110011`.

10. **BNE r0, r1, 20**
    - **Type**: B
    - **Operation**: Branches to the address offset by 20 if the contents of registers r0 and r1 are not equal.
    - **Format**:
      ```
      imm[12] imm[10:5]  rs2   rs1    func3  imm[4:1] imm[11] opcode
      0       000001     00001 00000  001    0100     0       1100011
      ```
    - **32-bit Instruction**: `0_000001_00001_00000_001_0100_0_1100011`

      **Explanation**: 
      - **imm[12]**: 1-bit immediate value (bit 12). Here it is `0`.
      - **imm[10:5]**: 6-bit immediate value (bits 10 to 5). Here it is `000001`.
      - **rs2**: 5-bit source register 2. Here it is r1 (register 1) represented as `00001`.
      - **rs1**: 5-bit source register 1. Here it is r0 (register 0) represented as `00000`.
      - **func3**: 3-bit function code. For BNE, it is `001`.
      - **imm[4:1]**: 4-bit immediate value (bits 4 to 1). Here it is `0100`.
      - **imm[11]**: 1-bit immediate value (bit 11). Here it is `0`.
      - **opcode**: 7-bit opcode for the B-type format. For branch operations, it is `1100011`.

11. **BEQ r0, r0, 15**
    - **Type**: B
    - **Operation**: Branches to the address offset by 15 if the contents of registers r0 and r0 are equal.
    - **Format**:
      ```
      imm[12] imm[10:5]  rs2   rs1    func3  imm[4:1] imm[11] opcode
      0       000000     00000 00000  000    1111     0       1100011
      ```
    - **32-bit Instruction**: `0_000000_00000_00000_000_1111_0_1100011`

      **Explanation**: 
      - **imm[12]**: 1-bit immediate value (bit 12). Here it is `0`.
      - **imm[10:5]**: 6-bit immediate value (bits 10 to 5). Here it is `000000`.
      - **rs2**: 5-bit source register 2. Here it is r0 (register 0) represented as `00000`.
      - **rs1**: 5-bit source register 1. Here it is r0 (register 0) represented as `00000`.
      - **func3**: 3-bit function code. For BEQ, it is `000`.
      - **imm[4:1]**: 4-bit immediate value (bits 4 to 1). Here it is `1111`.
      - **imm[11]**: 1-bit immediate value (bit 11). Here it is `0`.
      - **opcode**: 7-bit opcode for the B-type format. For branch operations, it is `1100011`.

12. **LW r13, r11, 2**
    - **Type**: I
    - **Operation**: Loads the word from memory at the address calculated by adding 2 to the contents of register r11 into register r13.
    - **Format**:
      ```
      imm[11:0]   rs1    func3  rd     opcode
      000000000010 01011  010    01101  0000011
      ```
    - **32-bit Instruction**: `000000000010_01011_010_01101_0000011`

      **Explanation**: 
      - **imm[11:0]**: 12-bit immediate value. Here it is `000000000010` representing the value 2.
      - **rs1**: 5-bit source register. Here it is r11 (register 11) represented as `01011`.
      - **func3**: 3-bit function code. For LW, it is `010`.
      - **rd**: 5-bit destination register. Here it is r13 (register 13) represented as `01101`.
      - **opcode**: 7-bit opcode for the I-type format. For load operations, it is `0000011`.

13. **SLL r15, r11, r1**
    - **Type**: R
    - **Operation**: Performs a logical left shift on the contents of register r11 by the number of bits specified in register r1, and stores the result in register r15.
    - **Format**:
      ```
      func7   rs2    rs1    func3  rd     opcode
      0000000 00001  01011  001    01111  0110011
      ```
    - **32-bit Instruction**: `0000000_00001_01011_001_01111_0110011`

      **Explanation**: 
      - **func7**: 7-bit function code. For SLL, it is `0000000`.
      - **rs2**: 5-bit source register 2. Here it is r1 (register 1) represented as `00001`.
      - **rs1**: 5-bit source register 1. Here it is r11 (register 11) represented as `01011`.
      - **func3**: 3-bit function code. For SLL, it is `001`.
      - **rd**: 5-bit destination register. Here it is r15 (register 15) represented as `01111`.
      - **opcode**: 7-bit opcode for the R-type format. For shift operations, it is `0110011`.


**Summary :**

These instructions and their corresponding formats provide a clear representation of how RISC-V organizes its operations. The exact 32-bit codes ensure that each instruction is properly encoded for execution in a RISC-V processor. 

</details>


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------




module iiitb_rv32i(clk,RN,NPC,WB_OUT);
input clk;
input RN;
//input EN;
integer k;
wire  EX_MEM_COND ;

reg 
BR_EN;

//I_FETCH STAGE
reg[31:0] 
IF_ID_IR,
IF_ID_NPC;                                

//I_DECODE STAGE
reg[31:0] 
ID_EX_A,
ID_EX_B,
ID_EX_RD,
ID_EX_IMMEDIATE,
ID_EX_IR,ID_EX_NPC;      

//EXECUTION STAGE
reg[31:0] 
EX_MEM_ALUOUT,
EX_MEM_B,EX_MEM_IR;                        

parameter 
ADD=3'd0,
SUB=3'd1,
AND=3'd2,
OR=3'd3,
XOR=3'd4,
SLT=3'd5,

ADDI=3'd0,
SUBI=3'd1,
ANDI=3'd2,
ORI=3'd3,
XORI=3'd4,

LW=3'd0,
SW=3'd1,

BEQ=3'd0,
BNE=3'd1,

SLL=3'd0,
SRL=3'd1;


parameter 
AR_TYPE=7'd0,
M_TYPE=7'd1,
BR_TYPE=7'd2,
SH_TYPE=7'd3;


//MEMORY STAGE
reg[31:0] 
MEM_WB_IR,
MEM_WB_ALUOUT,
MEM_WB_LDM;                      


output reg [31:0]WB_OUT,NPC;

//REG FILE
reg [31:0]REG[0:31];                                               
//64*32 IMEM
reg [31:0]MEM[0:31];                                             
//64*32 DMEM
reg [31:0]DM[0:31];   


//assign EX_MEM_COND = (EX_MEM_IR[6:0]==BR_TYPE) ? 1'b1 : 1'b0;
                     //1'b1 ? (ID_EX_A!=ID_EX_RD) : 1'b0;

always @(posedge clk or posedge RN) begin
    if(RN) begin
    NPC<= 32'd0;
    //EX_MEM_COND <=1'd0;
    BR_EN<= 1'd0; 
    REG[0] <= 32'h00000000;
    REG[1] <= 32'd1;
    REG[2] <= 32'd2;
    REG[3] <= 32'd3;
    REG[4] <= 32'd4;
    REG[5] <= 32'd5;
    REG[6] <= 32'd6;
    end
    //else if(EX_MEM_COND)
    //NPC <= EX_MEM_ALUOUT;

    //else if (EX_MEM_COND)begin
    //NPC = EX_MEM_COND ? EX_MEM_ALUOUT : NPC +32'd1;
    //NPC <= EX_MEM_ALUOUT;
    //EX_MEM_COND = BR_EN;
    //NPC = BR_EN ? EX_MEM_ALUOUT : NPC +32'd1;
    //BR_EN = 1'd0;
    //EX_MEM_COND <= 1'd0;
    //end
    else begin
    NPC <= BR_EN ? EX_MEM_ALUOUT : NPC +32'd1;
    BR_EN <= 1'd0;
    //NPC <= NPC +32'd1;
    //EX_MEM_COND <=1'd0;
    IF_ID_IR <=MEM[NPC];
    IF_ID_NPC <=NPC+32'd1;
    end
end

always @(posedge RN) begin
    //NPC<= 32'd0;
MEM[0] <= 32'h02208300;         // add r6,r1,r2.(i1)
MEM[1] <= 32'h02209380;         //sub r7,r1,r2.(i2)
MEM[2] <= 32'h0230a400;         //and r8,r1,r3.(i3)
MEM[3] <= 32'h02513480;         //or r9,r2,r5.(i4)
MEM[4] <= 32'h0240c500;         //xor r10,r1,r4.(i5)
MEM[5] <= 32'h02415580;         //slt r11,r2,r4.(i6)
MEM[6] <= 32'h00520600;         //addi r12,r4,5.(i7)
MEM[7] <= 32'h00209181;         //sw r3,r1,2.(i8)
MEM[8] <= 32'h00208681;         //lw r13,r1,2.(i9)
MEM[9] <= 32'h00f00002;         //beq r0,r0,15.(i10)
MEM[25] <= 32'h00210700;         //add r14,r2,r2.(i11)
//MEM[27] <= 32'h01409002;         //bne r0,r1,20.(i12)
//MEM[49] <= 32'h00520601;         //addi r12,r4,5.(i13)
//MEM[50] <= 32'h00208783;         //sll r15,r1,r2(2).(i14)
//MEM[51] <= 32'h00271803;         //srl r16,r14,r2(2).(i15) */

//for(k=0;k<=31;k++)
//REG[k]<=k;
/*REG[0] <= 32'h00000000;
REG[1] <= 32'd1;
REG[2] <= 32'd2;
REG[3] <= 32'd3;
REG[4] <= 32'd4;
REG[5] <= 32'd5;
REG[6] <= 32'd6;
REG[7] = 32'd7;
REG[6] = 32'd6;
REG[7] = 32'd7;
REG[8] = 32'd8;
REG[9] = 32'd9;
REG[10] = 32'd10;
REG[11] = 32'd11;
REG[12] = 32'd12;
REG[13] = 32'd13;
REG[14] = 32'd14;
REG[15] = 32'd15;
REG[16] = 32'd16;
REG[17] = 32'd17;*/
/*end
else begin
    if(EX_MEM_COND==1 && EX_MEM_IR[6:0]==BR_TYPE) begin
    NPC=EX_MEM_ALUOUT;
    IF_ID=MEM[NPC];
    end

    else begin
    NPC<=NPC+32'd1;
    IF_ID<=MEM[NPC];
    IF_ID_NPC<=NPC+32'd1;
    end
end*/
end
//I_FECT STAGE

/*always @(posedge clk) begin

//NPC <= rst ? 32'd0 : NPC+32'd1;

if(EX_MEM_COND==1 && EX_MEM_IR[6:0]==BR_TYPE) begin
NPC=EX_MEM_ALUOUT;
IF_ID=MEM[NPC];
end

else begin
NPC<=NPC+32'd1;
IF_ID<=MEM[NPC];
IF_ID_NPC<=NPC+32'd1;
end
end*/


//FETCH STAGE END

//I_DECODE STAGE 
always @(posedge clk) begin

ID_EX_A <= REG[IF_ID_IR[19:15]];
ID_EX_B <= REG[IF_ID_IR[24:20]];
ID_EX_RD <= REG[IF_ID_IR[11:7]];
ID_EX_IR <= IF_ID_IR;
ID_EX_IMMEDIATE <= {{20{IF_ID_IR[31]}},IF_ID_IR[31:20]};
ID_EX_NPC<=IF_ID_NPC;
end
//DECODE STAGE END

/*always@(posedge clk) begin
if(ID_EX_IR[6:0]== BR_TYPE)
EX_MEM_COND <= EN;
else
EX_MEM_COND <= !EN;
end*/


//EXECUTION STAGE

always@(posedge clk) begin

EX_MEM_IR <=  ID_EX_IR;
//EX_MEM_COND <= (ID_EX_IR[6:0] == BR_TYPE) ? 1'd1 :1'd0;


case(ID_EX_IR[6:0])

AR_TYPE:begin
    if(ID_EX_IR[31:25]== 7'd1)begin
    case(ID_EX_IR[14:12])

    ADD:EX_MEM_ALUOUT <= ID_EX_A + ID_EX_B;
    SUB:EX_MEM_ALUOUT <= ID_EX_A - ID_EX_B;
    AND:EX_MEM_ALUOUT <= ID_EX_A & ID_EX_B;
    OR :EX_MEM_ALUOUT <= ID_EX_A | ID_EX_B;
    XOR:EX_MEM_ALUOUT <= ID_EX_A ^ ID_EX_B;
    SLT:EX_MEM_ALUOUT <= (ID_EX_A < ID_EX_B) ? 32'd1 : 32'd0;

    endcase
    end
    else begin
        case(ID_EX_IR[14:12])
        ADDI:EX_MEM_ALUOUT <= ID_EX_A + ID_EX_IMMEDIATE;
        SUBI:EX_MEM_ALUOUT <= ID_EX_A - ID_EX_IMMEDIATE;
        ANDI:EX_MEM_ALUOUT <= ID_EX_A & ID_EX_B;
        ORI:EX_MEM_ALUOUT  <= ID_EX_A | ID_EX_B;
        XORI:EX_MEM_ALUOUT <= ID_EX_A ^ ID_EX_B;
        endcase
    end

end

M_TYPE:begin
    case(ID_EX_IR[14:12])
    LW  :EX_MEM_ALUOUT <= ID_EX_A + ID_EX_IMMEDIATE;
    SW  :EX_MEM_ALUOUT <= ID_EX_IR[24:20] + ID_EX_IR[19:15];
    endcase
end

BR_TYPE:begin
    case(ID_EX_IR[14:12])
    BEQ:begin 
    EX_MEM_ALUOUT <= ID_EX_NPC+ID_EX_IMMEDIATE;
    BR_EN <= 1'd1 ? (ID_EX_IR[19:15] == ID_EX_IR[11:7]) : 1'd0;
    //BR_PC = EX_MEM_COND ? EX_MEM_ALUOUT : 1'd0; 
end
BNE:begin 
    EX_MEM_ALUOUT <= ID_EX_NPC+ID_EX_IMMEDIATE;
    BR_EN <= (ID_EX_IR[19:15] != ID_EX_IR[11:7]) ? 1'd1 : 1'd0;
end
endcase
end

SH_TYPE:begin
case(ID_EX_IR[14:12])
SLL:EX_MEM_ALUOUT <= ID_EX_A << ID_EX_B;
SRL:EX_MEM_ALUOUT <= ID_EX_A >> ID_EX_B;
endcase
end

endcase
end


//EXECUTION STAGE END
		
//MEMORY STAGE
always@(posedge clk) begin

MEM_WB_IR <= EX_MEM_IR;

case(EX_MEM_IR[6:0])

AR_TYPE:MEM_WB_ALUOUT <=  EX_MEM_ALUOUT;
SH_TYPE:MEM_WB_ALUOUT <=  EX_MEM_ALUOUT;

M_TYPE:begin
case(EX_MEM_IR[14:12])
LW:MEM_WB_LDM <= DM[EX_MEM_ALUOUT];
SW:DM[EX_MEM_ALUOUT]<=REG[EX_MEM_IR[11:7]];
endcase
end

endcase
end

// MEMORY STAGE END


//WRITE BACK STAGE
always@(posedge clk) begin

case(MEM_WB_IR[6:0])

AR_TYPE:begin 
WB_OUT<=MEM_WB_ALUOUT;
REG[MEM_WB_IR[11:7]]<=MEM_WB_ALUOUT;
end

SH_TYPE:begin
WB_OUT<=MEM_WB_ALUOUT;
REG[MEM_WB_IR[11:7]]<=MEM_WB_ALUOUT;
end

M_TYPE:begin
case(MEM_WB_IR[14:12])
LW:begin
WB_OUT<=MEM_WB_LDM;
REG[MEM_WB_IR[11:7]]<=MEM_WB_LDM;
end
endcase
end



endcase
end
//WRITE BACK STAGE END

endmodule









---











module iiitb_rv32i_tb;

reg clk,RN;
wire [31:0]WB_OUT,NPC;

iiitb_rv32i rv32(clk,RN,NPC,WB_OUT);


always #3 clk=!clk;

initial begin 
RN  = 1'b1;
clk = 1'b1;

$dumpfile ("iiitb_rv32i.vcd"); //by default vcd
$dumpvars (0, iiitb_rv32i_tb);
  
  #5 RN = 1'b0;
  
  #300 $finish;

end
endmodule
