# D_Flip-Flop-using-28nm-CMOS-Technology <br/>
This respossitory presents the design and implemenataion of a D Flip-Flop on Synopsys Custom Compiler in 28nm technology node.<br/>
# Table Of Content <br/>
* [Abstract](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#Abstract)</br>
* [Introduction](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#introduction)<br/>
* [D FLIP FLOP CIRCUIT DESIGN](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#d-flip-flop-ciruit-design)<br/>
* [CMOS D Flip Flop](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#cmos-d-flip-flop)<br/>
* [Tool used](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#tool-used)<br/>
* [Schematic](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#Schematic)<br/>
* [Symbol](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#Symbol)<br/>
* [Test bench Schematic](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#Test-bench-Schematic)<br/>
* [Waveforms](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/edit/main/README.md#waveforms)<br/>
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
D flip-flop can be built in different methods by using NAND and NOR gate. In this project a D flip flop is designed and implemented using NOR and AND gates. This design is further designed in TRansisitor level as shown below<br/>
![dflipflop](https://user-images.githubusercontent.com/62325785/156088504-51bb3694-41a5-4ee4-bde2-da4725b1f8a8.png)<br/>
The input D and D* are given in both sides , since it is a advancement of JK flipflop the outputs Q and Q* are connected inversely to the inputs D and D* and the ouput will be collected from Q and Q*.<br/>
# Tool used</br>
*Synopsys Custom Compiler*:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. The above CMOS level cicruit is designed by using this tool.<br/>
*Synopsys Primewave*:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. With the help of the tool the above CMOS ciruit is simulated.<br/>
*Synopsys 28nm PDK*:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above circuit design.<br/>
# Schematic</br>
D flip flop design in Synopsys Custom Compiler tool<br/>
![D FF Sch](https://user-images.githubusercontent.com/62325785/156106192-8958fcef-3e25-45cb-ad74-017584758d77.png)<br/>
# Symbol</br>
Symbol created from the D flip flop design is<br/>
![symbol](https://user-images.githubusercontent.com/62325785/156106206-87a80a2d-19b0-4b26-82c3-2b8c7c7cbe53.png)<br/>
# Test bench schematic<br/>
Schemaic designed to similate<br/>
![TB_schematic](https://user-images.githubusercontent.com/62325785/156106234-b7f8342f-ef00-414a-987f-23290675d4c0.png)<br/>
# Waveforms<br/>
Waveforms generated after implimentation<br/>
![Schematic waveforms](https://user-images.githubusercontent.com/62325785/156106216-872c7613-fd85-4b51-8a1b-2bd5fe49366a.png)<br/>
# Netlist<br/>
Netlist for the D flip flop circuit can be viewed [here](https://github.com/saicharanreddy17/D_Flip-Flop-using-28nm-CMOS-Technology/blob/main/Netlist.spi)<br/>
# Author</br>
Baddi Sai Charan Reddy ,
BTech in Electronics and Communication Engineering at B V Raju Institute of Technology, Narsapur, Telangana.502313.</br>
# Acknowledgements </br>
[Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.](https://www.linkedin.com/in/kunal-ghosh-vlsisystemdesign-com-28084836/)<br/>
[Cloud Based Analog IC Design Hackathon](https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/)<br/>
[Synopsys India](https://www.synopsys.com/)<br/>
# Refernce<br/>
1.https://electronics.stackexchange.com/questions/401240/cmos-implementation-of-d-flip-flop<br/>
2.1.	Design of CMOS Based D Flip-Flop with Different Low Power techniques<br/>
