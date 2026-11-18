# Precision Sensor Interface Design

### From Physics to PCB to Firmware

**Author:** Mohsen Hatami  
**Edition:** First Edition (2026)  
**Format:** PDF · 306 pages

[**Read or download the book (PDF)**](./Precision_Sensor_Interface_Design.pdf)

## About the book

*Precision Sensor Interface Design: From Physics to PCB to Firmware* is a technical textbook and reference for instrumentation, analog, and embedded hardware engineers and graduate students. It follows a measurement from the physical quantity to the number in firmware: the sensor and its physics, the way it is connected, the bridge, the amplifier, the anti-aliasing filter, the data converter, and the digital filter. It brings together explanations, design equations, step-by-step procedures, read-out circuits with real ICs, design rules, and worked examples. It is the companion volume to *High-Speed Digital Design*.

This edition has 16 chapters, an appendix of answers, more than 160 figures, more than 30 tables, 47 worked examples, and 143 references. One three-channel force, current, and temperature front-end is used as a running reference design throughout. Each chapter opens with an overview and learning objectives and closes with key takeaways, further reading, review problems, and a Practical Example: a complete design case with its own circuit, worked in numbered steps. The answers to all 172 review problems are collected at the back of the book. Worked equations are set on their own lines, and every figure states what kind of evidence it is: analytical, simulation, schematic, conceptual, or photograph.

The book is planned in ten parts. This edition contains Part I, Part II, and the active-filter chapter of Part IV; the remaining parts are in preparation, and the chapters keep the numbers they have in the complete plan.

## Topics covered

- **Part I — Foundations of Measurement:**
  - The measurement chain as a system, and the work-backward method: from the smallest change that must be detected to the noise, gain, and converter requirements.
  - How a sensor is connected to a circuit: in series, in parallel, and in a bridge, with a first read-out circuit for each kind of sensor.
  - The Wheatstone bridge: quarter, half, and full bridge, their equations, linearity, and temperature compensation.
  - Metrology: accuracy, precision, resolution, uncertainty budgets, and calibration.
  - Noise: thermal, shot, and flicker noise, noise bandwidth, amplifier noise models, and a complete input-referred noise budget.
  - Signals and systems: transfer functions, Bode plots, first- and second-order responses, and Sallen–Key filter analysis.
  - Sampling, aliasing, and the Nyquist criterion, with anti-aliasing filter requirements and input circuits for SAR and delta-sigma converters.
  - Digital filters: FIR and IIR block diagrams, the moving average, the exponential moving average, and the biquad, with Python code and real sample records.
  - Changing the sample rate: downsampling, decimation, upsampling, interpolation, and oversampling for resolution.
- **Part II — Sensors: Physics, Models and Electrical Behavior:**
  - Strain, force, load, and torque: strain gauges, load cells, and piezoelectric and capacitive force sensors.
  - Pressure and vacuum: piezoresistive, capacitive, and resonant sensors, and vacuum gauges.
  - Temperature: RTDs, thermistors, thermocouples, semiconductor sensors, and infrared thermometry.
  - Position, displacement, proximity, and angle: potentiometers, LVDTs, resolvers, encoders, and capacitive, inductive, magnetic, and optical ranging sensors.
  - Motion, vibration, and inertial sensing: accelerometers, IEPE sensors, gyroscopes, and magnetometers.
  - Current and voltage sensing: shunts, Hall, fluxgate, and magnetoresistive sensors, current transformers, Rogowski coils, and isolated amplifiers and modulators.
  - Flow and level: differential-pressure, thermal, Coriolis, magnetic, ultrasonic, vortex, and turbine meters, and level measurement.
  - Optical and radiation sensors: photodiodes, APDs, SiPMs, PMTs, image sensors, and radiation detectors.
  - Acoustic and ultrasonic sensors: microphones, hydrophones, and ultrasonic transducers.
  - Chemical, environmental, and biopotential sensors: humidity, gas, pH, conductivity, ECG, EMG, and EEG.
  - Smart, digital, and MEMS sensors: architecture, buses, timing, and power.
  - Read-out circuits with real ICs in every sensor chapter, including the HX711, INA333, ADS1220, XTR115, MAX31865, MAX31855, AD598, AD2S1210, LDC1612, INA226, INA240, AMC1301, TDC1000, OPA380, LMP91000, AD5933, and AD8232.
- **Part IV — Analog Signal Conditioning (Chapter 22):**
  - Active filters in the analog-to-digital signal chain: first-order stages, and Sallen–Key and multiple-feedback low-pass, high-pass, and band-pass sections.
  - Butterworth, Bessel, and Chebyshev responses, cascaded sections, and the limits set by a real amplifier.
  - Design examples with standard component values, including a differential converter driver.

The back matter includes:
- Appendix A, with the answers to all review problems;
- a numbered reference list of books, standards, papers, application notes, and datasheets.

## Intended readers

Practicing instrumentation, analog, and embedded hardware engineers, and graduate students with a background in circuit theory and basic signals and systems. The book develops the noise, bridge, filter, and sampling results it uses from first principles, and assumes no prior experience with sensors.

## A note on the circuits and worked examples

The circuits and worked examples are calculated examples for study and a starting point for engineering work. They have not been built or measured. The plots are evaluations of the equations in the text, or simulations whose assumptions are stated in their captions; the sample records in Chapter 4 are produced by the Python programs printed with them. Component part numbers and datasheet values are given for illustration. Values marked "verify" in the text must be confirmed against the current revision of the datasheet or standard before a design is built; see the notice on the copyright page.

## Copyright and permitted use

Copyright © 2026 **Mohsen Hatami**. All rights reserved.

The PDF may be downloaded and read for personal use. **Do not modify or redistribute the PDF.** To share it, link to the author's official GitHub or LinkedIn page rather than uploading another copy. This PDF should be hosted here only with the author's permission.

**This repository is not published under an open-source license.** See the copyright page of the PDF for full terms and disclaimer.

## Feedback

Corrections and technical feedback are welcome. Please contact the author through his professional profile or an author-approved contact channel.
