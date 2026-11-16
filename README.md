# WaveLab ECE — Interactive Virtual Laboratory & Viva Workstation

**WaveLab ECE** is a single-page, zero-dependency virtual laboratory, Digital Storage Oscilloscope (DSO) waveform simulator, circuit theory reference, and oral viva preparation suite built for B.Tech Electronics and Communication Engineering (ECE) students across **Semesters I through VIII**.

---

## Key Features

- **8-Semester Curriculum Navigator (Sem I – VIII):** Covers core ECE practical subjects including Basic Electrical & Electronics (BEEE), Semiconductor Devices, Analog Electronic Circuits, Digital System Design, Linear Integrated Circuits (Op-Amps), Microcontrollers (8051/ARM), Analog & Digital Communication, Digital Signal Processing (DSP), VLSI Design, Microwave & Optical Fiber, and Embedded IoT.
- **60fps Interactive DSO Waveform Simulator:**
  - Dual-channel phosphor display (`CH1` input in cyan, `CH2` output in amber) rendered via HTML5 Canvas.
  - Real-time controls for Frequency, Amplitude, Volts/Div, Time/Div, and circuit-specific parameters.
  - Automated telemetry readouts ($V_{pp}$, Frequency, Phase Shift) and **Hardware Fault Injection** mode to observe real-world clipping, saturation, and distortion behavior.
- **Circuit Schematics & Blackboard Derivations:**
  - Interactive SVG circuit diagrams with clickable test points (`TP1`, `TP2`, `TP3`).
  - Step-by-step mathematical derivations, design formulas, and Bill of Materials (BOM) with IC part numbers.
- **Viva Exam Simulator & Diagnostic Fault Quizzes:**
  - High-yield oral examiner trap questions with revealable model answers and self-rated confidence tracking that dynamically updates the **Viva Readiness Index**.
  - Interactive diagnostic fault-finding MCQs with instant circuit explanations.

---

## Project Structure

```text
wavelab-ece/
├── index.html      # Complete self-contained application (HTML, Tailwind CSS, Canvas DSO & JS)
└── README.md       # Project documentation