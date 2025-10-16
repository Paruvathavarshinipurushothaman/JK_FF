# JK_FF
AIM: 

To implement JK flipflop using verilog and validating their functionality using their functional tables 

SOFTWARE REQUIRED: 

Quartus prime 

THEORY 

JK Flip-Flop 

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure. 

<img width="610" height="402" alt="image" src="https://github.com/user-attachments/assets/3912edea-397b-4ff9-b526-1b8c0c8495fb" />
This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop. 
<img width="412" height="336" alt="image" src="https://github.com/user-attachments/assets/7f5e4d26-9c8f-4ebe-b6b7-36158c226084" />
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State 

<img width="575" height="487" alt="image" src="https://github.com/user-attachments/assets/5d2e86ba-d2ab-41f7-a9dd-60a9799fd0f9" />
By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure. 
<img width="357" height="248" alt="image" src="https://github.com/user-attachments/assets/00c1ff29-df84-4036-937d-12394d0037bc" />
The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

RESULTS:
Thus the JK flipflop using verilog and validating their functionality using their functional tables is implemented and verified. 



