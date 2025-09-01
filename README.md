# universal-rf-pcb

Supervisor: [Mr. Axel](https://www.tu-braunschweig.de/cmos/team/wissenschaftliche-mitarbeiterinnen/axel-engelhardt)  

Hello this is my first hiwi task at CMOS Institute. 

<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/1.png?raw=true" width="400" height="250">
</div>


In this task, I first learned how to use Altium Designer. Then, I created the component libraries and designed the schematic. It was not difficult. Because there were not so manany componens. The layout is the important part of this task.

We place in the central a bare chip (without package). This chip will be designed by my supervisor. Wire bonding is used to connect the chip to the pads.

This board includes two differential pairs, four single-ended transmisson lines and serveral DC. Between the pads and the SMA Edge mount connectors the coplanar waveguides were used instead of microstrip lines. And there is also a structure of De-Embedding for measure.


<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/2.png?raw=true" width="250" height="300">
</div>

<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/4.png?raw=true" width="250" height="140">
</div>


In this project, simulation tasks were of great importance. For the choice of the simulation line, we selected the single-ended trace used for de-embedding, as it was the longest and most meandering. 

The reasoning was that if its results were satisfactory, then the performance of the other traces would certainly be acceptable as well.

<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/3.png?raw=true" width="340" height="110">
</div>



Based on the simulation results, three versions of the PCB were designed. 

In version V1.0, SMA THT connector was used. However, its diameter was much larger than the PCB trace, which caused multiple reflections.



<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/origin.png?raw=true" width="450" height="320">
</div>


In version V1.1, taking RF impedance theory into account, the ground under the SMA THT connector was removed so that its reference ground was on Layer 3. This approach achieved a slightly better result but oscillations still remained.


<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/ref3.png?raw=true" width="450" height="320">
</div>

In version V2.0, an SMA edge-mount connector was used, and the simulation results were relatively satisfactory.


<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/s11.PNG?raw=true" width="600" height="300">
</div>

<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/s12.png?raw=true" width="600" height="300">
</div>

<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/s21.PNG?raw=true" width="600" height="300">
</div>

<div align=center>
	<img src="https://github.com/myry07/universal-rf-pcb/blob/main/jpg/s22.PNG?raw=true" width="600" height="300">
</div>


