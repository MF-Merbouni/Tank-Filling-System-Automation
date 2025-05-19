# Tank-Filling-System-Automation
Simulation of an automated tank filling and draining system using Ladder Logic and Structured Text

> **Note**:This project simulates a basic **tank filling and draining system** using **PLC programming** in both **Structured Text (ST)** and **Ladder Logic (LD)**. It includes auto/manual modes, safety interlocks, and a simple HMI visualization.

---

## Features

-  Gradual tank filling using a pump
-  Manual and automatic control modes
-  Safety interlock to prevent simultaneous filling and draining
-  Alarm indication and full/empty level detection
-  Timer-based filling and draining with visual animation (HMI)
-  Value scaling for HMI height animation
-  Display of fill level as a percentage on screen


## Technologies Used

| Tool          | Purpose                               |
|---------------|----------------------------------------|
| **CODESYS**   | PLC programming and simulation         |
| **Structured Text** | Main logic implementation        |
| **Ladder Logic** | Alternative logic implementation    |
| **CODESYS Built-in Visualization** | Visualization of the process (HMI)|

---

## How It Works

- **In Auto Mode**: The tank fills automatically until full, then waits for a drain command.
- **In Manual Mode**: User controls pump and drain valve directly.
- **Safety Interlock**: Prevents pump and valve from running at the same time.
- **Timers**: Used to simulate gradual filling/draining.
- **HMI**: A rectangle shows water level; numerical percentage is displayed using a scaled value.
