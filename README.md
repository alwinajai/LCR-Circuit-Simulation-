🔁 LCR Circuit Simulation using Falstad Circuit Simulator

This project demonstrates a basic **LCR (Inductor–Capacitor–Resistor)** circuit simulation using the **Falstad Circuit Simulator**, focusing on the transient and steady-state behavior of AC circuits. It utilizes fundamental electronic components such as an **AC voltage source**, **inductor**, **capacitor**, **resistor**, **ground**, and **conductive wires**. The simulation visually illustrates how current and voltage behave over time in an LCR system.


🔧 Components Used

- AC Voltage Source
- Resistor (R)
- Inductor (L)
- Capacitor (C)
- Ground
- Conductor/Wire


⚙️ Circuit Design Overview

The LCR circuit is constructed in a **series configuration** using the following layout:
AC Source (+) → Resistor → Inductor → Capacitor → Ground → AC Source (-)

▶️ How to Simulate

1. Visit [Falstad Circuit Simulator] https://falstad.com/circuit/
2. Click **"File" > "New Circuit"**.
3. Add components:
   - AC Voltage Source (5V, 50Hz suggested)
   - Resistor (100 Ω)
   - Inductor (0.2 H)
   - Capacitor (100 µF)
4. Connect components in series using wires.
5. Attach a ground connection below the capacitor.
6. Press "Run / Simulate" to begin the simulation.

📈 Simulation Observations
- Observe voltage and current across the resistor, inductor, and capacitor.
- Vary the AC source frequency to study resonance behavior.
- At the **resonant frequency**, the impedance is minimized and current is maximized.
- Use the **oscilloscope view** to see phase differences and waveform characteristics.

💡 Key Concepts
- **LCR Circuit**: A second-order reactive circuit with unique behavior in AC systems.
- **Resonance**: The point at which inductive and capacitive reactance cancel out.
- **Impedance**: Frequency-dependent opposition to current.
- **Phase Shift**: Difference in phase between voltage and current waveforms.
- **Damping**: The effect of the resistor on reducing oscillations.

🎓Learning Outcomes
By completing this simulation, you will:
- Understand the structure and behavior of a series LCR circuit.
- Visualize resonance, impedance, and phase relationships.
- Analyze transient and steady-state responses.
- Develop familiarity with Falstad’s Circuit Simulator interface.

📝 Notes
- This is a beginner-friendly circuit for those new to electronics or circuit simulation.
- Changing component values lets you explore different types of damping and resonance behavior.
- You can also export the circuit as a `.txt` file from Falstad and save it in this repository.

