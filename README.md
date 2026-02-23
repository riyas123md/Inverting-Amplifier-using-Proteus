# Inverting-Amplifier-using-Proteus
## Experiment 1
Design and Simulation of Inverting Amplifier using Op-Amp (μA741) in Proteus
## Aim
To design and simulate an Inverting Amplifier using μA741 Op-Amp in Proteus Design Suite and verify the voltage gain experimentally.
## Apparatus / Components Required
S.No	Component	Specification	Quantity
1	Op-Amp IC	μA741	1
2	Resistor R1	10 kΩ	1
3	Resistor Rf	100 kΩ	1
4	Signal Generator	Sine wave, 1 kHz	1
5	Dual DC Power Supply	+15V, -15V	1
6	CRO / Oscilloscope	Virtual (Proteus)	1
7	Connecting Wires	—	As required
## Theory
An Inverting Amplifier is a closed-loop amplifier configuration where the input signal is applied to the inverting terminal (-) of the op-amp through resistor R1, and feedback resistor Rf is connected between output and inverting terminal.
The non-inverting terminal (+) is grounded.
## Circuit Description
•	Pin 2 → Inverting input
•	Pin 3 → Non-inverting input (Grounded)
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → -15V
The input sine wave is applied through R1 and output is taken from pin 6.
## Circuit Diagram
![exp01new](https://github.com/user-attachments/assets/154f9597-b906-4f42-90e3-e09825e05fe4)

## Tabulation
Input Voltage (Vin)	Theoretical Gain (Av)	Theoretical Vout	Practical Vout (Proteus)
| S.No | Input Voltage (Vin) | Theoretical Gain (Av) | Theoretical Vout (V) | Practical Vout (Proteus) (V) |
| ---- | ------------------- | --------------------- | -------------------- | ---------------------------- |
| 1    | 0.1 V               | -10                   | -1 V                 | -0.98 V                      |
| 2    | 0.2 V               | -10                   | -2 V                 | -1.97 V                      |
| 3    | 0.3 V               | -10                   | -3 V                 | -2.95 V                      |
| 4    | 0.5 V               | -10                   | -5 V                 | -4.9 V                       |
| 5    | 0.7 V               | -10                   | -7 V                 | -6.85 V                      |

## Simulation Procedure (Proteus)
1.	Open Proteus Design Suite
2.	Select components:
o	μA741
o	Resistors
o	AC Signal Generator
o	Oscilloscope
3.	Connect circuit as per inverting amplifier configuration.
4.	Set:
o	R1 = 10kΩ
o	Rf = 100kΩ
o	Input = 1V, 1kHz sine wave
5.	Apply ±15V power supply.
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
##  Waveform Observation
•	Input: Sine wave
•	Output: Amplified sine wave
•	Phase Shift: 180°
•	Gain ≈ -10
![exp 01 final op](https://github.com/user-attachments/assets/3bd58683-8a9c-4e29-b714-e67e5575dda1)


## Result
The Inverting Amplifier using μA741 Op-Amp was successfully designed and simulated in Proteus.
The practical output voltage closely matches the theoretical value.
The gain obtained is approximately -10, and the output waveform is inverted with respect to the input waveform.

