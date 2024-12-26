# EXPERIMENT-4-BIT-RIPPLE-COUNTER

# NAME: PRASIDHA A

# REGISTER NUMBER: 24005839

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

**PROCEDURE**

 1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram

**PROGRAM**


![Screenshot 2024-12-26 185012](https://github.com/user-attachments/assets/6e585219-1515-441e-bab1-7e6bcfa12fdf)


**RTL LOGIC**


![Screenshot 2024-12-26 185056](https://github.com/user-attachments/assets/3a592b74-0eda-4751-bddd-60f389620379)


**TIMING DIGRAMS**


![Screenshot 2024-12-26 185124](https://github.com/user-attachments/assets/874c34a7-d30d-48d4-99d1-755443110e03)


**RESULTS**

Thus, to implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is verified.
