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

1.Type the program in Quartus software.                                                                                                                                                                              2.Compile and run the program.                                                                                                                                                                                     3.Generate the RTL schematic and save the logic diagram.                                                                                                                                                       4.Create nodes for inputs and outputs to generate the timing diagram.                                                                                                                                          t 5.For different input combinations generate the timing diagram.
**PROGRAM**


![WhatsApp Image 2024-12-31 at 12 09 49_a57f5b21](https://github.com/user-attachments/assets/c80f29fe-ffd8-4c4b-9917-67231c5e1d80)

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: n.shalini;RegisterNumber:24002375
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**

![WhatsApp Image 2024-12-31 at 12 10 07_ee3019b6](https://github.com/user-attachments/assets/0a45e1c4-418a-4943-9e46-84b931ae2fe0)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![WhatsApp Image 2024-12-31 at 12 10 35_3177aa75](https://github.com/user-attachments/assets/289f9b92-f5f0-48f6-af19-2d1d705149d5)

**RESULTS**
Thus implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is done successfully
