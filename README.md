# CMOE-Tutorials

Welcome to the **CMOE-Tutorials** repository! This repository hosts tutorials used and produced by researchers of the **[Computational Multiphysics in Offshore Engineering (CMOE)](https://tudelftcmoe.super.site/)** team at TU Delft.

## 🎯 Purpose

This repository provides comprehensive tutorials on PDE solvers for multiphysics problems with applications to offshore renewable energies. The tutorials are designed to help researchers, students, and practitioners learn and apply computational methods in the context of offshore engineering challenges.

## 📚 Content

The tutorials primarily focus on:

- **PDE Solvers**: Numerical methods for solving partial differential equations
- **Multiphysics Problems**: Coupled systems involving fluid dynamics, structural mechanics, heat transfer, and more
- **Offshore Renewable Energy Applications**: Wind turbines, wave energy converters, tidal energy systems, and floating solar platforms

## 🛠️ Main Tools

While the tutorials primarily use [**Gridap.jl**](https://github.com/gridap/Gridap.jl), a Julia library for grid-based approximation of PDEs, tutorials for other computational libraries will also be included as the repository grows.

### Gridap.jl

Gridap.jl is a powerful finite element library in Julia that provides:
- High-level abstractions for PDE discretization
- Support for complex geometries and adaptive meshes
- Efficient parallel computing capabilities
- Extensibility for custom physics and solvers

## 📂 Repository Structure

```
CMOE-Tutorials/
├── Gridap_tutorials/       # Tutorials using Gridap.jl
│   └── Tutorial_1.ipynb    # Itroduction to Gridap.jl - From Weak Form to Elemental Matrix and Vector
├── Project.toml            # Julia project dependencies
├── Manifest.toml           # Julia environment specification
└── README.md               # This file
```

## 🚀 Getting Started

### Prerequisites

To run the tutorials, you'll need:
- [Julia](https://julialang.org/downloads/) (version 1.6 or later recommended)
- [Jupyter](https://jupyter.org/install) or [IJulia](https://github.com/JuliaLang/IJulia.jl) for running notebooks

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/CMOE-TUDelft/CMOE-Tutorials.git
   cd CMOE-Tutorials
   ```

2. Start Julia in the repository directory:
   ```bash
   julia
   ```

3. Activate and instantiate the project environment:
   ```julia
   using Pkg
   Pkg.activate(".")
   Pkg.instantiate()
   ```

4. Launch Jupyter notebook:
   ```julia
   using IJulia
   notebook(dir=pwd())
   ```

## 📖 Tutorial Overview

### Gridap Tutorials

- **Tutorial 1: Introduction to Gridap.jl - From Weak Form to Elemental Matrix and Vector**  
  This tutorial explores the fundamentals of finite element assembly in Gridap.jl, going in depth into how weak formulations are transformed into elemental matrices and vectors before global assembly.

*More tutorials will be added regularly*

## 🤝 Contributing

We welcome contributions from the CMOE team and the broader research community! If you have a tutorial to share:

1. Fork the repository
2. Create a new branch for your tutorial
3. Add your tutorial with clear documentation
4. Submit a pull request

Please ensure your tutorials include:
- Clear explanations of the problem being solved
- Well-commented code
- Example outputs and visualizations
- References to relevant literature

## 📧 Contact

For questions or suggestions, please contact the CMOE team at TU Delft.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## 🙏 Acknowledgments

This work is supported by the Computational Multiphysics Offshore Engineering (CMOE) research group at TU Delft.

---

*Last updated: November 2025*
