# OPTIMIZATION-MODEL

- **Company Name**: CodTech IT Solutions  
- **Intern Name**: *AYESHA SABA*  
- **Intern ID**: CT4MWP218  
- **Domain**: Data Science  
- **Duration**: 16 Weeks  
- **Mentor**: Neela Sanrosh

  # 🚚 Solving the Transportation Problem using PuLP

## 📖 Overview
This project demonstrates how to solve a classic **Transportation Problem** using **Linear Programming** with the **PuLP** library in Python. It is part of my internship deliverables at **CodTech IT Solutions**, under the Data Science domain.

The goal is to determine the most cost-effective way to transport goods from multiple warehouses to multiple retail stores, while satisfying supply and demand constraints and minimizing total transportation cost.

---

## 📌 Problem Statement
A company operates:
- **3 Warehouses**, each with a limited supply of goods  
- **4 Retail Stores**, each with a fixed demand  
- Known **transportation costs per unit** from each warehouse to each store

### Objective:
Determine how many units to ship from each warehouse to each store such that:
- ✅ All supply and demand constraints are satisfied  
- 💰 Total transportation cost is minimized

---

## 🛠️ Approach

### 🔹 Step 1: Model Setup
- Defined supply values for each warehouse  
- Defined demand values for each retail store  
- Created a cost matrix representing transportation costs between each warehouse–store pair

### 🔹 Step 2: Formulation in PuLP
- **Decision Variables**: Quantity of goods shipped from each warehouse to each store  
- **Objective Function**: Minimize total transportation cost  
- **Constraints**:
  - **Supply Constraints**: Total shipments from a warehouse ≤ its supply  
  - **Demand Constraints**: Total shipments to a store ≥ its demand

### 🔹 Step 3: Solution
- Solved using PuLP’s built-in **CBC solver**  
- Extracted optimal shipment plan and total transportation cost  
- Displayed results in a readable format

---

## 📊 Results

### ✅ Optimal Shipment Plan
The model provides the exact number of units to be shipped from each warehouse to each retail store to meet demand efficiently.

### 💸 Minimum Total Cost
The total transportation cost is minimized while satisfying all constraints. This cost is computed based on the optimal allocation.

---


## 📁 Repository Contents

- **`Task 4 PULP.ipynb`**  
  Jupyter Notebook containing the complete implementation: data setup, model formulation, solving, and result interpretation.

- **`README.md`**  
  Project documentation and overview.

---

## 🚀 Potential Applications
- Logistics planning for multi-location supply chains  
- Cost optimization in transportation and distribution networks  
- Decision support systems for warehouse-to-store allocation  
- Real-time resource allocation in retail and manufacturing

---
