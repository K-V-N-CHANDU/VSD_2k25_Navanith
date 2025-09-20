# 🚀 Week 0: VLSI System Design (VSD) – Tool Setup & Environment Configuration

Welcome to my VLSI System Design (VSD) Program repository!  
This week is focused on creating a reliable development environment using open-source EDA tools essential for synthesis, simulation, and waveform analysis.

---

### 🖥️ System & Virtual Machine Configuration

| **Operating System** | **RAM** | **Storage**     | **vCPUs** |
|----------------------|---------|-----------------|-----------|
| Ubuntu 24.04 🐧      | 6 GB 💾 | 50 GB HDD 💿    | 4 ⚡       |

💡 *This setup ensures smooth simulation and synthesis operations.*



---

## ⚙️ EDA Tool Installation & Verification

### 🧠 Yosys – RTL Synthesis Tool

**Purpose**: Yosys converts Verilog RTL code into gate-level netlists.

**Installation Steps**:
```bash
# Install dependencies
sudo apt-get update
sudo apt-get install build-essential clang bison flex \
libreadline-dev gawk tcl-dev libffi-dev git graphviz \
xdot pkg-config python3 libboost-system-dev \
libboost-python-dev libboost-filesystem-dev zlib1g-dev

# Clone, build, and install
git clone https://github.com/YosysHQ/yosys.git
cd yosys
make
sudo make install
```
## 📷 **Installation Verification**
<p align="center">
  <img src="https://github.com/K-V-N-CHANDU/VSD_2k25_Navanith/blob/Week0/yosys.jpg" 
       alt="Yosys Installed" width="600"/>
</p>

<div align="center">

✅ **Yosys Successfully Installed**

</div>
### 📟 **2. Iverilog – Verilog Simulator**

<details>
<summary><b>Purpose:</b> Compiles and simulates Verilog designs for functional verification.</summary>

Icarus Verilog is a Verilog simulation and synthesis tool that supports the IEEE-1364 Verilog HDL standard.

</details>

## **Iverilog Installation**
```bash
$ sudo apt-get install iverilog
```

## 📷 **Installation Verification**
<p align="center">
  <img src="https://github.com/K-V-N-CHANDU/VSD_2k25_Navanith/blob/Week0/iverilog.jpg" 
       alt="Iverilog Installed" width="600"/>
</p>

<div align="center">

✅ **Iverilog Successfully Installed**

</div>

---

### 📊 **3. GTKWave – Waveform Viewer**

<details>
<summary><b>Purpose:</b> Analyzes and visualizes simulation waveforms for debugging.</summary>

GTKWave is a fully featured GTK+ based wave viewer for Unix, Win32, and Mac OSX.

</details>

## **GTKWave Installation**
```bash
$ sudo apt update
$ sudo apt install gtkwave
```

## 📷 **Installation Verification**
<p align="center">
  <img src="https://github.com/K-V-N-CHANDU/VSD_2k25_Navanith/blob/Week0/gtkwave.jpg" 
       alt="GTKWave Installed" width="600"/>
</p>

<div align="center">

✅ **GTKWave Successfully Installed**

---

<div align="center">

### 🎉 Installation Summary

#### 🧠 **Yosys**  
**Status**: ✅ Complete  
**Primary Use**: RTL Synthesis  

#### 📟 **Iverilog**  
**Status**: ✅ Complete  
**Primary Use**: Verilog Simulation  

#### 📊 **GTKWave**  
**Status**: ✅ Complete  
**Primary Use**: Waveform Analysis  



### 🚀 Environment Ready for VLSI Design Journey!

<div align="center">
  
  **📂 Repository**: [VSD_2k25_Navanith](https://github.com/K-V-N-CHANDU/VSD_2k25_Navanith)  
  **👨‍💻 Author**: [K V N Chandu](https://github.com/K-V-N-CHANDU)  
  **📚 Program**: VLSI System Design (VSD)
</div>
