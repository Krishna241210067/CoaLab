# Experiment 2  

## Design and Implementation of Ripple Carry Adder using Basic Logic Gates  

---

## Objective  

The aim of this experiment is to design and simulate a Ripple Carry Adder (RCA) using fundamental logic gates such as AND, OR, and NOT in Logisim Evolution. The goal is to analyze how binary addition is performed at the hardware level and to observe the propagation of carry across multiple stages.

---

## Background Study  

In digital systems, arithmetic operations are carried out using combinational circuits. One of the most essential arithmetic circuits is the adder, which performs binary addition. A Ripple Carry Adder is constructed by connecting multiple full adders in series, where the carry output of one stage becomes the carry input of the next stage.

Each full adder can be built using basic logic gates. It takes three inputs—two significant bits and a carry-in—and produces a sum and carry-out. The term “ripple” refers to the way the carry propagates sequentially through each stage, which introduces a delay proportional to the number of bits.

Logisim Evolution provides a convenient platform to design such circuits by allowing users to assemble gates, connect them logically, and simulate real-time behavior for verification.

---

## Experiment Description  

In this experiment, a Ripple Carry Adder was constructed by first designing a full adder circuit using AND, OR, and NOT gates. Multiple full adder units were then cascaded to create a multi-bit adder.

The circuit was implemented in Logisim, where each stage handled one bit of the input numbers. The carry output from each stage was connected to the next stage, forming a chain-like structure. Various input combinations were applied to test the correctness of sum and carry outputs.

The behavior of the circuit was carefully analyzed by observing how the carry propagated through each stage, especially in cases involving multiple consecutive carry generations.

---

## Circuit Diagram  

[Ripple Carry Adder Design](https://github.com/Krishna241210067/CoaLab/blob/main/lab2/image.png)  

---

## Observations  

The simulation confirmed that the Ripple Carry Adder produced accurate results for all tested input combinations. It was observed that the sum output at each stage depended not only on the input bits but also on the incoming carry.  

A noticeable delay in output was observed as the carry signal propagated sequentially through each full adder stage, demonstrating the inherent limitation of ripple carry adders.

---

## Result  

The Ripple Carry Adder was successfully designed and verified using basic logic gates in Logisim. The circuit correctly performed binary addition, and the propagation of carry across stages was clearly observed. This validated the working principle of multi-bit addition using combinational logic.

---

## Conclusion  

This experiment provided hands-on experience in constructing arithmetic circuits from basic gates. It enhanced the understanding of how full adders are combined to form a Ripple Carry Adder and highlighted the concept of carry propagation delay. The use of Logisim made it easier to design, simulate, and analyze the circuit effectively, strengthening the foundation of digital logic design.

---
