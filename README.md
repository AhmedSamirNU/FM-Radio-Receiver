<p align="center">
  <img src="Images/final-project.jpeg" alt="FM Radio Receiver" width="600">
</p>

<h1 align="center">📻 FM Radio Receiver with Audio Amplification System</h1>

<p align="center">
An analog FM radio receiver designed, simulated, and implemented using discrete electronic components. The project demonstrates RF tuning, FM demodulation, audio amplification, and practical hardware implementation using both Breadboard and PCB.
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

This project presents the complete design, simulation, implementation, and testing of an **Analog FM Radio Receiver** capable of receiving commercial FM radio stations within the **88–108 MHz** frequency band.

The receiver consists of an RF reception stage, an LC resonant tuning circuit for station selection, an FM demodulation stage, an audio amplifier, a regulated power supply, and an 8Ω loudspeaker.

Before hardware implementation, the amplifier stage was simulated using **LTspice** to verify its performance and minimize design errors. The complete system was then assembled, tested, debugged, and validated on both **Breadboard** and **PCB**.

---

# ✨ Key Features

- 📡 FM Broadcast Reception (88–108 MHz)
- 🎚 Manual Frequency Tuning
- 📻 FM Signal Demodulation
- 🔊 Audio Amplification
- 🔈 8Ω Speaker Output
- 🧪 LTspice Simulation
- 🛠 Breadboard Prototype
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

# 📸 Hardware Gallery

<table>

<tr>

<td align="center">

<b>Final Prototype</b><br>

<img src="Images/final-project.jpeg" width="380">

</td>

<td align="center">

<b>Breadboard Implementation</b><br>

<img src="Images/breadboard-implementation.jpeg" width="380">

</td>

</tr>

<tr>

<td align="center">

<b>PCB Implementation</b><br>

<img src="Images/pcb-implementation.jpeg" width="380">

</td>

<td align="center">

<b>Power Supply</b><br>

<img src="Images/power-supply.jpeg" width="380">

</td>

</tr>

<tr>

<td colspan="2" align="center">

<b>Audio Amplifier</b><br>

<img src="Images/class-ab-amplifier.jpeg" width="450">

</td>

</tr>
# 🧪 LTspice Simulation

Before building the hardware, the amplifier stage was designed and verified using **LTspice**. Simulation helped validate circuit behavior, analyze the output waveform, and identify potential issues before physical implementation.

<table>

<tr>

<td align="center">

<b>Amplifier Circuit</b><br>

<img src="Images/ltspice-amplifier.jpeg" width="400">

</td>

<td align="center">

<b>Output Waveform</b><br>

<img src="Images/ltspice-output.jpeg" width="400">

</td>

</tr>

</table>

---

# 📊 Testing & Results

The completed system was experimentally tested after assembly to verify proper operation and evaluate the overall performance.

<p align="center">
<img src="Images/oscilloscope-output.jpeg" width="450">
</p>

### Testing Included

- ✅ RF signal reception
- ✅ Manual frequency tuning
- ✅ Audio signal verification
- ✅ Oscilloscope measurements
- ✅ Hardware debugging
- ✅ Noise reduction
- ✅ Power supply validation

---

# 🔩 Main Hardware Components

| Component | Function |
|-----------|----------|
| Antenna | Receives FM broadcast signals |
| LC Tank Circuit | Tunes the desired station |
| Variable Capacitor | Frequency adjustment |
| Audio Amplifier | Amplifies the recovered audio |
| 8Ω Speaker | Produces audible sound |
| Voltage Regulator | Provides a stable supply voltage |
| Battery | Powers the complete system |

---

# 🚀 Development Workflow

```text
Research
    │
    ▼
Component Selection
    │
    ▼
Circuit Design
    │
    ▼
LTspice Simulation
    │
    ▼
Breadboard Assembly
    │
    ▼
Hardware Debugging
    │
    ▼
PCB Implementation
    │
    ▼
Testing & Validation
```

---
# ⚠ Challenges

Throughout the implementation of this project, several practical engineering challenges were encountered during both simulation and hardware development. These challenges provided valuable hands-on experience in circuit analysis and troubleshooting.

- RF tuning sensitivity
- Signal instability during testing
- Breadboard parasitic capacitance
- Grounding and noise issues
- Component tolerance variations
- Coil optimization for stable tuning
- Hardware debugging and iterative testing

Each issue was addressed through repeated simulations, component replacement, practical measurements, and circuit optimization until stable operation was achieved.

---

# 💡 Skills Demonstrated

This project strengthened both theoretical knowledge and practical engineering skills in several areas:

- Analog Electronics
- Electronic Circuit Design
- RF Communication Fundamentals
- Audio Amplifier Design
- LTspice Circuit Simulation
- Breadboard Prototyping
- PCB Assembly
- Oscilloscope Measurements
- Circuit Debugging
- Hardware Troubleshooting
- Engineering Problem Solving

---

# 📈 Future Improvements

Several enhancements can further improve the overall performance of the system:

- Improve receiver sensitivity
- Enhance audio quality
- Design a compact custom PCB
- Implement automatic station tuning
- Add stereo FM decoding
- Improve antenna matching
- Reduce circuit noise and interference

---

# 🎯 Learning Outcomes

Through this project, we gained practical experience in designing, simulating, implementing, and testing analog electronic circuits. The project bridged theoretical concepts with real hardware implementation while improving our understanding of RF communication, audio amplification, measurement techniques, and systematic debugging.

---
# 🎥 Project Demonstration

Watch the complete demonstration of the system in action.

[![Demo Video](https://img.shields.io/badge/Demo-Watch%20Video-red?style=for-the-badge&logo=youtube)](https://drive.google.com/file/d/1h2xnaICsLna61kK0NpyrLvJ_sNMtKfjN/view?usp=drive_link) 
---

# 📁 Repository Structure

```text
FM-Radio-Receiver
│
├── Images
│   ├── final-project.jpeg
│   ├── breadboard-implementation.jpeg
│   ├── pcb-implementation.jpeg
│   ├── class-ab-amplifier.jpeg
│   ├── power-supply.jpeg
│   ├── oscilloscope-output.jpeg
│   ├── ltspice-amplifier.jpeg
│   └── ltspice-output.jpeg
│
├── Simulation
│   ├── FM_Receiver.asc
│   └── Amplifier.asc
│
├── Project_Report.pdf
├── README.md
└── LICENSE
```

---

# 📚 References

- Electronic Circuits II Course Material
- LTspice Simulation Software
- Component Datasheets
- FM Receiver Design References

---

# 👨‍💻 Author

<div align="center">

## Ahmed Samir

**Computer Systems Engineering Student**

Faculty of Engineering and Applied Sciences

Nile University

</div>

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

It helps support the project and makes it easier for others to discover.

</div>
</table>

---

<!-- ========================================================= -->
<!--                     END OF README                         -->
<!-- ========================================================= -->

## 🤝 Contributing

Suggestions, improvements, and feedback are always welcome.

If you have ideas to improve the project or optimize the circuit performance, feel free to open an Issue or submit a Pull Request.

---

## 📄 License

This project is intended for educational purposes.

Feel free to use or modify the design for learning and academic projects.

---

<p align="center">

### 📡 Designed & Implemented with Passion for Analog Electronics ❤️

</p>

<p align="center">

<img src="https://img.shields.io/github/stars/AhmedSamirNU/FM-Radio-Receiver?style=social">
<img src="https://img.shields.io/github/forks/AhmedSamirNU/FM-Radio-Receiver?style=social">

</p>
