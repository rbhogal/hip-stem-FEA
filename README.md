# Hip Stem FEA

Finite element analysis of a femoral hip stem implant, evaluating stress distribution under simulated physiological loading. Three cross-sectional stem geometries — elliptical, circular, and trapezoidal — are compared to assess the effect of cross-section shape on stress performance.

## Design

Dimensioned sketch showing key geometry and critical dimensions of the stem.

![Dimensioned sketch](images/sketch-dimensioned.png)

## 3D Model

![Hip stem render](images/render.png)

An interactive 3D model is also available as an STL file: [`model/hip-stem.stl`](model/hip-stem.stl). Open it directly in GitHub to rotate and inspect the geometry.

## Cross-Section Variants

Three stem cross-section geometries were modeled and analyzed for comparison:

| Circular | Elliptical | Trapezoidal |
|---|---|---|
| ![Elliptical cross-section](images/circular-hip-stem.png) | ![Circular cross-section](images/elliptical-hip-stem.png) | ![Trapezoidal cross-section](images/trapezoidal-hip-stem.png) |

## Loading & Boundary Conditions

Applied load and fixture/restraint locations used in the simulation.

![Load and boundary conditions](images/load-and-boundary-conditions.png)

*[Add a short note here on load magnitude/direction, e.g. "2600 N axial, simulating peak gait load"]*

## Stress Results

Von Mises stress distribution for each cross-section variant.

| Elliptical | Circular | Trapezoidal |
|---|---|---|
| ![Elliptical stress plot](images/stress-plot-elliptical.png) | ![Circular stress plot](images/stress-plot-circular.png) | ![Trapezoidal stress plot](images/stress-plot-trapezoidal.png) |

*[Add a short summary here — e.g. peak stress values, which geometry performed best, and why]*

## Repository Structure

```
hip-stem-FEA/
├── README.md
├── images/
│   ├── sketch-dimensioned.png
│   ├── render.png
│   ├── cross-section-elliptical.png
│   ├── cross-section-circular.png
│   ├── cross-section-trapezoidal.png
│   ├── load-and-boundary-conditions.png
│   ├── stress-plot-elliptical.png
│   ├── stress-plot-circular.png
│   └── stress-plot-trapezoidal.png
├── cad/
│   ├── hip-stem-elliptical.sldprt
│   ├── hip-stem-circular.sldprt
│   └── hip-stem-trapezoidal.sldprt
└── model/
    └── hip-stem.stl
```

## Software

- SolidWorks (part modeling)
- SolidWorks Simulation (FEA)
