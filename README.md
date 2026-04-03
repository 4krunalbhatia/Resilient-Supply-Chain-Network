# Resilient Supply Chain Network Simulation & Optimization

## 📌 Overview
This project models and analyzes a large-scale supply chain network to evaluate its performance and resilience under disruption scenarios.

The system combines **network flow optimization** and **discrete-event simulation** to assess how failures in suppliers or warehouses impact overall operations.

---

## 🎯 Business Problem
Supply chains are vulnerable to disruptions such as supplier failures or warehouse outages. These disruptions can lead to:
- Reduced throughput
- Increased delivery times
- Lower service levels

This project aims to simulate and quantify these impacts.

---

## ⚙️ Approach

### 1. Network Modeling
- 100-node supply chain network
- Nodes represent suppliers, warehouses, and distribution centers
- Edges represent transportation routes with capacity constraints

### 2. Optimization
- Implemented **Edmonds-Karp max-flow algorithm**
- Calculated maximum throughput under different conditions

### 3. Simulation
- Used **SimPy** for discrete-event simulation
- Modeled order flow, delays, and system dynamics

### 4. Disruption Scenarios
- Single-node failures (critical warehouse/supplier)
- Regional disruptions
- Random failures

---

## 📊 Key Metrics
- Throughput
- Service level
- Average delivery time
- Resilience ratio

---

## 📈 Results & Insights
- Identified **critical nodes** whose failure significantly reduces throughput
- Demonstrated how disruptions impact service levels and delivery performance
- Showed the importance of redundancy in supply chain design
- Provided insights into improving network robustness

---

## 🛠 Tech Stack
- Python (NetworkX, pandas, numpy)
- SimPy
- Matplotlib
- Optimization Algorithms (Max Flow)

---

## 📷 Visualizations
(Add your charts here)

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
