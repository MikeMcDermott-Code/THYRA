# THYRA Framework

THYRA (Thermal-HYdraulic Reactor Analysis) is a reduced-order, multi-scale modelling framework for predictive thermal-hydraulic analysis of advanced reactor coolant systems.

The framework focuses on computationally efficient transient evaluation of coolant network behaviour across multiple spatial scales, with initial application to Water-Cooled Lithium-Lead (WCLL) blanket technology.

---

## Framework Structure

THYRA is currently organised into two principal modelling work packages corresponding to different spatial scales.

---

### 1. System-Level Modelling (0D / 1D)

A modular, network-based system code implemented in Modelica for transient thermal-hydraulic prediction.

**Work Package 1A – Blanket Scale (WCLL-TBM)**  
Reduced-order modelling and validation of the WCLL Test Blanket Module.

(Associated publication to be linked here.)

**Work Package 1B – Reactor / Plant Scale (EU-DEMO)**  
Extension of the system model toward tokamak-scale integration and plant-level transient analysis.

---

### 2. Cross-Sectional Conduction Modelling (1D / 2D) – SLICE

A cross-sectional conduction solver developed to resolve local temperature gradients and inform reduced-order closures within the system model.

SLICE supports multi-scale consistency through effective thermal resistance modelling and structural heat transfer characterisation.

---

## License

MIT License.
