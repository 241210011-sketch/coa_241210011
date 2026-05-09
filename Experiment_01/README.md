# Implementation of Basic Logic Circuits using Logisim

## Objective

The objective of this experiment is to understand and implement basic digital logic circuits using Logisim Evolution. The experiment focuses on designing and simulating fundamental components such as multiplexers, priority encoders, and combinational logic circuits.

---

# Background Study

Digital logic circuits form the backbone of computer architecture and are used to perform logical operations on binary inputs. Basic components such as AND, OR, and NOT gates are combined to form more complex circuits like multiplexers and encoders.

A Multiplexer (MUX) is a combinational circuit that selects one input from multiple inputs based on select lines and forwards it to the output. A priority encoder is used to encode multiple inputs into a binary format while giving priority to the highest-order input.

Logisim Evolution is a digital circuit simulation tool that allows users to design, test, and analyze digital circuits visually. It provides a user-friendly interface where components can be connected and their behavior can be observed in real-time.

---

# Experiment Description

In this experiment, various digital circuits were designed and simulated using Logisim Evolution.

## 1. 8:1 Multiplexer

An 8:1 multiplexer was implemented to select one input among eight inputs using select lines.

### Components Used

- Input Pins
- Multiplexer
- Select Lines
- Output Pin

### Working

The select lines determine which input is connected to the output. By changing the select line values, different inputs were observed at the output.

---

## 2. Hierarchical Multiplexer Design

A hierarchical multiplexer design was created to efficiently handle multiple input lines using smaller multiplexers combined together.

### Components Used

- Multiple 2:1 or 4:1 Multiplexers
- Input Pins
- Select Lines
- Output Pin

### Working

Smaller multiplexers were interconnected to create a larger multiplexer structure. This demonstrated modular circuit design.

---

## 3. 8:3 Priority Encoder

An 8:3 priority encoder circuit was designed to convert multiple input signals into a binary coded output while giving priority to the highest-order input.

### Components Used

- Input Pins
- OR Gates
- Encoder Logic
- Output Pins

### Working

When multiple inputs were active simultaneously, the encoder generated the binary code corresponding to the highest-priority input.

---

## 4. Combinational Logic Circuits

Basic combinational logic circuits using OR gates were implemented to understand signal flow and logical operations.

### Components Used

- OR Gates
- Input Pins
- Output Pins

### Working

Different combinations of inputs were tested, and the corresponding outputs were verified according to OR gate truth tables.

---

# Procedure

1. Open Logisim Evolution.
2. Create a new project.
3. Add required components from the toolbar.
4. Design the circuits according to the required logic.
5. Connect all components properly using wiring tools.
6. Simulate the circuit by changing input values.
7. Observe and verify the outputs.

---

# Observations

The simulation results showed that:

- The multiplexers correctly selected inputs based on the select lines.
- The priority encoder produced the expected binary output corresponding to the highest-priority input.
- The combinational logic circuits responded accurately to different input combinations.
- The outputs changed correctly during simulation.

This confirmed the correctness of the designed circuits.

---

# Result

The experiment was successfully completed, and the designed circuits were verified using Logisim Evolution. The behavior of multiplexers, priority encoders, and combinational logic gates was clearly understood through simulation.

---

# Conclusion

This experiment provided practical exposure to designing and simulating digital logic circuits using Logisim Evolution. It reinforced the theoretical concepts of logic gates, multiplexers, and encoders, and demonstrated how complex digital systems can be built using simple components. The use of simulation tools made it easier to visualize and verify circuit behavior effectively.

---

# Applications

- Digital Communication Systems
- Computer Architecture
- Data Routing
- Signal Processing
- Processor Design
- Memory Selection Circuits

---

# Tools Used

- Logisim Evolution
- Digital Logic Components
- Simulation Environment
