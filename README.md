# 🧩 GH_Suite: Geometry-Driven Structural Analysis and Optimization Framework

## Overview
**GH_Suite** is a modular computational framework developed in Rhino–Grasshopper for integrating **parametric modeling**, **finite element analysis (FEM)**, and **optimization** within a unified workflow.

The framework is designed to bridge the gap between **architectural design exploration** and **structural reasoning**, enabling designers to evaluate structural performance directly within parametric modeling environments.

---

## 🔄 Workflow Concept

The system follows a closed-loop workflow:
    Geometry → FEM → Performance → Optimization → Geometry

    
- **Geometry**: Parametric definition of structural form  
- **FEM**: Structural analysis based on geometric input  
- **Performance**: Evaluation (e.g., displacement, strain energy)  
- **Optimization**: Design update based on performance  

This loop enables **continuous performance-driven design exploration**.

---

## 🧱 Structural Modules

### 1. Truss Module
- 3D truss analysis  
- Axial force behavior  
- Lightweight structural systems  

📄 Documentation:  
https://frequent-beluga-27a.notion.site/3D-TRUSS-Finite-Element-Method-Rhino-Grasshopper-290171f044c780c3a365e9377dfbafb9

---

### 2. Frame Module
- 3D frame analysis  
- Axial, bending, and shear behavior  
- Suitable for building-scale structures  

📄 Documentation:  
https://frequent-beluga-27a.notion.site/3D-FRAME-Finite-Element-Method-Rhino-Grasshopper-290171f044c780818313e24a8454d713

---

### 3. Shell Module
- Triangular shell FEM  
- Membrane and bending behavior  
- Suitable for complex surface structures  

📄 Documentation:  
https://frequent-beluga-27a.notion.site/Triangular-Shell-Finite-Element-Method-Rhino-Grasshopper-290171f044c7803a9dacd85032fcd0a6

---

## ⚙️ Key Features

- **Geometry-driven input**  
  Structural models are defined directly using points, lines, and meshes  

- **Unified input–output structure**  
  Same workflow for truss, frame, and shell systems  

- **Optimization-ready outputs**  
  Direct access to:
  - Displacement  
  - Strain energy  
  - Other performance metrics  

- **Seamless Grasshopper integration**  
  Compatible with tools such as:
  - Galapagos  
  - Wallacei  
  - Custom optimization scripts  

- **Low learning curve**  
  Designed for architects and students with minimal programming experience  

---

## 🎓 Applications

- Architectural design studios  
- Performance-based design exploration  
- Structural optimization workflows  
- Research in architecture × structure × computation  

---

## 📊 Example Use Cases

- Pavilion optimization (truss / shell)  
- Frame structure refinement  
- Multi-objective design (e.g., strain energy vs span)  
- Integration with evolutionary solvers  

---

## ⚠️ Limitations

- Linear elastic analysis only  
- Simplified structural assumptions  
- Not intended for detailed engineering validation  
- Focused on early-stage design exploration  

---

## 🔬 Research Context

This framework is developed as part of ongoing research in:

> **Architecture × Structure × AI**  
> *(Form – Performance – Data integration)*

It supports the development of:
- Performance-aware generative design  
- Structural optimization workflows  
- Future integration with machine learning models  

---

## 📌 Future Development

- Nonlinear analysis  
- Multi-objective optimization integration  
- Data-driven / ML-based structural prediction  
- Graph-based structural representation  

---

## 👤 Author

**Chi-tathon Kupwiwat**  
Faculty of Architecture  
Chulalongkorn University, Thailand  

---

## 📄 Related Publication

*A Modular Framework for Integrating Parametric Modeling, Structural Analysis, and Optimization in Architectural Design*
