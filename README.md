# High-Frequency Transformer (HFT) Design and Simulation for a 5 kW DAB Converter using ANSYS Maxwell

This repository presents the design, modelling, and transient simulation of a 5 kW High Frequency Transformer (HFT) intended for a Dual Active Bridge (DAB) converter operating at 100 kHz. The transformer was designed using the Area Product Method, implemented using an EE65 ferrite core (N87 material), and validated through finite-element simulations in ANSYS Maxwell. The work includes custom ferrite material creation, B-H curve implementation, Steinmetz core-loss modelling, open-circuit testing, and magnetic field validation.


## Design Specifications

| Parameter | Value |
|------------|------------| 
| Power Rating | 5 kW |
| Switching Frequency | 100 kHz |
| Core Type | EE65 (N87) |
| Primary Turns | 6 |
| Secondary Turns | 9 |
| Peak Flux Density | 0.2 T |

## Project Documentation

Presentation:

- [HFT ANSYS Maxwell Presentation](docs/HFT_ANSYS_Maxwell_Presentation.pdf)

  ## Skills Demonstrated

- High Frequency Transformer Design
- ANSYS Maxwell 3D
- Finite Element Analysis (FEA)
- Ferrite Core Modelling
- B-H Curve Implementation
- Steinmetz Core Loss Modelling
- Power Electronics
- DAB Converter Design

  ## Key Contributions

- Designed a 5 kW High Frequency Transformer
- Selected EE65 ferrite core using Area Product Method
- Created custom N87 ferrite material
- Imported nonlinear B-H characteristics
- Implemented Steinmetz core loss modelling
- Performed transient simulations in ANSYS Maxwell
- Validated peak flux density near 0.2 T

  ## Transformer Model

![Transformer Model](images/complete_transformer_model.png)

## Flux Distribution

![Flux Distribution](images/flux_distribution.png)
