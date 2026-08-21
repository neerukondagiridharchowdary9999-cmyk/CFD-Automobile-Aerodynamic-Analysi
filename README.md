# Numerical Analysis of Aerodynamic Performance of a Scaled Automobile Using ANSYS Fluent

## 📌 Project Overview

This project presents a **Computational Fluid Dynamics (CFD) analysis of a 1:10 scaled passenger car model** using **ANSYS Fluent**. The objective is to study the aerodynamic behavior of airflow around the vehicle and evaluate parameters such as drag, lift, pressure distribution, velocity distribution, streamline patterns, turbulence, and wake formation.

## 🎯 Objectives

* Analyze airflow behavior around a scaled passenger car.
* Evaluate **Drag Coefficient (Cd)** and **Lift Coefficient (Cl)**.
* Study pressure and velocity distributions around the vehicle.
* Analyze flow separation and wake formation.
* Identify regions contributing to aerodynamic losses.
* Explore potential areas for future aerodynamic optimization.

## 🛠️ Software & Tools

* **ANSYS Fluent**
* **ANSYS SpaceClaim**
* **CAD Software** – SolidWorks / Creo / CATIA
* Computational Fluid Dynamics (CFD)

## ⚙️ Methodology

The analysis followed these major steps:

1. Developed a **1:10 scaled passenger car model** using CAD software.
2. Imported the geometry into **ANSYS SpaceClaim** for geometry cleanup.
3. Created a sufficiently large computational domain.
4. Generated an unstructured **tetrahedral mesh**.
5. Applied inflation layers near the vehicle surface to capture boundary-layer effects.
6. Defined airflow and wall boundary conditions.
7. Performed steady-state CFD simulation using ANSYS Fluent.
8. Analyzed the aerodynamic results using CFD-Post.

## 🔧 Simulation Setup

| Parameter                  | Value                        |
| -------------------------- | ---------------------------- |
| Model Scale                | 1:10                         |
| Flow Type                  | Steady-state, incompressible |
| Inlet Velocity             | 30 m/s                       |
| Fluid                      | Air                          |
| Turbulence Model           | SST k–ω                      |
| Solver                     | Pressure-Based               |
| Pressure-Velocity Coupling | SIMPLE                       |
| Spatial Discretization     | Second Order Upwind          |
| Convergence Criterion      | 10⁻⁶                         |
| Mesh Type                  | Tetrahedral                  |
| Inflation Layers           | 10                           |
| First Layer Thickness      | 0.5 mm                       |
| Growth Rate                | 1.2                          |
| Total Elements             | 1.2–2.0 million              |

The report specifies a velocity inlet of 30 m/s, pressure outlet, no-slip vehicle wall, moving road surface, and symmetry conditions for the side and top boundaries.

## 📊 Key Results

| Parameter                        |   Result |
| -------------------------------- | -------: |
| Maximum Velocity                 | 42.7 m/s |
| Maximum Static Pressure          |   560 Pa |
| Minimum Static Pressure          |  -420 Pa |
| Drag Force                       |   11.6 N |
| Lift Force                       |    2.1 N |
| Drag Coefficient (Cd)            | **0.31** |
| Lift Coefficient (Cl)            | **0.08** |
| Maximum Turbulent Kinetic Energy | 18 m²/s² |
| Maximum Wall Shear Stress        |    58 Pa |
| Iterations                       |      850 |

The simulation showed high pressure near the frontal stagnation region, accelerated airflow over the roof, and flow separation with a turbulent wake behind the vehicle.

## 📈 Results & Analysis

The following outputs were evaluated:

* Velocity contours
* Pressure contours
* Streamline patterns
* Velocity vectors
* Turbulent kinetic energy
* Wall shear stress
* Wake formation
* Drag force
* Lift force
* Drag coefficient
* Lift coefficient

The analysis indicates that **rear-end flow separation and wake formation are major contributors to aerodynamic drag**. The results also identify opportunities for improving the rear geometry, roof-to-trunk transition, diffuser, and underbody design.

## 🚗 Conclusion

The CFD study successfully evaluated the aerodynamic performance of the scaled passenger car using ANSYS Fluent. The model achieved a **drag coefficient of 0.31** and **lift coefficient of 0.08**. The results demonstrate the usefulness of CFD for understanding vehicle airflow and identifying regions for aerodynamic improvement before physical prototype development.

## 🔮 Future Scope

* Validate CFD results using wind-tunnel experiments.
* Perform transient CFD using LES or DES.
* Analyze different vehicle speeds and Reynolds numbers.
* Investigate crosswind and yaw-angle effects.
* Include rotating wheels and moving-ground effects.
* Evaluate different spoilers, diffusers, and vehicle geometries.
* Apply AI and optimization techniques for aerodynamic optimization.

## 👨‍💻 Authors

**T J Prasanna Kumar¹, P Manoj Kumar², P Yeswanth Kumar³, N Giridhar⁴, M Dileep Kumar⁵, K Damodhara Rao⁶**

¹ Assistant Professor, Department of Mechanical Engineering, PVPSIT, Vijayawada
²⁻⁶ Undergraduate Students, Department of Mechanical Engineering, PVPSIT, Vijayawada

---

### 📄 Project Report

The complete project report is available in the `report/` directory.

**Project:** Numerical Analysis of Aerodynamic Performance of a Scaled Automobile Using ANSYS Fluent
