# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1a32e911-04fc-40c0-ab2f-dd9f5bb7b79e" />


## AC INPUT WAVEFORM:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f64a5922-a4b8-4374-9dcf-6ce5ff689913" />

## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a3e6244a-1fa6-457a-953d-e8829d3f6e26" />

## SIGNAL OUTPUT(WITH FILTER)

<img width="1920" height="1080" alt="Screenshot 2025-11-24 150705" src="https://github.com/user-attachments/assets/97ea7058-7891-49a0-ae31-2311124b4c73" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4581158a-6a29-4edb-a2f3-ad47a5fa8ab1" />


## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
