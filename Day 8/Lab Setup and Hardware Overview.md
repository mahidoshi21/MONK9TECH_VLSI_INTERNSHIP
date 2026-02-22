# 💻 Lab Setup and Hardware Overview

## 💻 Lab Setup — Tool Installation

### 🔹 Git Installation

Git is used for **version control and project collaboration**. It helps track code changes and manage repositories.

Basic installation steps (Linux):

```bash
sudo apt update
sudo apt install git
```

Verify installation:

```bash
git --version
```

Common Git commands used in labs:

```bash
git clone <repository_url>
git status
git add .
git commit -m "message"
git push
```

---

### 🔹 IC Studio Installation

IC Studio (ICSTUDIO) is used for **ASIC / Physical Design lab environments**. It provides tools required for design visualization and chip implementation flows.

Typical setup steps in lab environments:

1. Load the environment setup file

```bash
source setup.csh
```

2. Launch IC Studio

```bash
icstudio &
```

This opens the graphical environment used for:

* Layout visualization
* Physical design flow interaction
* Library and design database management

---

## 🔌 Sonpapdi FPGA Board — Overview

The **Sonpapdi FPGA board** is used in training labs to demonstrate how digital designs interact with real hardware. It allows engineers and students to implement logic designs and test them directly on programmable hardware.

### Key Features

* FPGA-based programmable hardware platform
* Used for digital logic experimentation
* Supports RTL design testing
* Interfaces with switches, LEDs, and external IO

### Typical Learning Use Cases

* Understanding hardware implementation
* Testing simple RTL designs
* Observing signal behavior in real hardware
* Practicing FPGA programming workflows

## 🔌 Sonpapdi FPGA Board

The Sonpapdi FPGA board is used in lab sessions to understand how digital logic designs are implemented on programmable hardware.  
It allows students to test RTL designs and observe real hardware behavior.

![Sonpapdi FPGA Board](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTs0VivoKRZ-dAe7Qtey3kLAEbcl18MRbFBEQ&s)