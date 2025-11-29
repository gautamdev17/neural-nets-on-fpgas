# Neural Networks on FPGA (Verilog)

A from-scratch exploration of implementing neural network computation on FPGAs using Verilog.  
This repo builds the core blocks (MAC, neurons, layers) and experiments with dataflow, quantization, and hardware acceleration from first principles.

##  Goals
- Implement NN building blocks in Verilog  
- Learn fixed-point arithmetic & efficient dataflow  
- Build a small NN accelerator and test on FPGA  

##  Structure
- docs/ — notes, roadmap, first principles  
- src/verilog/ — MAC, neuron, layer modules  
- sim/ — testbenches  
- python/ — quantization & model tooling  

##  Status
Starting with first principles + MAC design.
