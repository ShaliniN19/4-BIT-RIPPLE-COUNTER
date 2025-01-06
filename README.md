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

/* write all the steps invloved */

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: N.Shalini  RegisterNumber: 24002375
 
*/
![WhatsApp Image 2024-12-31 at 12 09 49_036510b6](https://github.com/user-attachments/assets/4c2e233b-c1c9-4248-9ddb-7607516ef9bc)


**RTL LOGIC FOR 4 Bit Ripple Counter**
![WhatsApp Image 2024-12-31 at 12 10 07_eccf45b3](https://github.com/user-attachments/assets/bd702c50-af63-436b-bf2d-abb64d163704)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![WhatsApp Image 2025-01-06 at 09 04 08_df8eccff](https://github.com/user-attachments/assets/ad8fd6b2-b52f-49ca-a468-2f37e8bb6e37)


**RESULTS**

Thus implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is done successfully
