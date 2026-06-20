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

# High-Frequency Transformer (HFT) Design and Simulation for a 5 kW DAB Converter using ANSYS Maxwell

This repository presents the design, modelling, and transient simulation of a 5 kW High Frequency Transformer (HFT) intended for a Dual Active Bridge (DAB) converter operating at 100 kHz. The transformer was designed using the Area Product Method, implemented using an EE65 ferrite core (N87 material), and validated through finite-element simulations in ANSYS Maxwell.

---

## B-H Curve Implementation

A custom N87 ferrite material model was created in ANSYS Maxwell since the default material was unavailable. The nonlinear B-H characteristics were imported from the manufacturer's datasheet to accurately represent magnetic saturation and hysteresis behaviour of the ferrite core.

![B-H Curve](images/bh_curve.png)

---

## Transformer Core Geometry

The EE65 ferrite core geometry was modelled in ANSYS Maxwell according to the dimensions obtained from the transformer design calculations. The custom N87 material was assigned to the core for magnetic field and core-loss analysis.

![Transformer Geometry](images/transformer_geometry.png)

---

## Winding Geometry

Primary and secondary windings were modelled around the centre limb of the EE65 core. Copper conductors were assigned to the windings, and the number of turns was selected to satisfy the required voltage conversion ratio for the DAB converter application.

- Primary Turns: 6
- Secondary Turns: 9
- Winding Material: Copper

![Winding Geometry](images/winding_geometry.png)

---

## Complete Transformer Model

The complete transformer model consists of the EE65 ferrite core and the corresponding primary and secondary windings. This model was used for transient simulations under both sinusoidal and square-wave excitation conditions.

![Complete Transformer Model](images/complete_transformer_model.png)
