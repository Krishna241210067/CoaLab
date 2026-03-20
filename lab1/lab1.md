# Experiment 1  

## Design and Simulation of Multiplexer and Priority Encoder using Logisim  

---

## Objective  

The objective of this experiment is to design and simulate fundamental combinational circuits, namely a multiplexer and a priority encoder, using Logisim Evolution. The purpose is to understand how data selection and encoding operations are performed in digital systems.

---

## Background Study  

Combinational logic circuits are essential building blocks in digital electronics, as their outputs depend solely on present input values. Among these, multiplexers and encoders are widely used for data handling and signal processing.

A multiplexer (MUX) is a device that selects one input from multiple input lines and forwards it to a single output line based on select signals. It is commonly used in communication systems and data routing applications.

A priority encoder is a combinational circuit that converts multiple input signals into a binary code. It assigns priority to inputs, meaning that if multiple inputs are active simultaneously, the highest-priority input is encoded in the output.

Logisim Evolution is a simulation tool that enables users to construct digital circuits graphically, test their functionality, and analyze outputs interactively, making it ideal for learning and experimentation.

---

## Experiment Description  

In this experiment, an 8-to-1 multiplexer was designed and implemented in Logisim to select one of the eight input signals using three select lines. A hierarchical design approach was also explored to efficiently manage multiple inputs.

Additionally, an 8-to-3 priority encoder was constructed to convert multiple input lines into a corresponding binary output, ensuring that higher-order inputs were given precedence.

The circuits were tested by applying different input combinations and observing the outputs. The functionality of both circuits was verified through simulation.

---

## Circuit Diagram  

[Multiplexer and Encoder Design](https://github.com/Krishna241210067/CoaLab/blob/main/lab1/image.png)  

---

## Observations  

The simulation results confirmed that the multiplexer correctly routed the selected input to the output based on the select lines.  

The priority encoder successfully generated the correct binary code corresponding to the highest-priority active input.  

All circuits responded accurately to varying input conditions, demonstrating correct logical behavior.

---

## Result  

The multiplexer and priority encoder circuits were successfully designed and simulated using Logisim. The outputs matched the expected results for all tested input combinations, validating the correctness of the implementations.

---

## Conclusion  

This experiment provided practical exposure to designing key combinational circuits such as multiplexers and priority encoders. It reinforced the theoretical understanding of data selection and encoding mechanisms. The use of Logisim simplified the design process and allowed easy verification of circuit behavior, strengthening the fundamentals of digital logic design.

---
