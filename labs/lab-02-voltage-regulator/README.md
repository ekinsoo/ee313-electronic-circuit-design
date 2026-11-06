# Low-Dropout Voltage Regulator

I measured the current gain of a PNP transistor and designed an 11.5 V regulator using an LM358, a BD136 pass transistor, and a Zener reference. I compared line regulation, load regulation, and an LED regulation indicator in simulation and on a breadboard.

The [final report](final-report.pdf) contains the drawings and measurements. It reports approximately 6.6 mV line variation and 3.0 mV load variation in simulation. The hardware section uses a 560-ohm load, about 20 mA at the reported output voltage, followed by a no-load comparison. That does not establish hardware regulation at the original 100 mA target.
