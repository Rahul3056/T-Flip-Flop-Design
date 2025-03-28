### T Flip-Flop Design**  

#### **Concept Overview**  
A **T Flip-Flop (Toggle Flip-Flop)** is a special case of the JK Flip-Flop where both **J and K inputs are tied together** to form a single **T (Toggle) input**. It is mainly used in **counters, frequency dividers, and sequential circuits** due to its toggling nature.  

#### **Detailed Explanation**  
- **T = 0:** No change (Hold State).  
- **T = 1:** Toggle (Invert **Q** at each clock pulse).  

- **Boolean Expression:**  
  - `Q(next) = T(Q') + T'(Q)`  
  - `Q(next) = Q ⊕ T`  

#### **Truth Table**  

| Clock | T | Q (Next State) |
|-------|---|--------------|
| ↑     | 0 | Q (Hold)    |
| ↑     | 1 | Q' (Toggle) |

#### **Applications**  
T Flip-Flops are primarily used in **binary counters**, **frequency division circuits**, and **state machines**.  

#### **Execution Steps**  
1. Open **QuestaSim, ModelSim, Xilinx ISE, or Vivado**.  
2. Write the **T Flip-Flop Verilog code**.  
3. Write a **testbench** to verify its operation.  
4. Simulate and check the **waveform or console output**.  

#### **Real-World Example for Practice**  
Design a **4-bit asynchronous counter** using T Flip-Flops and simulate its behavior.   

#### **Further Enhancements**  
Modify the design to support **synchronous and asynchronous reset**. Implement a **T-based counter circuit** using multiple T Flip-Flops.
