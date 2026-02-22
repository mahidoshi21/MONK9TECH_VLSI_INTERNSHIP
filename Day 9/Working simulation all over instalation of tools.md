# 💻 VLSI Lab Setup and Simulation Verification

This document explains how to verify the working environment after installing the required tools such as **Git**, **IC Studio**, and the lab simulation environment.  
The purpose is to confirm that the installation is successful and that simulations can run correctly.

---

## ▶️ Working Simulation After Tool Installation

After installing all required tools such as **Git**, **IC Studio**, and the lab environment, the next step is to verify the setup by running a **basic simulation**.  
This ensures that the tools, libraries, and environment variables are configured correctly.

---

## 🎯 Purpose

The working simulation step helps to:

- Verify that the **EDA tools are installed correctly**
- Confirm that **environment variables and libraries are loaded**
- Ensure that the **simulation flow runs without errors**
- Validate that the **design files can be compiled and executed**

---

## ⚙️ Basic Simulation Flow

### 1️⃣ Load the Tool Environment

```bash
source setup.csh

This command loads the required tool paths and environment variables.

2️⃣ Navigate to the Project Directory
cd project_directory

This moves to the directory containing the design and testbench files.

3️⃣ Compile the Design
vlog design.v
vlog testbench.v

This step compiles the Verilog design and testbench files.

4️⃣ Run the Simulation
vsim testbench

The simulator executes the design and prepares the simulation environment.

5️⃣ View Waveform Results
add wave *
run -all

Waveforms allow you to observe signal transitions and verify that the circuit behaves as expected.

📊 Expected Output

After running the simulation:

The design compiles without errors

The simulation runs successfully

Waveforms display correct signal transitions

Output signals match the expected functionality
```
