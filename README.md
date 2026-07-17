<p align="center">
  <img src="Images/final-project.jpg" alt="FM Radio Receiver" width="900">
</p>

<h1 align="center">📻 FM Radio Receiver with Audio Amplification System</h1>

<p align="center">
An analog FM radio receiver designed, simulated, and implemented using discrete electronic components. The project demonstrates RF tuning, FM demodulation, audio amplification, and practical hardware implementation on both Breadboard and PCB.
</p>

<p align="center">

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Course](https://img.shields.io/badge/Course-Electronic%20Circuits%20II-blue?style=for-the-badge)
![Simulation](https://img.shields.io/badge/LTspice-Simulated-red?style=for-the-badge)
![Hardware](https://img.shields.io/badge/Hardware-Tested-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)

</p>

---

# 📖 Overview

This project presents the complete design and implementation of an Analog FM Radio Receiver capable of receiving commercial FM radio stations in the 88–108 MHz frequency band.

The receiver consists of an RF reception stage, an LC tuning network for station selection, an FM demodulation stage, an audio amplification stage, and a regulated power supply. The complete system was first analyzed using LTspice simulation before being assembled and tested on both Breadboard and PCB.

Throughout the project, practical engineering challenges such as RF tuning, grounding, signal stability, and hardware debugging were addressed through iterative testing and optimization.

---

# ✨ Key Features

- 📡 FM Broadcast Reception (88–108 MHz)
- 🎚 Manual Frequency Tuning
- 📻 FM Signal Demodulation
- 🔊 Audio Amplification
- 🔈 8Ω Speaker Output
- 🧪 LTspice Circuit Simulation
- 🛠 Breadboard Implementation
- 💻 PCB Implementation
- 📈 Oscilloscope Testing
- 🔋 Battery Powered

---

# 🏗 System Architecture

```text
              Antenna
                 │
                 ▼
         RF Receiver Stage
                 │
                 ▼
        LC Tuning Circuit
                 │
                 ▼
      FM Demodulation Stage
                 │
                 ▼
      Audio Amplifier Stage
                 │
                 ▼
            8Ω Speaker
```

---

# 📸 Project Gallery

## Final Prototype

<p align="center">
<img src="Images/final-project.jpg" width="800">
</p>

---

## Breadboard Implementation

<p align="center">
<img src="Images/breadboard-implementation.jpg" width="800">
</p>

---

## PCB Implementation

<p align="center">
<img src="Images/pcb-implementation.jpg" width="800">
</p>

---

## Audio Amplifier

<p align="center">
<img src="Images/class-ab-amplifier.jpg" width="800">
</p>

---

## Power Supply

<p align="center">
<img src="Images/power-supply.jpg" width="800">
</p>

---

# 🧪 LTspice Simulation

### Amplifier Circuit

<p align="center">
<img src="Images/ltspice-amplifier.jpg" width="750">
</p>

### Output Waveform

<p align="center">
<img src="Images/ltspice-output.jpg" width="750">
</p>

The amplifier stage was simulated using LTspice to verify gain, waveform quality, and circuit stability before hardware implementation.

---

# 📊 Testing & Results

## Oscilloscope Output

<p align="center">
<img src="Images/oscilloscope-output.jpeg" width="750">
</p>

The completed hardware was experimentally validated through:

- Audio signal verification
- Oscilloscope measurements
- RF tuning evaluation
- Hardware debugging
- Grounding optimization
- Noise reduction

---

# 🔩 Main Hardware Components

| Component | Function |
|-----------|----------|
| FM Receiver Circuit | Receives FM broadcast signals |
| Antenna | Captures RF signals |
| LC Tank Circuit | Tunes the desired frequency |
| Audio Amplifier | Amplifies recovered audio |
| 8Ω Speaker | Produces sound |
| Voltage Regulator | Provides stable supply voltage |
| Battery | Powers the system |

---

# 🚀 Development Workflow

```text
Research
    ↓
Circuit Design
    ↓
LTspice Simulation
    ↓
Breadboard Assembly
    ↓
Hardware Debugging
    ↓
PCB Assembly
    ↓
Testing & Validation
```

---

# ⚠ Challenges

- RF tuning sensitivity
- Coil optimization
- Breadboard parasitic effects
- Signal instability
- Grounding issues
- Noise coupling
- Component tolerance variations

These challenges were addressed through repeated simulation, practical testing, and iterative hardware debugging until stable operation was achieved.

---

# 💡 Skills Demonstrated

- Analog Electronics
- RF Circuit Design
- Audio Amplifier Design
- LTspice Simulation
- Breadboard Prototyping
- PCB Assembly
- Oscilloscope Measurements
- Hardware Testing
- Circuit Debugging
- Engineering Problem Solving

---

# 📈 Future Improvements

- Increase receiver sensitivity
- Improve audio quality
- Design a compact custom PCB
- Add automatic station tuning
- Integrate stereo FM decoding
- Improve antenna matching

---

# 🎥 Project Demonstration

📹 **Project Video**

https://drive.google.com/file/d/1h2xnaICsLna61kK0NpyrLvJ_sNMtKfjN/view

---

# 📁 Repository Structure

```text
FM-Radio-Receiver
│
├── Images
│   ├── final-project.jpg
│   ├── breadboard-implementation.jpg
│   ├── pcb-implementation.jpg
│   ├── class-ab-amplifier.jpg
│   ├── power-supply.jpg
│   ├── oscilloscope-output.jpg
│   ├── ltspice-amplifier.jpg
│   └── ltspice-output.jpg
│
├── Simulation
│   └── LTspice Files
│
├── Project_Report.pdf
├── README.md
└── LICENSE
```

---

# 👨‍💻 Author

**Ahmed Samir**

Computer Systems Engineering Student

Faculty of Engineering and Applied Sciences

Nile University

GitHub: https://github.com/AhmedSamirNU

---

<p align="center">
⭐ If you found this project interesting, consider giving it a star!
</p>
