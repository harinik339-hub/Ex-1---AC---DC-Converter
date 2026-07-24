# Ex-1---AC---DC-Converter
**Aim:**
To design, simulate, and analyze an AC–DC converter circuit using Proteus software by converting alternating current (AC) input into direct current (DC) output using a transformer, bridge rectifier, filter capacitor, and voltage regulator.
**Apparatus Required**
S.No	Components/Software	Specification
1	Proteus Design Suite	Version 8.0 or above
2	AC Voltage Source	230 V AC / 50 Hz
3	Step-down Transformer	230 V / 12 V
4	Bridge Rectifier	Four 1N4007 Diodes
5	Filter Capacitor	1000 µF / 25 V
6	Voltage Regulator IC	7805 / 7812
7	Resistor	1 kΩ
8	LED	Indicator
9	Ground Terminal	-
10	Oscilloscope/Voltmeter	Virtual Instrument
 **Circuit Diagram**

(Insert Proteus circuit diagram here)

**Theory**
An AC–DC converter is an electronic circuit that converts alternating current (AC) into direct current (DC). Most electronic devices require a stable DC voltage for operation; therefore, power supply circuits are widely used in electronic systems.
The AC–DC conversion process consists of four stages:
1. Step-Down Transformation
The transformer reduces the mains voltage (230 V AC) to a lower AC voltage, typically 12 V AC, suitable for electronic circuits.
2. Rectification
A bridge rectifier composed of four diodes converts the alternating current into pulsating direct current. During each half-cycle of the AC input, two diodes conduct, resulting in full-wave rectification.
3. Filtering
A capacitor connected across the rectifier output smooths the pulsating DC by reducing ripple voltage. The capacitor charges during voltage peaks and discharges during voltage drops, producing a nearly constant DC output.
4. Voltage Regulation
A voltage regulator IC such as 7805 or 7812 maintains a constant output voltage irrespective of input fluctuations or load variations. The regulated output is supplied to the load circuit.
Proteus software enables virtual implementation and analysis of the complete AC–DC converter without requiring physical components. Instruments such as oscilloscopes and voltmeters can be used to observe waveforms and measure output parameters.
**Procedure**
1.	Open Proteus Design Suite and create a new project.
2.	Select and place the required components:
o	AC source
o	Transformer
o	Four diodes (1N4007)
o	Capacitor
o	Voltage regulator
o	Load resistor and LED
3.	Connect the components according to the circuit diagram.
4.	Set the component values:
o	Transformer: 230 V / 12 V
o	Capacitor: 1000 µF
o	Regulator: 7805 or 7812
5.	Connect virtual instruments such as voltmeter and oscilloscope.
6.	Run the simulation.
7.	Observe:
o	AC waveform at transformer output
o	Pulsating DC after rectifier
o	Filtered DC after capacitor
o	Regulated DC output
8.	Record the output voltage and waveform characteristics.
**Output**
(Insert Proteus output diagram here)
 

**Result**
The AC–DC converter circuit was successfully designed and simulated using Proteus software. The alternating current input was converted into a stable direct current output through rectification, filtering, and voltage regulation stages. The simulated output voltage matched the expected theoretical values.

