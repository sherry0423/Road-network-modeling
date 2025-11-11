# 🦽 Road Network Modeling for Wheelchair Accessibility

This repository provides two core **Grasshopper battery files** —  
`zebra generation_final.gh`(zebra generation_try1/2/3 is process documentation) and `capture point offset.gh` — for the **systematic modeling of wheelchair-friendly non-motorized networks**.

---

## 📘 Overview

Urban renewal and accessibility design increasingly rely on **data-informed modeling** rather than manual measurement.  
This toolset automates two essential steps in the computational workflow for **wheelchair-accessible street network analysis**:

1. **Zebra Generation (`zebra generation.gh`)**  
   Generates zebra crossing systems by identifying intersection point subsets based on traversal distance thresholds, then constructing convex hulls within each subset—all derived from base street geometry to ensure logical connectivity and geometric consistency across intersections.

2. **Sampling Point Offset (`capture point offset_final.gh`)**  
   Accurately places and offsets sampling points along sidewalks and crossings, enabling precise spatial data extraction and accessibility measurement.

Together, these tools **replace traditional manual surveying** with a **high-efficiency computational process**, providing a reproducible foundation for accessibility analysis and simulation.

---

## 🧠 Key Features

- 🔹 **Automated pedestrian system generation** — Derives zebra crossings and continuous walkways from existing urban layouts.  
- 🔹 **Sampling precision** — Captures exact offset points for wheelchair trajectory or accessibility evaluation.  
- 🔹 **Flexible integration** — Works seamlessly with GIS or CAD-based input data within Grasshopper/Rhino environments.  
- 🔹 **Supports urban renewal workflows** — Designed for iterative optimization of accessible street designs.  

---

## 🛠 Requirements

- **Rhinoceros 7.0 or later**  
- **Grasshopper (built-in visual programming interface)**  
- Recommended plugins:  
  - *Human*  
  - *LunchBox*  
  - *pandasGH* (if used for data export)

---

## 🚀 Usage

1. Open Rhino and launch Grasshopper.  
2. Load either `.gh` file from this repository.  
3. Input your base street or sidewalk geometry.  
4. Adjust parameters (offset distance, connection tolerance, etc.) as needed.  
5. Bake or export results for further analysis.

