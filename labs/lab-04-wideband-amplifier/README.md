# Wide-Band Amplifier with Feedback

I designed a two-stage BC238 amplifier with feedback to study gain, bandwidth, harmonic content, and input and output impedance. The design uses a 12 V supply and a 47-ohm load, with a target midband gain of 20 dB.

The [final report](final-report.pdf) contains the circuit drawings, simulation plots, and breadboard measurements. It reports approximately 20.09 dB gain at 200 kHz and 54 mA supply current.

The report has an unresolved unit discrepancy in its input-resistance discussion: the simulation section uses 47 ohms and the hardware section uses 47 kilohms. Its phase-margin description also needs a separate technical check. I have left the report's technical content unchanged and do not present those figures as verified results.

## Download reports

If GitHub's PDF preview is blank or reports an error, use these direct file links:

- [Download final report PDF](https://raw.githubusercontent.com/ekinsoo/ee313-electronic-circuit-design/main/labs/lab-04-wideband-amplifier/final-report.pdf)
