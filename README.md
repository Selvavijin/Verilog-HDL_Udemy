
# Verilog-HDL_Udemy

![image](https://github.com/user-attachments/assets/472a2577-7a11-4d1c-9e85-b4eb57ba20ac)

![image](https://github.com/user-attachments/assets/d5718b2c-943d-42c5-9b57-bc52955e4f49)

Introduction to VerilogHDL:

Verilog fundamentals:

![image](https://github.com/user-attachments/assets/5112d0db-3e9e-4e9b-bae2-5589675d8c2a)

![image](https://github.com/user-attachments/assets/cc5f9334-73b5-4879-b45a-3f5548cfb3bf)

Testing a circuit in physical level is called testing and testing it in virtual level is called simulation. FPGA has the logical components in it and we can do the arithmetic and logical operations in it also we can do advanced level operations.

![image](https://github.com/user-attachments/assets/5fd395e0-544e-4217-882c-789386fe9aaa)

![image](https://github.com/user-attachments/assets/598bb152-85ea-4234-8c26-c480493bcfb3)

Sensitivity list is present inside the always block as parameters and it is also present in 'C'. ie) when any one of the values inside the always block changes, it get executed. Parallel execution takes place if we use '<=' even if there is 100 lines of code or more. If '=' symbol is used, then step by step execution takes place. We should make it clear that, this parallel execution occurs in the simulation time and not in the processor time or real time or system time. Inside the processor, the statement execute at different times. For example, let us say that a program is simulated for 100ns, that same might get executed for a day in real time in processor. In simulation, we are only functionally verifying.

![image](https://github.com/user-attachments/assets/81b8c239-c47f-4401-84fe-fca2231dcfdb)

Verilog is more popular because it is similar to C language. System tasks are the library files of C. C language can interact with verilog.

![image](https://github.com/user-attachments/assets/b387815d-abdb-4ace-87c8-4f4f28fdedbf)

![image](https://github.com/user-attachments/assets/c3db77b2-5e10-4c45-ba73-8666104f266a)

VLSI Design flow (FPGA & ASIC):

In DFT insertion, we add some extra logic for testing. The below shown is the entire vlsi design flow. We will be focusing on RTL design and functional simulation.

![image](https://github.com/user-attachments/assets/e08ce25a-184d-42a0-a6f2-13d9329ee4a4)

FPGA vs ASIC:

An example is paracetamol tablet. When the tablet is identified first, lets say it is 1 crore rupees. Because they have to find the formula to do the tablet. But afterwards, only making charges is seen. So, the cost reduces drastically to 1 rupee. Similarly in ASIC design, the cost of the first chip will be in crores and for the further chips, the cost will gets reduced. Whenever there is a bulk requirement only we will go for ASIC design. So that the price will get reduced. FPGA is made up of CLBs and each CLBs are made up of some SRAM chips and some MUXs. 

![image](https://github.com/user-attachments/assets/d419da7c-490d-41d2-b8c8-b2d0f018ecdb)

Three levels of verilog design Description:

![image](https://github.com/user-attachments/assets/9938a339-4147-4db2-a31d-30ba1ad649f8)

![image](https://github.com/user-attachments/assets/880446ce-ae35-4365-ac70-fdc2ceb93008)

![image](https://github.com/user-attachments/assets/fdd7dd1f-065b-4da9-9484-de49c8d0289b)

Example: mux_2x1 with 3 abstracts models

![image](https://github.com/user-attachments/assets/a0aa751b-a6e2-4c08-a985-f6bf383e7f5b)

![image](https://github.com/user-attachments/assets/83e50a22-bbb4-4b31-aca2-22e5f4919051)

Language constructs -Comments, keywords, identifier, Number specific, Operators

![image](https://github.com/user-attachments/assets/ca8df82c-c6f0-4960-914c-edb4c26d726d)

Datatypes - net,reg, integer, real, string, time, Parameter, Vector,Array,Memory

![image](https://github.com/user-attachments/assets/49c4e6f5-6e55-420e-8fad-a0d183dfd9a3)

![image](https://github.com/user-attachments/assets/08d6927b-6987-42be-ad54-e2f060b3c0d4)

Compiler Directives

![image](https://github.com/user-attachments/assets/4f580aa3-01ec-42d7-b56b-9151501b79c3)

Verilog Program Structure -Module

![image](https://github.com/user-attachments/assets/cc45b930-49c8-49b8-bc7a-0594ac1a840c)

![image](https://github.com/user-attachments/assets/4faae513-e7d6-4e77-8d41-8cf63deb35f9)

 Ports

 ![image](https://github.com/user-attachments/assets/bef8f79e-395b-422b-bbd1-23dfe01a1a4c)

Port Connection Rules

![image](https://github.com/user-attachments/assets/a437a703-a54f-4ef3-ac94-c9b534b5990e)

Design Methodologies Approaches

![image](https://github.com/user-attachments/assets/a8623df2-f9d4-4cf1-bb13-cebda4cd966e)

Here the example is shown as constructing the module C first and then constructing the modules A and B which is the top level approach. If we design the modules A and B first and then design the module C, then it is the bottom up approach.

![image](https://github.com/user-attachments/assets/052d825f-5155-4ec3-bb7b-a89b56470097)

Gate Level Model Introduction

![image](https://github.com/user-attachments/assets/f2e23f1e-d7cc-4adb-8436-e7f2ccacaf8d)

![image](https://github.com/user-attachments/assets/f7db66df-d7cf-4773-8f28-786c9e8b8f03)

Example: 4x1 Mux

![image](https://github.com/user-attachments/assets/740668dc-8656-46be-8b03-da95c8f1c16b)

Example: Full Adder

![image](https://github.com/user-attachments/assets/07dabbe0-c1a0-4fad-9d6b-7a3741267f26)

Tri-state Buffers with Examples

![image](https://github.com/user-attachments/assets/62a6d518-9b92-4903-b641-3fd0167727eb)

Array of Instance with example

![image](https://github.com/user-attachments/assets/5633b6ef-1b1c-4d17-888e-ef54e9815b5b)

Data flow Modeling : assign statement

![image](https://github.com/user-attachments/assets/237602c9-b822-4df2-b02e-21df887c463d)

The two main things for the data flow modeling are, operators and "assign" which is the continuous assignment statement. 
NOTE: In data flow modeling, all the inputs and outputs should be declared as wire. Because these are continuous assignment statement and so, no storage is required. 'reg' is used, when we need to hold a data.

![image](https://github.com/user-attachments/assets/59ee1809-2ec0-4155-a6f8-8b800f74faec)

Operators

Here, '&&' is logical AND. '=' is for assign. '==' is for equal. '{ }' is the concatenation operator.

![image](https://github.com/user-attachments/assets/154f17c8-efc1-4c70-85bd-d73845b36743)

Arithmetic Operators

![image](https://github.com/user-attachments/assets/2cd3a608-7404-4634-bbf9-15a9f131562b)

Logical Operators

For arithmetic operations, if we use 4 bits for input, we use 5 bits for the output. Because, there will be a carry. But, in logical operations, if we use 4 bits for input, we use 4 bits for output.

![image](https://github.com/user-attachments/assets/07cd1fd3-60ec-4b35-8519-3ae4df55826a)

Example : Full Adder: Logical operators

![image](https://github.com/user-attachments/assets/15e7d071-2a64-4876-8d1a-25a0f85c48a0)

Example : Full Adder: Arithmetic operators

![image](https://github.com/user-attachments/assets/92e2c0bc-f264-48ea-a8a2-418b07e96e79)

Example: Binary to Gray code converter

![image](https://github.com/user-attachments/assets/db09d4bc-64fe-4ee9-b69c-b397e027670e)

Logical and , Logical or (&&, ||)

The output of logical AND and logical OR will be one bit value.

![image](https://github.com/user-attachments/assets/8ae9a0ec-e564-42c1-ad01-97f8b7a7c7e7)

Shift operators : Left/right Shift

![image](https://github.com/user-attachments/assets/bbf0ac47-73f1-4d6d-a630-591b5c5ff401)

Shifting without shift operator , just with concatenation operator

![image](https://github.com/user-attachments/assets/8732aca5-b629-4d68-9dea-a890f4fa1995)

Ternary operator : Example : 2x1 MUX, 4x1 MUX

![image](https://github.com/user-attachments/assets/e8b8b822-ffc8-4793-b7de-bc44da500028)

Relational operators Example: Comparator

![image](https://github.com/user-attachments/assets/17fff4d4-485c-4935-8afc-2e0cd4abb40b)

Equality (==) , case Equality (===) operators

![image](https://github.com/user-attachments/assets/3c87ffaf-c526-4291-a19f-1b4610b21064)

Reduction operator : Example: Parity Generator

![image](https://github.com/user-attachments/assets/49539e11-2a7f-472b-9620-0c26a985f078)

Behavioral Modeling - Introduction

If we know the functionality of the design, we can write the behavioral code. Almost 90% of people use behavioral code. And some people use data flow model. And gate level model is rarely used. Since we can use the 'C' language constructs(if else, case, for, while) in the behavioral modeling, we use it the most. All those constructs should be written inside the procedural blocks. In combinational logic, people use blocking statements and in sequential logic, people use non-blocking statements.

![image](https://github.com/user-attachments/assets/606ecb18-c9aa-4c31-a0bb-fd21d18b2261)

Behavioral Modeling Constructs

![image](https://github.com/user-attachments/assets/3d395375-6f74-446a-b89a-a06e9c210df3)

Procedural Blocks- initial & always

For hardware models, the processing is continuous so we will use the always block which is synthesisable. Similarly the initial block is used for initialization, where 'integer' like that initialization is not allowed in hardware. And this 'initial' block is used in testbench But, nowadays people are using this in design also. But this 'initial' block is never  synthesizable to hardware. These procedural blocks executes parallely which is called concurrency.

![image](https://github.com/user-attachments/assets/a51d1070-3012-4579-b804-72a64dd396db)

Example: Clock Generation

![image](https://github.com/user-attachments/assets/b9d5be0e-2e4e-4c2f-8f05-0441fbbe616f)

Assignment Statements - Blocking & Non-blocking

![image](https://github.com/user-attachments/assets/b58d2888-0042-4372-8651-5721342766f8)

![image](https://github.com/user-attachments/assets/b28715a6-79b2-4661-bf68-da17aa2b2f97)

Mechanism in Non-blocking

![image](https://github.com/user-attachments/assets/47633a60-2053-494b-b33d-1718ed3a4efb)

Concurrency

![image](https://github.com/user-attachments/assets/7b2cd849-f3c6-40c9-aba2-ccc2fafcc841)

Advantage of Non-blocking assignment: Example: swapping

![image](https://github.com/user-attachments/assets/67407909-d33b-4977-8736-b0b6c16a4052)

