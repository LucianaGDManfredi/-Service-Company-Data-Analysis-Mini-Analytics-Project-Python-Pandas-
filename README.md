
<div align="center">
<h1> Python-Insights <br> Service Company Data Analysis – Mini Project (Python & Pandas) </h1>
<img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" alt="Logo Python" width="220">
<img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" alt="Logo Pandas" width="220">
</div>

This project presents a complete exploratory data analysis (EDA) of a fictional service-based company using **Python**, **Pandas**, and **Matplotlib**.  
The goal is to simulate a real-world data workflow involving multiple relational datasets, cleaning, merging, KPI calculation, and business insights.

The analysis uses three datasets from the year *2019*:
- `CadastroFuncionarios`
- `CadastroClientes`
- `BaseServiçosPrestados`

---

## 📊 Project Objectives

This mini-project answers key business questions:

1. **What was the total payroll cost?**  
2. **What was the total company revenue?**  
3. **What percentage of employees closed at least one contract?**  
4. **How many contracts were closed per department?**  
5. **How many employees are in each department?**  
6. **What is the average monthly contract value (ticket médio)?**

Additional improvements were also included to elevate this project to portfolio quality.

---

## 🗂️ Dataset Description

### 1) Employees (`CadastroFuncionarios.csv`)
Contains employee financial and organizational data.

Key columns:
- `ID Funcionário`
- `Area`
- `Salario Base`
- `Beneficios`
- `Impostos`
- `VT`
- `VR`

### 2) Clients (`CadastroClientes.csv`)
Contains client financial data.

Key columns:
- `ID Cliente`
- `Valor Contrato Mensal`

### 3) Services (`BaseServiçosPrestados.xlsx`)
Contains every contract closed in 2019.

Key columns:
- `ID Cliente`
- `ID Funcionário`
- `Tempo Total de Contrato (Meses)`

---

## 🛠️ Tools and Technologies

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Summary of Analyses

### **1. Total Payroll**
Using:
