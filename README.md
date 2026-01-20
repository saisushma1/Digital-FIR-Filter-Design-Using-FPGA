# Digital-FIR-Filter-Design-Using-FPGA
This project implements a reconfigurable FIR filter on FPGA using Verilog. Filter coefficients are updated dynamically via UART without reprogramming the FPGA. The design is validated by comparing FPGA output with a Python reference model, demonstrating accurate real-time signal filtering performance.

## Abstract
FIR filters are widely used in digital signal processing due to their stability and linear phase response. This project implements a reconfigurable FIR filter on FPGA, where filter coefficients can be updated dynamically via UART communication without regenerating the FPGA bitstream. The design is validated by comparing FPGA output with a Python-based reference model, demonstrating accurate and reliable filtering performance.

## Key Features
- Reconfigurable FIR filter architecture  
- Dynamic coefficient update without FPGA reprogramming  
- UART-based USB serial communication  
- FPGA output verified against Python simulation  

## Tools & Technologies
- Verilog / VHDL  
- FPGA (Xilinx)  
- UART / USB Serial Interface  
- Python (signal generation and verification)  
- Vivado / ModelSim  

## Project Structure
.
├── constraints/        # FPGA constraints file
├── src/                # FIR filter and UART modules
├── images/             # Signal plots and frequency response
├── python/             # Signal generation and validation scripts
└── docs/               # Project documentation

## Status
Self-learning project  
AI-assisted documentation used

