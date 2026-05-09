# Experiment 4: Design of 8-bit Shift Register using Flip-Flops

---

# Objective

The objective of this experiment is to design and simulate an 8-bit Shift Register using D flip-flops in Logisim and to study the sequential shifting of binary data. This experiment helps in understanding how data is stored and transferred step-by-step using clock pulses in a sequential circuit.

---

# Background Study

A shift register is a type of sequential circuit used for storing and transferring binary data. It is constructed using flip-flops connected in series, where each flip-flop stores one bit of information.

The output of one flip-flop is connected to the input of the next, forming a chain-like structure.

In an 8-bit shift register, eight flip-flops are used to store 8 bits of data. The data is shifted either to the left or right depending on the design. With each clock pulse, the data moves one position forward. This type of operation is commonly referred to as Serial-In Serial-Out (SISO) when both input and output are serial.

Shift registers are widely used in digital systems for:

- Data storage
- Data transfer
- Timing applications
- Serial communication
- Digital signal processing

---

# Circuit Description

In this experiment, an 8-bit Shift Register was implemented using D flip-flops.

- Each flip-flop represents one stage of the register.
- A common clock signal was connected to all flip-flops for synchronized operation.
- The serial input was applied to the first flip-flop.
- The output of each flip-flop was connected to the input of the next stage.
- LEDs were connected to outputs to visualize data movement.

The circuit was simulated in Logisim using different binary input sequences. The movement of data from one stage to another was observed with each clock pulse.

---

# Components Used

- 8 × D Flip-Flops
- Clock Signal
- Input Pin (Serial Input)
- LED Output Pins
- Wiring Tools
- Logisim Evolution

---

# Procedure

1. Open Logisim Evolution.
2. Create a new project.
3. Place 8 D flip-flops on the workspace.
4. Connect the output of each flip-flop to the input of the next flip-flop.
5. Connect a common clock signal to all flip-flops.
6. Add a serial input to the first flip-flop.
7. Connect LEDs to all outputs for visualization.
8. Simulate the circuit by applying different binary inputs.
9. Observe the shifting of data with each clock pulse.

---

# Working Principle

The shift register operates based on clock pulses.

- Initially, all flip-flops are set to zero.
- When binary input is applied, it is stored in the first flip-flop.
- On each clock pulse, the stored data shifts to the next stage.
- Simultaneously, new input data enters the first stage.

This process continues until the data reaches the final flip-flop, enabling controlled storage and transfer of binary information.

---

# Data Shifting Process

```text
Input Bit → FF1 → FF2 → FF3 → FF4 → FF5 → FF6 → FF7 → FF8
