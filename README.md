# 2-Stage Spur Gearbox Design and CAD Assembly
<br>
<img width="1916" height="1041" alt="Gear Box Design Assembly" src="https://github.com/user-attachments/assets/d3fc55b7-6c1d-4c76-a9ce-7dcbd82fa48b" />
<br>

## 📚 Table of Contents

1. [Project Summary](#project-summary)  
2. [Project Overview](#project-overview)
3. [Objectives](#objectives)
4. [Design Specifications](#design-specifications)  
5. [Engineering Calculations](#engineering-calculations)  
6. [Gear Design](#gear-design)  
7. [Shaft Design](#shaft-design)  
8. [Bearing Selection](#bearing-selection)  
9. [Materials Used](#materials-used)
10. [Software Used](#software-used)
11. [CAD Modeling and Assembly](#cad-modeling-and-assembly)  
12. [Results](#results)  
13. [Applications](#applications)  
14. [Future Improvements](#future-improvements)  
15. [Author](#author)  
16. [Final Note](#final-note)

## Project Summary

The 2-Stage Gearbox Design project focuses on the complete design and development of a mechanical gearbox using standard engineering calculations and 3D CAD modeling in SolidWorks.

## Project Overview

This project focuses on the design and development of a **2-Stage Spur Gearbox** using standard mechanical engineering calculations and 3D CAD modeling in SOLIDWORKS.

The gearbox assembly was developed using standard design procedures and engineering calculations including:
- Speed reduction analysis
- Torque calculations
- Gear design
- Shaft design
- Bearing selection
- Assembly modeling

## Objectives

- Design a 2-stage gearbox for mechanical power transmission
- Perform accurate engineering calculations
- Develop complete 3D CAD models and assembly
- Apply standard mechanical design procedures
- Understand industrial gearbox design methodology

## Design Specifications

| Parameter | Value |
|---|---|
| Motor Power | 0.746 kW (1 HP) |
| Input Speed | 1440 RPM |
| Output Speed | 60 RPM |
| Gearbox Type | Spur Gear |
| Number of Stages | 2 |
| Pressure Angle | 20° |
| Gear Material | EN8 Steel |

## Engineering Calculations

## 1. Gear Ratio Calculation

```math
i = \frac{N_{in}}{N_{out}} = \frac{1440}{60} = 24
```

Selected Stage Ratios:
- Stage 1 = 4:1
- Stage 2 = 6:1

Overall Reduction Ratio:

```math
i_{total} = 4 \times 6 = 24
```


## 2. Torque Calculation

Motor Torque:

```math
T = \frac{9550P}{N}
```

```math
T = \frac{9550 \times 0.746}{1440} = 4.95 \ Nm
```

Output Torque:

```math
T_{out} = 4.95 \times 24 = 118.8 \ Nm
```


## Gear Design

### Selected Module
- Module (m) = 2.5 mm

### Stage 1 Gears

| Component | Teeth |
|---|---|
| Pinion | 20 |
| Gear | 80 |

### Stage 2 Gears

| Component | Teeth |
|---|---|
| Pinion | 18 |
| Gear | 108 |


## 3. Pitch Circle Diameter

Formula:

```math
d = mZ
```

| Gear | Diameter |
|---|---|
| Gear 1 | 50 mm |
| Gear 2 | 200 mm |
| Gear 3 | 45 mm |
| Gear 4 | 270 mm |


## 4. Center Distance

Formula:

```math
a = \frac{d_1 + d_2}{2}
```

| Stage | Center Distance |
|---|---|
| Stage 1 | 125 mm |
| Stage 2 | 157.5 mm |


## Shaft Design

Using torsion equation:

```math
d = \left(\frac{16T}{\pi\tau}\right)^{1/3}
```

| Shaft | Diameter |
|---|---|
| Input Shaft | 20 mm |
| Intermediate Shaft | 25 mm |
| Output Shaft | 35 mm |

## Bearing Selection

| Shaft Diameter | Bearing |
|---|---|
| 20 mm | 6204 |
| 25 mm | 6205 |
| 35 mm | 6207 |


## Materials Used

| Component | Material |
|---|---|
| Gears | EN8 Steel |
| Shafts | EN24 Steel |
| Housing | Cast Iron FG200 |

## Software Used

- SOLIDWORKS
- MS Excel

## CAD Modeling and Assembly

The complete gearbox assembly was modeled in SOLIDWORKS including:
- Spur gears
- Shafts
- Bearings
- Housing
- Side covers
- Assembly mates and constraints

The CAD workflow included:
1. Part Modeling  
2. Assembly Creation  
3. Component Mating  
4. Alignment and Constraints  
5. Exploded Views  
6. Technical Drawings

## Results

- Successfully designed a functional 2-stage gearbox
- Completed accurate engineering calculations
- Developed complete 3D CAD assembly
- Implemented industrial gearbox design methodology

## Applications

- Conveyor systems
- Industrial automation
- Mechanical power transmission
- Speed reduction systems

## Future Improvements

- Helical gear implementation
- Finite Element Analysis (FEA)
- Weight optimization
- Lubrication system design
- Manufacturing drawing generation

## Author

**Utkarsh Jadhav**  
Mechanical Engineering Student | CAD Designer | Robotics Enthusiast  

- GitHub: https://github.com/utkarsh-jadhav-mech
- LinkedIn: https://www.linkedin.com/in/utkarsh-jadhav-mech

## Final Note

The **2 Stage Gearbox Design** project provides practical experience in:
- Machine Design
- Mechanical Engineering Calculations
- Gear Design
- Shaft Design
- CAD Modeling and Assembly

This project demonstrates the complete engineering workflow from theoretical calculations to final 3D assembly development using standard industrial design practices.
