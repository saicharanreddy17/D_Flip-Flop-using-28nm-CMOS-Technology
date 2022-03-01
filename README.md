# D_Flip-Flop-using-28nm-CMOS-Technology <br/>
This respossitory presents the design and implemenataion of a D Flip-Flop on Synopsys Custom Compiler in 28nm technology node.<br/>
# Table Of Content <br/>
* [Abstract](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#Abstract)</br>
* [Introduction](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#introduction)<br/>
* [D FLIP FLOP CIRCUIT DESIGN](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#d-flip-flop-ciruit-design)<br/>
* [CMOS D Flip Flop](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#cmos-d-flip-flop)<br/>
* * [Tool used](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#tool-used)<br/>
* [Setup & Hold Time](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#setup-&-hold-time)<br/>
* [Power Calculations](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#power-calculations)<br/>
* [Netlist](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#netlist)<br/>
* [Author](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#author)<br/>
* [Acknowledgements](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#Acknowledgements)<br/>
* [Refernce](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#refernce)<br/>
# Abstract<br/>
D Flipflop using 28nm CMOS Technology using Synopsys Tools, D Flipflop is a modified version of JK Flipflop in which it has only one input D, this input is connected to directly connected to J and inverted D is connected to K of JK Flipflop. It has two Outputs namely Q and Q*.D flipflop functionality is to gives the same output as the input. We can implement, design, and obtain the waveform using Synopsys custom design platform. The whole design is based on CMOS technology which features high speed, low power, small size, low cost.<br/>
# Introduction<br/>
D flipflop is a modified version of JK flipflop in which k terminal is given inverted value of D and basic memory unit which stores data of 1-bit is called flipflop. D flip-flop has one D input and a clocked input. D flip-flop is also called as delay flipflop.D flip-flop is edge triggered sequentail block , the main applications of D flip-flop is to introduce time delay in circuit just like a buffer and acts a 1 bit storage element.</br>
![DFlipflop_gate](https://user-images.githubusercontent.com/62325785/156086317-e4d58c2d-ce07-412e-bb98-83d194ee7083.png)<br/>
# D Flip Flop Ciruit Design <br/>
If the reset pin of D flip-flop is high the flip-flop is set to zero and the ouput will be zero, aaif the reset pin is zero and Whenever the clock input is high, (1)  D=0, the output of the flipflop will be active low Q=0 and Q* = 1, (2) when  D=1, the output of the flipflop is active high Q=1and Q*= 0.
As the output represents the input data D Flipflop is also called a “transparent flipflop”.
The truth table of the D flip-flop is <br/>
![dtruth](https://user-images.githubusercontent.com/62325785/156086466-b95d562e-abcb-46a0-a6e0-660b9f82dee1.png)<br/>
# CMOS D Flip FLop </br>
D flip-flop can be built in different ways 
![dflipflop](https://user-images.githubusercontent.com/62325785/156088504-51bb3694-41a5-4ee4-bde2-da4725b1f8a8.png)










