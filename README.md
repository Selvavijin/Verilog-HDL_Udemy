
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

Advantage of Non-blocking assignment: Example : Pipelining

Explanation of graph of non-blocking assignment statement: For the first rising edge of clk, Q1 is high, but there will be some delay. Due to this, Q2 will not be able to high and it will be high at the next clock edge.

![image](https://github.com/user-attachments/assets/5e93343a-15c4-4756-be99-3c1d51fe7609)

If-else: statement: Example : 4x1 Mux

Inside the if or else statement, if more than one statements are present, then it is compulsory to use the begin and end statements. Otherwise it is optional. If-else is also considered as a single statement, so if we use single if-else statement inside the always block, it is optional to use the begin and end statement.

![image](https://github.com/user-attachments/assets/ebd81a14-4857-441c-a599-be953fe70067)

Case – statement : Example : 4x1 Mux

![image](https://github.com/user-attachments/assets/0659e52e-78d0-41d0-a0ad-9314cab387df)

Advantage of Case over if-else

Case statement is better than if-else statements.

![image](https://github.com/user-attachments/assets/929c5aaf-d59f-45f7-96c8-98b77eea2b07)

Loops: while, for, repeat, forever

![image](https://github.com/user-attachments/assets/03b146ec-98d2-4577-8cd6-170a3c817cde)

Parallel blocks - fork-join

This fork-join block should be used in Testbench and not in the design.

![image](https://github.com/user-attachments/assets/284fca2d-c674-4734-9ce3-ac78e06c227f)

Combinational Logic circuits: List of Examples

![image](https://github.com/user-attachments/assets/ca164a15-61a7-4928-8711-23b64a96bbe2)

Example: 8x1 mux with 4x1 and 2x1

This is a example for bottom up approach.

![image](https://github.com/user-attachments/assets/f647185e-f8cd-4893-9017-216b047e317c)

Example: AND gate using 2x1 Mux

Using MUX we can any circuits.

![image](https://github.com/user-attachments/assets/fa6c6816-46fe-45a1-8b79-2aeb2470925d)

Example: 1x8 Demux

![image](https://github.com/user-attachments/assets/abaca8ab-ca49-43f3-9e80-3dde23cb1f04)

Example: Full Adder & 4-bit Full Adder

![image](https://github.com/user-attachments/assets/e1c3f6a7-5fbd-4369-af1f-d2fbf759a626)

Example : 3x8 Decoder and 3x8 Decoder using 2x4 decoder

![image](https://github.com/user-attachments/assets/7d0b877c-b302-4c0f-bb84-6e9fcc590c4d)

![image](https://github.com/user-attachments/assets/260d2130-f686-4b3c-94af-c10c14d281a6)

Example : 8x3 encoder

![image](https://github.com/user-attachments/assets/23f18cf2-de48-49f1-9a3a-d1c7ab7dc765)

Example : Priority encoder

Here 'casex' is used since we used don't cares.

![image](https://github.com/user-attachments/assets/8010b5f7-172f-4263-a6cf-5bc039825de6)

![image](https://github.com/user-attachments/assets/fef1ef63-b77e-4274-9588-1e300d6c53af)

Example : Seven Segment Display

![image](https://github.com/user-attachments/assets/a0a30e8c-d8b0-41f3-8ffc-6b510064c470)

![image](https://github.com/user-attachments/assets/f7021962-f56e-47d2-9990-44628ec1eb9d)

Example : ALU

![image](https://github.com/user-attachments/assets/1ee1b604-4d06-4dfc-8694-385c4216ec0a)

![image](https://github.com/user-attachments/assets/8249455a-ae2b-460d-bcf0-4bbd242092aa)

Sequential Logic Circuits: List of Examples

![image](https://github.com/user-attachments/assets/13231750-10b1-433d-ac22-597aa56fcff5)

Example: D Flip Flop vs D-Latch

![image](https://github.com/user-attachments/assets/71aaf259-cb0b-42f6-a4b3-02ee2a07cb73)

Example: Synchronous Reset D-Flip flop , Asynchronous Reset D-Flip flop

![image](https://github.com/user-attachments/assets/78ab4b93-c91a-408c-87b9-8da926a5e4fd)

Example : T-Flip Flop

![image](https://github.com/user-attachments/assets/9ddc7d63-5065-4869-b048-8037590902f1)

Example : Master-slave JK Flip Flop

![image](https://github.com/user-attachments/assets/b6d47eb3-332c-44dd-afd3-039d5cb9549a)

Example: Counter

Here the counter using FF is complex level and it is not used in the industry also. The second method is preferable.

![image](https://github.com/user-attachments/assets/26490a6e-f621-4c62-aed5-5d5f44afe204)

Example: UP/Down Counter

![image](https://github.com/user-attachments/assets/6078a0be-6767-4ee5-b80d-8e8524b8060a)

Example: clock divider using counter- Divide by 2,4,8,....

![image](https://github.com/user-attachments/assets/4546fdd0-8b5d-4d19-a7e0-76283f5b49ee)

Example: Pulse Generator: Mod-3 pulse generator

![image](https://github.com/user-attachments/assets/a6bb01d6-bfc1-413a-bc48-f887c2266605)

Example: Divide by 3 clock

![image](https://github.com/user-attachments/assets/67dc8d0f-97db-445b-b463-aa9a76c5dca1)

Example : Ring Counter vs Jonson Counter

![image](https://github.com/user-attachments/assets/48370e13-84c8-45ad-aa22-87a66896397d)

Example : Shift Registers : SISO, SIPO, PISO,PIPO

![image](https://github.com/user-attachments/assets/6d0df67f-7d6a-45aa-96df-de8f982413ff)

Example: LFSR (Linear Feedback Shift Register)- Random Generator

![image](https://github.com/user-attachments/assets/6f67c7ac-42c2-4dde-94c2-46186f45533c)

Memory design

![image](https://github.com/user-attachments/assets/8415e77c-9aae-410a-a97d-94a75c52011a)

Switch level modeling

![image](https://github.com/user-attachments/assets/de7c861a-91d5-41f1-b252-d51b81d68be0)

![image](https://github.com/user-attachments/assets/7ca053c1-7a6d-4abb-87e4-a5d84385933c)

![image](https://github.com/user-attachments/assets/29fa1f95-a35b-468e-89e5-549681502807)

Testbench:

Functional Simulation:

![image](https://github.com/user-attachments/assets/42bc3b89-a6a6-4c5f-8a6c-07cad892b6d8)

![image](https://github.com/user-attachments/assets/cacb1a24-ffb3-4017-9987-496834f5f88c)

![image](https://github.com/user-attachments/assets/9bedb696-f572-482f-baf1-216fe313178d)

![image](https://github.com/user-attachments/assets/9624f203-4924-452b-86f0-f94f4559a34c)

Example - Test bench for counter design

![image](https://github.com/user-attachments/assets/fed3277c-3170-48af-af44-c110ba1a2a00)

![image](https://github.com/user-attachments/assets/b8a192a3-ee8c-44c5-b5bd-ed873f704bb5)

![image](https://github.com/user-attachments/assets/7301131c-f634-48fe-b80a-d462c0432869)

Example - Test bench for Pulse generator

![image](https://github.com/user-attachments/assets/e83569db-ce59-4329-803a-148d374b91db)

![image](https://github.com/user-attachments/assets/9b77560c-92b4-4f42-b57d-a5e39582ba39)

Functions & tasks and system tasks

![image](https://github.com/user-attachments/assets/927f0ccb-a834-44ff-abd8-ebc244297138)

![image](https://github.com/user-attachments/assets/946bb9ba-7462-4042-95b4-84a6e33d00d5)

![image](https://github.com/user-attachments/assets/c7b8e0aa-b3d9-4925-9013-ce2a17a07fa4)

![image](https://github.com/user-attachments/assets/60652d16-6824-41ef-9b78-dd3eb796d1ab)

File based system tasks and random generator system task

![image](https://github.com/user-attachments/assets/925d03e3-b277-4e2a-8abb-0f950cfc91c3)

![image](https://github.com/user-attachments/assets/f7f75db1-9b9a-4b05-adf0-fba884dc19bf)

![image](https://github.com/user-attachments/assets/5b58e4cb-5813-4d18-90ed-87a43d177f6c)

Read file and write in to memory system task

![image](https://github.com/user-attachments/assets/5fbe9261-cc9e-4d1f-8e3d-58553f441814)

Programming Language Interface

![image](https://github.com/user-attachments/assets/a6adc499-5630-4040-acd7-ac425c1ec1c6)

FSM Topics

![image](https://github.com/user-attachments/assets/a5fdbdec-0106-423e-bef2-eda07ce7ccfb)

Why FSM ?

![image](https://github.com/user-attachments/assets/2cf8698f-d644-451b-b6b7-e1068377b036)

What is FSM ?

![image](https://github.com/user-attachments/assets/db74a279-a38f-450f-a3c0-dc9b25e1d131)

Hardware Realization of FSM : Component or Modules in FSM

In any state machines we have 3 blocks, 1. Next state block, 2. Memory block and 3. Output block. Here, the Next state block and Output block are made of combinational logic and the memory block is FF.
Moore machine: The output depends on the present state.
Mealy machine: The output depends on the present state and the present inputs.

![image](https://github.com/user-attachments/assets/9080974d-b1bc-4715-bfb8-494f931efb2c)

Types of FSM and Mealy Moore FSM differences

![image](https://github.com/user-attachments/assets/6466ba74-419b-4be9-8d16-49e4db4d0f26)

Example : Mealy FSM

In s0, we understood that when carry=1, the sum=0. But in s1, we cannot say the output when carry=0. It can be only known be the present input and the present state. 

![image](https://github.com/user-attachments/assets/259509c5-b244-4772-95b3-ddd6f3d67620)

Example: Moore FSM

![image](https://github.com/user-attachments/assets/c8ef5cfb-61aa-4997-81d1-4f13519ab1f2)

Example: Verilog HDL for Mealy FSM

![image](https://github.com/user-attachments/assets/8e7ea421-34fa-4af4-ba77-6d0a01571492)

Example: Verilog HDL for Moore FSM

![image](https://github.com/user-attachments/assets/7e2c0892-21d2-41de-9bf4-43261986302f)

Hands-on : Verilog HDL for Mealy FSM and run the execution

Example: Divide by 2 clk using FSM

![image](https://github.com/user-attachments/assets/cc84d3a9-a81d-4224-b439-f497f887d72f)

Example: Divide by 3 clk using FSM

![image](https://github.com/user-attachments/assets/5b3c3c25-547c-4f9b-a03a-168c7f391745)

Example: 33 perecent duty cycle clock generation using FSM

![image](https://github.com/user-attachments/assets/42bc91a3-d7c7-4ec4-8ac1-275d80dfa551)

Sequence Detector using FSM

![image](https://github.com/user-attachments/assets/757be986-26e9-49f7-8126-68e55c877b37)

![image](https://github.com/user-attachments/assets/4b478a07-2b34-45b0-9441-ab9c051bf828)

Memory controller with Design & TB

![image](https://github.com/user-attachments/assets/3a86a62e-18ed-4b0b-9475-9fea22318a16)

![image](https://github.com/user-attachments/assets/d45dbe63-5c6d-485f-a95f-eedabba70b43)

![image](https://github.com/user-attachments/assets/452f726c-9c27-41bc-9e7f-01358da8d54b)

![image](https://github.com/user-attachments/assets/5785a139-6937-4cab-aa5a-ee4d44a66786)

Introduction to FIFO

![image](https://github.com/user-attachments/assets/6a0eaacf-9c1c-49bc-af48-80538e8df896)

![image](https://github.com/user-attachments/assets/8be4a0f3-61ba-4cfc-81ad-619c544dc991)

![image](https://github.com/user-attachments/assets/130f5c36-68d8-4737-948d-8678e2e47604)

Write Read Operation of Normal RAM

![image](https://github.com/user-attachments/assets/c8ba4162-0f3d-4e2a-894c-d1a995dd8990)

FIFO I/O (input & Outputs)

Address is required in RAM. But is not required in FIFO because the address will be generated internally.

![image](https://github.com/user-attachments/assets/3e7c7521-1cc6-49a9-b1b5-f90fb49035fd)

Block Diagram and Architecture of FIFO

In FIFO we have RAM and some extra logic. This extra logic is used for the generation of address and also generate the status(FULL or EMPTY) of the FIFO. Initially the address is '0', so the first data will gets stored in the '0'th location and we have 8 locations, so we can store data for 8 'write clock', and for each write clock the counter gets incremented and the data is stored. Also, the write enable should be '1' to write data.

![image](https://github.com/user-attachments/assets/777f8a5a-362d-4099-b4f9-5ebdc23a515d)

Connection of FIFO design & Test bench environment

We are designing the synchrounous FIFO, so there is no write or read clock and there is only a common clock.

Verilog HDL for FIFO design

Verilog HDL code for FIFO Test Bench

Hamming code complete Design & TB for error detection & correction

![image](https://github.com/user-attachments/assets/5dd24da8-977e-4cdf-868f-61bb2f5b233c)

![image](https://github.com/user-attachments/assets/6d70476d-38ee-4f5a-beec-8efdceb81945)

![image](https://github.com/user-attachments/assets/0ceab44e-39fe-48ed-8125-ed2ff4f2b3cc)

![image](https://github.com/user-attachments/assets/7abfbddf-1772-4801-9204-b7c70f65c8d3)

FPGA

CLB - It consists of SRAM Memory blocks followed by some array of Multiplexers then followed by D FF. The actual inputs of the design will be given to the select lines of the MUX. 
IOB - It has tristate buffers.
SM - These are used to connect the CLBs.
Now coming again to the CLB. Let us consider the XNOR code is dumped in the FPGA. So, the output of the code is taken by the look up table. Then based on the input, we will get the output. 

![image](https://github.com/user-attachments/assets/39d802f9-6a72-47d9-8858-d408b95969d6)

![image](https://github.com/user-attachments/assets/dc6c55b8-613a-449e-8e1a-cebd81f7e3ec)

![image](https://github.com/user-attachments/assets/38b476d6-8c62-41e1-9b67-f49d4fb6f1d9)

![image](https://github.com/user-attachments/assets/93abdcad-ab2a-434e-816a-a82eabe5258e)
