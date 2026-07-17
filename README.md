<p align="center">
  <img src="Images/final-project.jpg" alt="FM Radio Receiver" width="900"/>
</p>

<h1 align="center">📻 FM Radio Receiver with Audio Amplification System</h1>

<p align="center">
An Analog FM Radio Receiver capable of receiving commercial FM broadcasts (88–108 MHz), featuring RF tuning, FM demodulation, Class AB audio amplification, LTspice simulation, and practical implementation on Breadboard and PCB.
</p>

<p align="center">

![Project](https://img.shields.io/badge/Project-Analog%20Electronics-blue?style=for-the-badge)
![Simulation](https://img.shields.io/badge/LTspice-Simulated-red?style=for-the-badge)
![Hardware](https://img.shields.io/badge/Hardware-Tested-success?style=for-the-badge)
![PCB](https://img.shields.io/badge/Prototype-Breadboard%20%26%20PCB-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge)

</p>

---

# 📖 Overview

This project presents the design, simulation, implementation, and testing of an **Analog FM Radio Receiver** capable of receiving commercial FM stations within the **88–108 MHz** band.

The receiver uses an **LC resonant tuning circuit** to select the desired station, followed by an FM demodulation stage to recover the audio signal. The recovered signal is amplified using an **LM386 Class AB audio amplifier** to drive an **8Ω loudspeaker**.

The project was first verified using **LTspice simulation**, then implemented on a **breadboard**, and finally assembled on a **PCB** after hardware validation.

---

# ✨ Key Features

- 📡 FM Broadcast Reception (88–108 MHz)
- 🎚 Manual Frequency Tuning
- 📶 RF Signal Reception
- 📻 FM Signal Demodulation
- 🔊 LM386 Class AB Audio Amplifier
- 🔈 8Ω Speaker Output
- 🧪 LTspice Simulation
- 🛠 Breadboard Prototype
- 💻 PCB Implementation
- 📈 Oscilloscope Verification

---

# 🏗 System Architecture

```text
             Antenna
                │
                ▼
        RF Receiver Stage
                │
                ▼
      LC Resonant Tuning
                │
                ▼
      FM Demodulation Stage
                │
                ▼
 LM386 Class AB Audio Amplifier
                │
                ▼
          8Ω Speaker
```

---

# 📷 Project Gallery

## Final Prototype

<p align="center">
<img src="Images/final-project.jpg" width="800"/>
</p>

---

## Breadboard Implementation

<p align="center">
<img src="Images/breadboard-implementation.jpg" width="800"/>
</p>

---

## PCB Implementation

<p align="center">
<img src="Images/pcb-implementation.jpg" width="800"/>
</p>

---

## Audio Amplifier

<p align="center">
<img src="Images/class-ab-amplifier.jpg" width="800"/>
</p>

---

## Power Supply

<p align="center">
<img src="Images/power-supply.jpg" width="800"/>
</p>

---

# 🧪 LTspice Simulation

### Audio Amplifier

<p align="center">
<img src="Images/ltspice-amplifier.jpg" width="750"/>
</p>

### Output Waveform

<p align="center">
<img src="Images/ltspice-output.jpg" width="750"/>
</p>

The amplifier stage was simulated using LTspice to verify signal amplification before practical implementation.

---

# 📊 Testing

## Oscilloscope Output

<p align="center">
<img src="Images/oscilloscope-output.jpg" width="750"/>
</p>

The completed hardware was tested through:

- Audio signal verification
- Oscilloscope measurements
- Hardware debugging
- Frequency tuning
- Grounding optimization
- Noise reduction

---

# 🔩 Main Hardware Components

| Component | Function |
|------------|----------|
| LM386 | Audio Power Amplifier |
| BC547 / BC557 | Signal Amplification |
| Variable Capacitor | Frequency Tuning |
| Inductors | LC Resonance |
| Capacitors | Filtering & Coupling |
| Resistors | Biasing Network |
| 8Ω Speaker | Audio Output |
| Antenna | FM Signal Reception |
| L7805 | Voltage Regulation |
| 9V Battery | Power Supply |

---

# 🚀 Engineering Workflow

```text
Research
      ↓
Circuit Design
      ↓
LTspice Simulation
      ↓
Breadboard Implementation
      ↓
Hardware Debugging
      ↓
PCB Assembly
      ↓
Testing & Optimization
```

---

# ⚠ Engineering Challenges

- RF tuning sensitivity
- LC coil optimization
- Breadboard parasitic capacitance
- Noise coupling
- Grounding issues
- Component tolerances
- Signal stability

---

# 💡 Skills Demonstrated

- Analog Electronics
- RF Circuit Design
- Audio Amplifier Design
- LTspice Simulation
- Breadboard Prototyping
- PCB Assembly
- Oscilloscope Measurements
- Hardware Debugging
- Circuit Testing
- Electronic Troubleshooting

---

# 📈 Future Improvements

- Improve receiver sensitivity
- Automatic station tuning
- Stereo FM decoding
- Custom PCB optimization
- Better antenna matching
- Enhanced audio quality

---

# 🎥 Project Demonstration

🎬 **Project Video**

**Google Drive:**

https://drive.google.com/file/d/1h2xnaICsLna61kK0NpyrLvJ_sNMtKfjN/view

---

# 📂 Repository Structure

```text
FM-Radio-Receiver
│
├── Images
├── Simulation
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

GitHub:
https://github.com/AhmedSamirNU

---

<p align="center">

⭐ If you found this project helpful, consider giving it a Star!

</p>
