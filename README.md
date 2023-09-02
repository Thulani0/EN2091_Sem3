## EN2091_Sem3
### EN2091 - Laboratory Practice and Projects 

During the third semester's EN2091-Laboratory Practice and Projects module, our team comprising Sadeep Madhushan, Aaqil Ahamed, Nimesh Fernandopulle, and Thulani Amanda meticulously designed and executed a Linear Power Supply Unit project. Our goal was to create a 10V, 10A Linear Power Supply from scratch, capable of maintaining constant voltage/current for a 100W load from a 230V input.
Pooling our skills, we collaboratively addressed every aspect of the project with professionalism. This encompassed conceptualization, voltage regulator implementation, PCB design enhancement, and enclosure development. Our efforts culminated in a successful outcome.  
<p align="center">
  <img width="300" height="300" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/a1b13a89-7c5f-4399-993e-4feb717726c2.png">
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
  <img width="200" height="300" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/fa4501e1-89d3-4c5f-825c-b8708de21c47.png">
</p>


  -	Current limiting stage
              -	This project is to design a 10V power supply with 10A high current. If there flows a high current than 10A it will cause damage to the load and the circuit components. Therefore, we have to limit the current to 10A.
   	
<p align="center">
  <img width="300" height="400" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/9ba8453c-13c7-4447-b5bd-6b6053eb30e9.png">
</p>

  -	Circuit Protection
<br>


### Simulation Circuit

<p align="center">
  <img width="800" height="550" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/fd26319d-2703-4f34-82a3-76c337708049.png">
</p>

### PCB Schematic

<p align="center">
  <img width="600" height="500" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/7b4b06f5-407f-4b79-b21d-9d33c180a413.png">
</p>


### PCB Layout

<p align="center">
  <img width="500" height="500" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/2337f858-1bbc-4c22-99c1-2233734f31bd.png">
</p>

### Enclosure
<p align="center">
  <img width="600" height="400" src="https://github.com/Thulani0/EN2091_Sem3/assets/129428203/ba9ac0c9-3d37-4bb2-8427-728cfe0ca410.png">
</p>

