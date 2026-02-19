# THYRA Framework

THYRA (Thermal-HYdraulic Reactor Analysis) is a reduced-order, multi-scale modelling framework for predictive thermal-hydraulic analysis of fusion breeding blanket cooling systems.

The framework provides computationally efficient, engineering-scale evaluation of complex coolant architectures, with primary application to Water-Cooled Lithium-Lead (WCLL) blanket technology.

---

## Vision

THYRA bridges the gap between:

- High-fidelity CFD simulations (computationally expensive)
- Simplified lumped parameter approaches (insufficiently predictive)

The framework prioritises:

- Modular architecture
- Reduced-order physics closure
- Multi-scale modelling
- Robust transient capability
- Engineering design applicability

---

## Framework Structure

THYRA currently comprises two principal modelling levels:

### 1. System-Level Solver
A modular network-based system code implemented in Modelica for blanket-scale thermal-hydraulic prediction.

### 2. SLICE
A cross-sectional conduction solver used to inform reduced-order closures and effective thermal resistance modelling.

---

## Applications

- Fusion blanket thermal-hydraulics (WCLL focus)
- Water and liquid metal coolant systems
- Multi-scale reactor modelling research

---

## Development Status

Active research development.

Planned features include:

- Multi-scale coupling formalisation
- Validation benchmark suite
- Extended coolant physics modules

---

## License

MIT License.
