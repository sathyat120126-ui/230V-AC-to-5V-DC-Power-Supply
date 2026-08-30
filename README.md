# 230V AC to 5V DC Power Supply

## 📌 Project Overview

This project presents the design and analysis of a regulated power supply that converts **230V AC, 50Hz mains voltage into a stable 5V DC output**.

The proposed system uses an isolated step-down transformer, bridge rectifier, smoothing capacitor, and LM7805 voltage regulator.

## 🎯 Objective

To design, simulate, and analyze a 230V AC to 5V DC power supply and evaluate its:

* Voltage conversion
* Rectification
* Filtering
* Voltage regulation
* Ripple voltage
* Load performance
* Regulator power dissipation

## ⚡ Circuit Stages

```text
230V AC
   ↓
Step-Down Transformer
230V / 9V
   ↓
Bridge Rectifier
4 × 1N4007
   ↓
Filter Capacitor
1000µF
   ↓
LM7805 Voltage Regulator
   ↓
5V DC Output
   ↓
Load
```

## 🔧 Components

| Component         | Specification    |
| ----------------- | ---------------- |
| Transformer       | 230V / 9V AC, 1A |
| Rectifier         | 4 × 1N4007       |
| Filter Capacitor  | 1000µF / 25V     |
| Voltage Regulator | LM7805           |
| Input Capacitor   | 0.33µF           |
| Output Capacitor  | 0.1µF            |
| Load              | 50Ω              |
| Output            | 5V DC            |

## 📊 Expected Performance

At approximately **100mA load**:

* Transformer secondary: **9V RMS AC**
* Secondary peak voltage: **12.73V**
* Bridge rectifier peak: approximately **11.33V**
* Rectifier ripple frequency: **100Hz**
* Filter capacitor: **1000µF**
* Output voltage: approximately **5V DC**
* Load resistance: **50Ω**
* Load current: approximately **100mA**

## 📈 Simulation

The simulation analyzes:

1. Transformer secondary waveform
2. Full-wave rectified waveform
3. Filtered DC waveform
4. Regulated 5V output
5. Capacitor ripple
6. Output performance under load

## 📁 Project Files

* `Documentation/` – Detailed project report
  

## 🛡️ Safety

This project involves **230V AC mains voltage**. Actual hardware implementation must use proper isolation, fuse protection, insulation, enclosure, earthing and appropriate laboratory safety procedures. The mains side must not be handled on a breadboard.

## 👩‍💻 Author

**Sathya**

Electrical & Electronics Engineering / Engineering Student

## 📜 License

This project is intended for educational and academic purposes.

