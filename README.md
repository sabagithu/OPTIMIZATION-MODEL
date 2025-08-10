# OPTIMIZATION-MODEL

- **Company Name**: CodTech IT Solutions  
- **Intern Name**: *AYESHA SABA*  
- **Intern ID**: CT4MWP218  
- **Domain**: Data Science  
- **Duration**: 16 Weeks  
- **Mentor**: Neela Sanrosh

  # 🚚 Supply Chain Optimization using PuLP

## 📖 Project Overview
This project is part of my internship deliverables at **CodTech IT Solutions**, focused on solving a classic supply chain optimization problem using **Linear Programming**. The objective is to determine the optimal shipment quantities from multiple warehouses to retail stores while minimizing transportation costs and satisfying supply and demand constraints.

The solution is implemented using the **PuLP** library in Python and demonstrates practical applications of operations research in logistics and resource allocation.

---

## 📌 Problem Statement
A company operates:
- **3 Warehouses** with limited supply  
- **4 Retail Stores** with fixed demand  
- Known **transportation costs per unit** between each warehouse-store pair

### Goal:
- Satisfy all supply and demand constraints  
- Minimize the total transportation cost

---

## 🛠️ Approach

### 🔹 Step 1: Define Data
- Supply available at each warehouse  
- Demand required at each retail store  
- Transportation cost matrix

### 🔹 Step 2: Formulate LP Model
- **Decision Variables**: Units to transport from each warehouse to each store  
- **Objective Function**: Minimize total transportation cost  
- **Constraints**:
  - Supply limits for each warehouse  
  - Demand requirements for each store

### 🔹 Step 3: Solve the Model
- Used PuLP’s built-in **CBC solver**  
- Extracted optimal shipment plan and minimum cost

---

## 📊 Results
- ✅ Optimal shipping quantities from each warehouse to each store  
- 💰 Minimum transportation cost calculated by the model  
- 📈 Model satisfies all constraints and provides a cost-efficient logistics plan

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
