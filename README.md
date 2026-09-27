# Capacitive MEMS Pressure Sensor — COMSOL Multiphysics

Numerical modeling and simulation of a capacitive MEMS pressure sensor using COMSOL Multiphysics. The project includes geometry development, material definition, meshing, multiphysics setup, deformation analysis, electrostatic simulation, and sensor response analysis.

---

## 1. Project Overview

A capacitive MEMS pressure sensor detects applied pressure through the mechanical deformation of a movable diaphragm, which changes the capacitance between two electrodes.

The model was developed in COMSOL Multiphysics to study the mechanical and electrostatic behavior of the sensor and its response to applied pressure.

### Objectives

- Develop the geometry of a capacitive MEMS pressure sensor
- Define material properties and model domains
- Generate an appropriate computational mesh
- Apply mechanical and electrostatic boundary conditions
- Analyze diaphragm deformation under applied pressure
- Investigate the electrostatic behavior of the sensor
- Study the relationship between applied pressure and sensor response

---

## 2. Geometry

The MEMS pressure sensor geometry was created in COMSOL Multiphysics, including the sensing structure and relevant electrode regions.

![image alt](https://github.com/SahanaGonalNagaraja/capacitive-mems-pressure-sensor/blob/79ac1fb3323f26800754bb9d14b712fb368c7c0d/01_model_geometry.png)

---

## 3. Materials

Material properties were assigned to the different domains of the sensor model.

![image alt](https://github.com/SahanaGonalNagaraja/capacitive-mems-pressure-sensor/blob/90e1717c064687356f87c02b7af235e29dd38e14/02_materials.png)

---

## 4. Mesh

A finite-element mesh was generated for numerical simulation. The final model consisted of approximately 13,950 domain elements and 930 boundary elements.

![image alt](https://github.com/SahanaGonalNagaraja/capacitive-mems-pressure-sensor/blob/6c2f2f75c182cef0b1d32b7781c4f8fdd328048a/02_mesh1.png)

---

## 5. Deformation Analysis

The mechanical response of the sensor structure was analyzed under the applied pressure. The resulting deformation of the movable structure was investigated.

![Deformation](images/04_deformation.png)

---

## 6. Electrostatic Analysis

The electrostatic behavior of the capacitive structure was simulated to investigate the electrical response of the sensor.

![Electrostatic Analysis](images/05_electrostatic.png)

---

## 7. Final Model

The completed multiphysics model combines the geometry, material properties, mesh, and defined physics interfaces for the sensor simulation.

![Final Model](images/06_final_model.png)

---

## 8. Simulation Results

The simulation results were analyzed to understand the relationship between the applied pressure and the resulting sensor response.

### Result 1

![Simulation Result 1](images/07_result_1.png)

### Result 2

![Simulation Result 2](images/08_result_2.png)

---

## 9. Key Learning

Through this project, I gained practical experience with:

- COMSOL Multiphysics
- MEMS sensor modeling
- Geometry construction
- Material and domain definition
- Boundary conditions
- Finite-element meshing
- Multiphysics simulation
- Mechanical deformation analysis
- Electrostatic analysis
- Post-processing and interpretation of simulation results

---

## Tools

**COMSOL Multiphysics**

**Finite Element Method (FEM)**

**MEMS / Microtechnology**



