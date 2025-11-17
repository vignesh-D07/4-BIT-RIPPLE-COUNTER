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

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

![WhatsApp Image 2025-11-17 at 12 59 36_c32f5f5c](https://github.com/user-attachments/assets/63999593-dc6b-43d9-80d9-225184ecb992)


 Developed by:JUHI JAHAN T S RegisterNumber:25011334
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**

![WhatsApp Image 2025-11-17 at 12 52 08_a7fc74ca](https://github.com/user-attachments/assets/3b12170b-2823-4664-88e5-4a881efd9e01)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![WhatsApp Image 2025-11-17 at 12 52 11_5054c276](https://github.com/user-attachments/assets/4316e998-7253-4cee-8852-d67e30c4b368)

**RESULTS**
Thus 4-BIT-RIPPLE-COUNTER is verified successfully
