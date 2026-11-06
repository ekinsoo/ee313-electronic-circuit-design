# Thermocouple-Controlled Heater

For my EE313 project, I designed and built a heater controller around a K-type thermocouple. An LM324-based instrumentation amplifier amplifies the thermocouple signal, a comparator checks it against a reference, and a BC238 transistor switches the heater. An LED indicates when heating is active.

I simulated the circuit in LTspice, drew the schematic and laid out the PCB in DipTrace, then assembled and tested the board. The final report includes the schematic, PCB layout, Gerber previews, photographs of the soldered board, and measurements.

## Reports

- [Final report](final-report.pdf): design overview, PCB implementation, and hardware results.
- [Design report](design-report.pdf): amplifier design, measured op-amp offsets, and simulation results.

The design report gives about 2.17 V output for zero input and 8.91 V for a 1.4112 mV input. The hardware report records 1.788 V at room temperature, with the LED on at 8.99 V and off at 9.17 V. These are historical report values, not new measurements.

The original project used a nominal 36-degree-Celsius setpoint. The reports demonstrate the amplifier and switching behavior, but do not establish calibrated absolute-temperature accuracy or cold-junction compensation. I would treat this as a course prototype rather than a calibrated temperature controller.

The original reports include the circuit and PCB drawings. Standalone CAD revisions and manufacturing exports are omitted because I could not verify which saved PCB file corresponds to the assembled board. The saved LTspice circuit also uses different reference-divider values from the DipTrace schematic shown in the final report.

## Download reports

If GitHub's PDF preview is blank or reports an error, use these direct file links:

- [Download design report PDF](https://raw.githubusercontent.com/ekinsoo/ee313-electronic-circuit-design/main/project-thermocouple-heater/design-report.pdf)
- [Download final report PDF](https://raw.githubusercontent.com/ekinsoo/ee313-electronic-circuit-design/main/project-thermocouple-heater/final-report.pdf)
