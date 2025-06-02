# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**
1.Type the program in Quartus software.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create nodes for inputs and outputs to generate the timing diagram.
5.For different input combinations generate the timing diagram.

**PROGRAM**
![393585436-419218b9-fe5c-4706-9dd5-b6eaae954277](https://github.com/user-attachments/assets/31d77030-d8a1-46c3-9da1-0e951fde9c64)


**RTL LOGIC FOR 4 Bit Ripple Counter**
![393585505-2e366ee4-f484-4c6b-9c1e-c576f25e10ff](https://github.com/user-attachments/assets/db61d9a7-ff78-47c9-93dd-8b7b5dd20f5d)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![393585804-6b6c83f4-cddf-4d18-97a1-45bb6e2d3a35](https://github.com/user-attachments/assets/2d5fead8-6706-468c-b475-f38ab106b01b)

**RESULTS**
