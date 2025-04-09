# 5-Layer PCB Signal Integrity Optimization

> A signal integrity (SI) optimization project focused on reducing voltage ripple and impedance peaks in a 5-layer PCB using Cadence PowerSI and decoupling capacitor networks.

---

### 📌 **Project Overview**
- **Objective:** Identify and eliminate power/ground noise in a 5-layer PCB using Cadence PowerSI by placing optimized decoupling capacitors.
- **Methodology:** Imported PCB layout into PowerSI, ran Z-parameter simulation for impedance hotspots, and placed decoupling capacitors based on frequency-domain targets.

---

### 💡 **Key Features**
- Impedance peak suppression  
- 30% improvement in voltage fluctuation  
- Power network visualization  
- Schematic-to-layout closed loop  

---

### 🧰 **Skills Used**
PCB Simulation, Power Integrity, Capacitor Optimization, S-parameter modeling

---

### 🧪 **Technologies & Tools**
Cadence Allegro, PowerSI, PowerNet

---

### 🔍 **Key Findings**
Drastic drop in peak impedance at target frequencies; better voltage ripple control.

---

### 🎓 **What I Learned**
SI metrics interpretation, design of decap networks, layout-aware simulation challenges.

---

### 🚀 **Future Work**
Perform eye diagram analysis and integrate with high-speed SerDes signals.

---

### 📂 **Files Attached**
5layer_layout.brd, z_param_results.csv, PowerSI_Report.pdf
