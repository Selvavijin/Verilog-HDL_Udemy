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
