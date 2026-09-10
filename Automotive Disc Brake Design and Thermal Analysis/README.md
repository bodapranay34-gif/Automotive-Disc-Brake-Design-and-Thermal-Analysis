# Automotive Disc Brake Design and Thermal Analysis Using MATLAB and SolidWorks

## 📌 Project Overview

This project focuses on the design and engineering analysis of an automotive disc brake system using **SolidWorks** and **MATLAB**.

The brake disc was designed based on specified vehicle operating conditions, including vehicle mass, initial velocity, required stopping distance, and braking torque. Standard automotive brake-design equations were used to determine the required braking force, disc dimensions, braking torque, energy absorption, and factor of safety.

A thermal analysis was also performed to evaluate the temperature rise of the brake disc during braking and to assess its ability to dissipate the generated heat.

The overall objective was to develop a brake disc design that provides adequate braking performance, structural safety, and effective thermal dissipation.

---

## 🎯 Project Objectives

- Design an automotive disc brake system using **SolidWorks**
- Calculate the required braking force from vehicle operating conditions
- Determine the required braking torque
- Calculate the kinetic energy absorbed during braking
- Determine suitable brake disc dimensions
- Evaluate the factor of safety of the brake disc
- Perform thermal analysis of the brake disc
- Study heat generation and dissipation during braking
- Optimize critical disc dimensions for improved thermal performance
- Verify that the final design provides reliable braking performance

---

## 🛠️ Software Used

- **MATLAB** – Engineering calculations and thermal analysis
- **SolidWorks** – 3D CAD modelling and design
- **Microsoft Excel** – Optional calculation verification

---

## 🚗 Design Inputs

The brake disc design is based on the following vehicle parameters:

| Parameter | Symbol | Unit |
|---|---:|---:|
| Vehicle Mass | `m` | kg |
| Initial Vehicle Speed | `V` | m/s |
| Final Vehicle Speed | `Vf` | m/s |
| Stopping Distance | `s` | m |
| Wheel Radius | `Rw` | m |
| Coefficient of Friction | `μ` | - |
| Number of Brake Discs | `n` | - |
| Brake Disc Material | - | - |

> **Note:** The input values can be modified in the MATLAB calculation files according to the required vehicle specifications.

---

## ⚙️ Engineering Calculations

### 1. Vehicle Deceleration

The required vehicle deceleration was determined from the stopping-distance requirement.

```text
Vf² = Vi² + 2as
