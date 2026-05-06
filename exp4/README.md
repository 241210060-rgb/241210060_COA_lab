# Experiment 04: Design of 8-bit Shift Register using Flip-Flops

---

## Objective

To design and simulate an 8-bit Shift Register using D flip-flops in Logisim and understand the sequential shifting of binary data using clock pulses.

---

## Background Study

A shift register is a sequential digital circuit used for storing and transferring binary data. It is built using flip-flops connected in series, where each flip-flop stores one bit.

In an 8-bit shift register:
- 8 flip-flops are connected sequentially  
- Each clock pulse shifts data from one stage to the next  
- Data movement occurs in a fixed direction (left or right)

When data is entered and retrieved serially, it is called a **Serial-In Serial-Out (SISO)** shift register.

Shift registers are widely used in:
- Data storage  
- Data transmission  
- Timing and synchronization systems  

---

## Circuit Description

The circuit was designed using D flip-flops in Logisim.

- Each flip-flop represents one bit  
- All flip-flops share a common clock signal  
- The output of one flip-flop is connected to the input of the next  
- Serial input is applied to the first flip-flop  

LEDs were connected to each output to visualize the shifting of data.

The circuit was tested by applying different input sequences and observing output changes with each clock pulse.

---

## Circuit Diagram

*(Insert your Logisim screenshot here)*

---

## Observations

- Data entered serially into the first flip-flop  
- With each clock pulse, data shifted to the next stage  
- LEDs displayed the movement of bits clearly  
- Multiple clock cycles were required for data to reach the final stage  

---

## Working Principle

Initially, all flip-flops are reset to zero.

- On applying input, the first flip-flop stores the data  
- On every clock pulse:
  - Data moves to the next flip-flop  
  - New input enters the first stage  

This process continues until data reaches the last stage, demonstrating sequential data transfer.

---

## Result

The 8-bit shift register was successfully implemented and simulated in Logisim. The output matched expected results, confirming correct data shifting behavior.

---

## Conclusion

This experiment helped in understanding:
- Working of shift registers  
- Role of clock signals in sequential circuits  
- Step-by-step data movement using flip-flops  

It provided practical insight into how data is stored and transferred in digital systems.

---
