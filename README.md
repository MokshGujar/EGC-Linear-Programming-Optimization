# Energy Generation Cost Minimization (EGC Model)

A Linear Programming based optimization model developed to minimize electricity generation costs while satisfying power demand constraints.

## Overview

The Energy Generation Cost Minimization (EGC) Model is an optimization system designed to determine the most cost-effective energy generation strategy using renewable and non-renewable energy sources.

The model uses Linear Programming (LP) techniques to allocate power generation among available generators while minimizing total generation cost and meeting energy demand requirements.

---

## Objectives

- Minimize overall electricity generation cost.
- Meet required energy demand.
- Optimize allocation among generators.
- Compare renewable and non-renewable generation strategies.
- Analyze cost-efficient power generation scenarios.

---

## Technologies Used

- Python
- PuLP
- Linear Programming
- Matplotlib

---

## Features

### Non-Renewable Energy Optimization
- Multiple generator support
- Cost minimization
- Demand satisfaction constraints

### Renewable Energy Optimization
- Renewable source allocation
- Cost analysis
- Generation optimization

### Hybrid Energy Optimization
- Combined renewable and non-renewable generation
- Cost comparison
- Optimal energy mix determination

### Visualization
- Power generation comparison
- Cost analysis charts
- Scenario comparison

---

## Methodology

The model formulates the energy generation problem as a Linear Programming optimization problem.

### Objective Function

Minimize:

```text
Total Generation Cost
```

Subject to:

```text
Total Power Generated ≥ Demand
```

and generator capacity constraints.

---

## Project Workflow

```text
User Input
      ↓
Generator Information
      ↓
Cost Parameters
      ↓
Demand Constraints
      ↓
Linear Programming Model
      ↓
Optimization Solver (PuLP)
      ↓
Optimal Generation Plan
      ↓
Visualization
```

---

## Inputs

The model accepts:

- Number of generators
- Generator capacities
- Cost per unit of electricity
- Demand requirements
- Renewable generation parameters

---

## Output

The system generates:

- Optimal generation values
- Total energy produced
- Total generation cost
- Generator-wise allocation
- Cost comparison visualizations

---

## Project Structure

```text
Energy-Generation-Cost-Minimization/

README.md
requirements.txt

EGC Model.ipynb
```

---

## Installation

```bash
git clone https://github.com/MokshGujar/Energy-Generation-Cost-Minimization.git

cd Energy-Generation-Cost-Minimization

pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
EGC Model.ipynb
```

Run all cells and provide:

- Generator details
- Cost parameters
- Energy demand

The model will compute the optimal generation strategy.

---

## Applications

- Smart Grid Management
- Energy Planning
- Power System Optimization
- Renewable Energy Integration
- Cost-Efficient Electricity Generation

---

## Results

The optimization model successfully determines the least-cost energy generation strategy while satisfying demand constraints and generator limitations.

The model demonstrated approximately **15–20% cost reduction** in simulated scenarios compared to non-optimized generation allocation.

---

## Future Improvements

- Carbon Emission Constraints
- Real-Time Energy Pricing
- Demand Forecast Integration
- Renewable Energy Forecasting
- Multi-Objective Optimization

---

## Author

### Moksh Gujar

B.Sc. Data Science  
M.Sc. Data Science (Pursuing)

Areas of Interest:

- Machine Learning
- Deep Learning
- Optimization
- Natural Language Processing
- Computer Vision

Portfolio:
https://moksh-gujar-portfolio.netlify.app
