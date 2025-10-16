<img width="1821" height="897" alt="image" src="https://github.com/user-attachments/assets/b7f5192c-7c6e-496a-af25-d096a29e216f" /># JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![WhatsApp Image 2025-10-15 at 10 06 00_80c4deb5](https://github.com/user-attachments/assets/34cafcdb-946d-4048-a4eb-ea6fb72199be)



This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

/* write all the steps invloved */

**PROGRAM**
<img width="1821" height="897" alt="image" src="https://github.com/user-attachments/assets/04399a5e-02ae-4162-89b1-1c24edaa85c0" />


/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:DWIJESH RAJ SINHA Y RegisterNumber:25013468
*/

**RTL LOGIC FOR FLIPFLOPS**
![WhatsApp Image 2025-10-15 at 10 06 01_7fa27b4a](https://github.com/user-attachments/assets/2d49c451-63c6-4472-8e2f-0ddc4f796ffe)

**TIMING DIGRAMS FOR FLIP FLOPS**

**RESULTS**
thus the logic for the given code is verified and studied successfully 
