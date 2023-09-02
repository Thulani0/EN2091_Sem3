## EN2091_Sem3
### EN2091 - Laboratory Practice and Projects 

During the third semester's EN2091-Laboratory Practice and Projects module, our team comprising Sadeep Madhushan, Aaqil Ahamed, Nimesh Fernandopulle, and Thulani Amanda meticulously designed and executed a Linear Power Supply Unit project. Our goal was to create a 10V, 10A Linear Power Supply from scratch, capable of maintaining constant voltage/current for a 100W load from a 230V input.
Pooling our skills, we collaboratively addressed every aspect of the project with professionalism. This encompassed conceptualization, voltage regulator implementation, PCB design enhancement, and enclosure development. Our efforts culminated in a successful outcome.  
<p align="center">
  <img width="300" height="300" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/ba7504f8-4cce-4c9e-9d86-70376778d817.png">
</p>


#### What you can find here: 
- Methodology 
- Simulation Circuit
- Schematic Diagrams
- PCB Designs
- Enclosure Designs
### Methodology
The circuit design contains following six stages:
  - Step-Down Transformer 
              -	In this project a voltage ratio of 230:15 step-down transformer is used to get the desirable voltage level which can be tolerated by the electronic components in the next stage.
  -	Full-wave rectification
              -	There are so many methods to rectify the AC voltage. But in this project Wheatstone bridge rectifier is used. Because it is the most common and simplest method to rectify the sinusoidal AC voltage.
  -	Smoothing stage
  -	Voltage Regulation stage
              -	In this stage, the ripple in the smoothened volt age is removed and output a constant DC voltage. In our project we mainly use two transistors, a resistor, a diode and a Zener diode. These two transistors (MJ4502 and BC547A) are connected as Sziklai pair. It acts as a single transistor and has a high current gain than an individual transistor.

  <p align="center">
  <img width="200" height="300" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/9b65e196-67ea-4ce6-aba7-aa1b6d3dbd99.png">
</p>



  -	Current limiting stage
              -	This project is to design a 10V power supply with 10A high current. If there flows a high current than 10A it will cause damage to the load and the circuit components. Therefore, we have to limit the current to 10A.
   	
<p align="center">
  <img width="300" height="400" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/27aca7c6-5624-4089-8467-f2812b7cb5cc.png">
</p>

  -	Circuit Protection

<br>


### Simulation Circuit

<p align="center">
  <img width="800" height="550" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/c5317808-6fb1-44ae-bc7d-9f4855a5be91.png">
</p>

### PCB Schematic

<p align="center">
  <img width="600" height="500" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/1125d088-1511-4a8a-9de6-2058b7102ac1.png">
</p>



### PCB Layout

<p align="center">
  <img width="500" height="500" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/12738099-bfc7-4c85-82fe-aadae730c9e0.png">
</p>

### Enclosure
<p align="center">
  <img width="600" height="400" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/fde12d06-ecb5-4a49-ada0-6e540868683e.png">
</p>

