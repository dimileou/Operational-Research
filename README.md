# 📊 Operations Research Projects – School Timetabling & Facility Location Optimization

This repository contains the implementation of two **Operations Research problems**, formulated as **Mixed-Integer Linear Programming (MILP)** models and solved in **Python** with the **Gurobi Optimizer**.  

---

## 📘 Contents
- 🕒 **Problem 1: High School Timetabling**  
- 🏭 **Problem 2: Facility Location Optimization**  
- 📊 **Visualizations and Results**  

---

## 🕒 Problem 1: High School Timetabling
This problem involves scheduling lessons for two high school classes over a 5-day week.  
The aim is to assign subjects to time slots and classrooms while satisfying constraints such as:

- Teacher availability  
- Subject frequency requirements  
- No overlapping lessons  
- Special rules (e.g., PE only on Thursday, Monday morning blocked)  

### 📌 Solution Highlights
- Binary MILP formulation  
- Implemented in Python with Gurobi  
- Produces a valid weekly schedule with all constraints satisfied  

---

## 🏭 Problem 2: Facility Location Optimization
A logistics company must decide:

- Which warehouses to open  
- How to distribute demand from warehouses to sales centers  

### Constraints
- Each warehouse has a fixed opening cost and a capacity limit  
- Each sales center has a fixed demand  
- Transportation costs are defined between warehouses and centers (some infeasible)  

### 📌 Solution Highlights
- MILP model with binary and continuous variables  
- Objective: minimize total cost (fixed + transportation)  
- Provides the optimal flow matrix and list of open warehouses  

---
