**EX.NO:6**  
# SR-FLIPFLOP-USING-CASE  
**DATE:**  
**NAME :SUBHASHINI.B**  
**REGISTER NUMBER :212223040211**  
**AIM:**

To implement  SR flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/0f710028-ad52-4d3e-9276-8714cf023a25)

 
This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dabfc4f4-87e3-4cbc-9472-f89ee1b5ed30)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/dd90d16c-aec5-4290-a586-e2346b1e9eb5)

 
By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![image](https://github.com/naavaneetha/SR-FLIPFLOP-USING-CASE/assets/154305477/473efad6-d70b-4ca7-aeb7-898bbfca319f)

 
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram


**PROGRAM**

![Screenshot 2024-05-08 132350](https://github.com/subha-shinibalasubramanian/SR-FLIPFLOP-USING-CASE/assets/164154478/78bf3f72-3fab-44a4-80d0-2636e22f58f0)


**RTL LOGIC FOR FLIPFLOPS**

![Screenshot 2024-05-08 132408](https://github.com/subha-shinibalasubramanian/SR-FLIPFLOP-USING-CASE/assets/164154478/5297c483-11dc-4ff4-8bb3-f2a818811486)


**TIMING DIGRAMS FOR FLIP FLOPS**

![Screenshot 2024-05-08 132942](https://github.com/subha-shinibalasubramanian/SR-FLIPFLOP-USING-CASE/assets/164154478/8dd16108-90e3-4a2a-91d4-f882f0045ced)


**RESULTS**

Thus the program to implement a SR flipflop using verilog and validating their functionality using their functional tables is successfully completed.


