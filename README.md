### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

![WhatsApp Image 2024-12-09 at 02 12 16_a8786e92](https://github.com/user-attachments/assets/a05abd38-de48-4d3d-aec8-1805d195fe05)

**Procedure**

1.Type the program in Quartus software. 2.Compile and run the program. 3.Generate
the RTL schematic and save the logic diagram. 4.Create nodes for inputs and outputs togenerate the timing diagram. 5.For different input combinations generate the timing diagram.


**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming.
![WhatsApp Image 2024-12-09 at 02 18 12_d61d3ed7](https://github.com/user-attachments/assets/14fc1c11-5e61-4cfa-8ee3-3065d5d46249)


Developed by: SONA .S  RegisterNumber: 21224110049
*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![WhatsApp Image 2024-12-09 at 02 12 17_3760a767](https://github.com/user-attachments/assets/fb31b6cc-338b-455c-84bb-9bf9c2fc1929)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![WhatsApp Image 2024-12-09 at 02 12 17_983db314](https://github.com/user-attachments/assets/dee62aa6-65c7-4d0a-99f7-05650f59a339)


**RESULTS**

Thus to implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables is verified.


