# Automatic Washing Machine Controller (Verilog HDL)

A Finite State Machine (FSM) based controller model for an automatic washing machine, designed and tested using Verilog HDL.

## 🛠️ Tech Stack & Tools
* **Language:** Verilog HDL (SystemVerilog)
* **Tools:** EDA Playground, EPWave

## 📋 Features & State Transitions
The controller manages the sequential operations of an automated washing system through defined states:
* `check_door` $\rightarrow$ Validates safety interlocks.
* `fill_water` & `add_detergent` $\rightarrow$ Prepares the wash cycle.
* `load_clothes` $\rightarrow$ Initiates the main cycle.
* `cycle` / `drain_water` / `spin` $\rightarrow$ Executes wash, rinsing, and water evacuation stages.

## 🚀 How to Run
1. Open [EDA Playground](https://www.edaplayground.com/).
2. Copy the contents of `design.sv` into the **Design** panel.
3. Copy the contents of `testbench.sv` into the **Testbench** panel.
4. Run the simulation to observe state changes and testbench wave transitions.
