# THYRA Framework

THYRA (Thermal-HYdraulic Reactor Analysis) is a reduced-order, multi-scale modelling framework for predictive thermal-hydraulic analysis of advanced reactor coolant systems.

The framework focuses on computationally efficient transient evaluation of coolant network behaviour across multiple spatial scales, with initial application to Water-Cooled Lithium-Lead (WCLL) blanket technology.

---

## Framework Structure

THYRA is currently organised into two principal modelling work packages corresponding to different spatial scales.

### 1. THYRA-NET (0D/1D system network solver)
A modular, network-based system code implemented in Modelica for transient thermal-hydraulic prediction.

**Work Package 1A – Blanket Scale (WCLL-TBM)**  
Reduced-order modelling and validation of the WCLL Test Blanket Module.

(Associated publication to be linked here.)

**Work Package 1B – Reactor / Plant Scale (EU-DEMO)**  
Extension of the system model toward tokamak-scale integration and plant-level transient analysis.

---

### 2. THYRA-SLICE (1D/2D cross-sectional conduction solver)

A cross-sectional conduction solver developed to resolve local temperature gradients and inform reduced-order closures within the system model.

SLICE (Spatial Low-order Integrated Conduction Energy model) supports multi-scale consistency through effective thermal resistance modelling and structural heat transfer characterisation.

---

## License

MIT License.
