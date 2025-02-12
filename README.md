# Digitally Assisted Low Dropout Regulator (DA-LDO)

## Overview  
This repository contains the *design, implementation, and analysis* of a *Digitally Assisted Low Dropout Regulator (DA-LDO). The DA-LDO enhances traditional LDOs by integrating a **hybrid analog-digital approach, providing **fast transient response, better power efficiency, and improved stability* across different technology nodes.

Link to the Reffered 

## Key Features  
- *Dual-loop architecture: Combines a **continuous-time analog loop* (Error Amplifier - EA) with an *event-driven digital loop*.  
- *Event-based digital assistance: Digital loop activates **only during load transients*, reducing steady-state power consumption.  
- *Fast transient response: Reduced **undershoot and overshoot* compared to conventional analog LDOs.  
- *Technology scalability: Optimized for **both low (≤65nm) and higher (130nm – 180nm) technology nodes*.  
- *Compact and efficient design*: Saves area and power compared to fully analog LDOs.  


## DA-LDO Architecture  


## Research Insights  
- DA-LDO was *first proposed for DRAM voltage regulation*, later adapted for SoCs.  
- Uses *event-based triggering instead of conventional PI control*.  
- Adaptive *digital calibration compensates for PVT variations*.  


## *Reference Research Paper:* 
- *[A Self-Triggered Digitally Assisted Hybrid LDO with 110 ns Settling Time in 65 nm CMOS](https://www.mdpi.com/2079-9292/12/15/3215)*

---
Guided by *Dr. Sakshi Arora*


 *Our Team:*  
- Eshwar Allampally 
- Harsh Verma
