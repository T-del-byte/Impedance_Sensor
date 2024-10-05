# IMPEDANCE_SENSOR
# Objective
To design an impedance sensor requires careful consideration of factors such as frequency range, accuracy, resolution, and noise.
# Tools & technologies
Nano, LCD Module Display, Resistor, Capacitor, Inductor.
# Working Principle
The principle relies on generating an alternating signal, applying it to the material or circuit under test, and then measuring the resulting voltage and current to calculate impedance.
# Construction
- Set up a circuit with a reference resistor in series with the unknown impedance.  
- Connect one side of the reference resistor to the PWM pin or signal generator, and the other side to the unknown impedance.
- Measure the voltages across both the reference resistor and the unknown impedance using the analog input pins (A0, A1, etc.).
- Use the analogRead() function to capture the voltages at different points in the waveform.
- Apply the formulas above to calculate the impedance.
- Display the impedance value on an LCD or send the data to a computer via the serial port.
# Output
The final output of the Impedence sencor is we were able to measure resistence only.
# Future Improvements
We have to take a look on the issues regarding the non-calculated inductance and capacitance which are expected to be measured.
# Applications 
Bioimpedance Measurement, Soil Moisture Measurement, Wearable Devices for Health Tracking.
