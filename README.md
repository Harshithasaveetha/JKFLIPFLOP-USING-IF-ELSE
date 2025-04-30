Reg no:212224040110
Name:Harshitha D

# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![300541519-a649c30b-232b-4558-b188-fd6c09845180](https://github.com/user-attachments/assets/1152c342-c2f9-4fff-aa07-6f437da0ca62)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![300541618-c4360742-e8a8-4937-b089-c46c0433f9a3](https://github.com/user-attachments/assets/e1258879-02f5-460f-9e5b-72cda0addef4)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 

![300541696-6c275261-a6d5-4c37-a3a7-1e88ca11c4cd](https://github.com/user-attachments/assets/e8e794d6-64b0-478d-9cf4-34c11701b8c7)



By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.


![300541801-5174f41b-0ce0-4329-a372-6d1943ea6673](https://github.com/user-attachments/assets/5e31c01a-f60b-47db-bc46-ff8278dc7b18)



The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.


**PROGRAM**

![439066909-72d0517a-3a00-4f31-b067-f6c6976f5d62](https://github.com/user-attachments/assets/f834dc04-14a9-4d9e-ba09-b59c6d572cef)
**Truthtable**

![439067279-8095feb9-911d-4ee8-970d-e4ae317f7212](https://github.com/user-attachments/assets/f67710b2-a306-412b-ac65-3d8f4cb8a8a6)


**RTL**
![439067355-c86d7838-ac95-4255-a50e-b9dbe2d1beb5](https://github.com/user-attachments/assets/a47f3bf4-56d2-49fd-b3be-ddd6956eef81)



**Waveform**
![439067416-ad9b4501-38d9-41b5-83e1-996be3e68eee](https://github.com/user-attachments/assets/618653fc-a91f-4370-b697-19485fa96914)

**RESULTS**
