# Experiment 02: Design of 4-bit Ripple Carry Adder and Propagation Delay Analysis

## Objective
To design and simulate a 4-bit Ripple Carry Adder (RCA) using basic logic gates in Logisim Evolution and analyze the propagation delay in carry generation.

---

## Background Study
A Ripple Carry Adder (RCA) is a combinational circuit used to add binary numbers.

It is built using multiple full adders connected in series:
- Each full adder adds two bits and a carry input
- Carry output of one stage becomes input of next stage

In a 4-bit RCA:
- 4 full adders are connected
- Carry propagates from LSB to MSB

### Drawback:
The main limitation is **propagation delay**, as each stage must wait for the previous carry.

---

## Circuit Description
The circuit consists of:
- 4 Full Adders
- Logic gates: AND, OR, XOR

Each stage:
- Takes Ai, Bi, and Carry-in
- Produces Sum and Carry-out

The carry-out is passed to the next stage, forming a ripple structure.

---

## Circuit Diagram

![Ripple Carry Adder](Lab_02.png)

---

## Files Included
- `lab2.circ` → Logisim circuit file  
- `Lab_02.png` → Circuit diagram screenshot  

---

## Observations
- Correct sum outputs were obtained for all inputs  
- Carry propagated sequentially through stages  
- Delay was observed in final output  

---

## Propagation Delay Analysis
- Delay increases with number of bits  
- Worst case: carry propagates through all 4 stages  
- Total delay = sum of delays of all full adders  

This makes RCA slower compared to advanced adders.

---

## Result
The 4-bit Ripple Carry Adder was successfully designed and verified using Logisim.

---

## Conclusion
This experiment demonstrated:
- Working of Ripple Carry Adder  
- Effect of carry propagation  
- Importance of faster adder designs  

---
