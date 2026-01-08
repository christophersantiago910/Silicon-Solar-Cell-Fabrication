# Silicon-Solar-Cell-Fabrication and IV Characterization

## Overview
This project reports the fabrication and evaluation of **silicon-based solar cells**. The submitted report is included in this repository. 

Two devices were fabricated:
- A **control solar cell** using a provided photomask
- An **experimental solar cell** with modified front-contact geometry

The goal was to evaluate how front-side contact design influences photovoltaic efficiency.

## Fabrication Process
1. Spin-on phosphorus dopant diffusion (P-SOD)
2. Drive-in anneal (1000 °C)
3. Photolithography using AZ 5214-EIR positive photoresist
4. Aluminum contact deposition via thermal evaporation
5. Metal lift-off
6. Rapid thermal annealing (RTA)
7. IV characterization under dark and illuminated conditions

## Characterization
- Dark IV curves to evaluate diode behavior
- Illuminated IV curves (AM 1.5 equivalent setup)
- Extraction of:
  - Short-circuit current (I_SC)
  - Open-circuit voltage (V_OC)
  - Fill factor (FF)
  - Conversion efficiency (η)

## Key Results
| Device | Efficiency |
|------|-----------|
| Control solar cell | 3.07% |
| Experimental solar cell | 2.99% |

The experimental design unexpectedly showed reduced efficiency due to:
- Improper metal lift-off
- Photolithography overexposure
- Insufficient photoresist

## Analysis
- Junction depth calculated using diffusion equations
- IV curve behavior linked to fabrication defects
- Mask design trade-offs between shading losses and resistive losses
