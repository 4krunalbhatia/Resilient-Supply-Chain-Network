# 🚀 Resilient Supply Chain Network Simulation & Optimization

## 📌 Overview
This project models and analyzes a large-scale **supply chain network** to evaluate its performance and resilience under disruption scenarios.

By combining **network flow optimization** and **discrete-event simulation**, the system provides insights into how failures in suppliers or warehouses impact overall logistics operations.

---

## 🎯 Business Problem
Modern supply chains are highly complex and vulnerable to disruptions such as:
- Supplier failures  
- Warehouse breakdowns  
- Transportation bottlenecks  

These disruptions can lead to:
- Reduced throughput  
- Increased delivery delays  
- Lower service levels  

👉 The goal of this project is to **quantify these impacts and identify critical vulnerabilities** in the network.

---

## ⚙️ Approach

### 🧩 1. Network Modeling
- Constructed a **100-node supply chain network**
- Nodes represent suppliers, warehouses, and distribution centers
- Edges represent transportation routes with capacity constraints

---

### 🔄 2. Optimization
- Implemented **Edmonds–Karp Max Flow algorithm**
- Calculated maximum throughput under different operational scenarios
- Identified network bottlenecks and capacity limitations

---

### ⏱️ 3. Simulation
- Used **SimPy** for discrete-event simulation
- Modeled real-world logistics processes including:
  - Order flow  
  - Processing delays  
  - System congestion  

---

### ⚠️ 4. Disruption Scenarios
Simulated multiple failure scenarios:
- Single-node failures (critical supplier/warehouse)
- Regional disruptions
- Random failures across the network  

---

## 📊 Key Metrics
- **Throughput** (total flow across network)  
- **Service Level**  
- **Average Delivery Time**  
- **Resilience Ratio**  

---

## 📈 Key Results
- Identified **critical nodes** whose failure significantly reduces overall throughput  
- Observed measurable decline in **service levels and delivery performance** under disruptions  
- Detected **network bottlenecks** affecting operational efficiency  
- Demonstrated importance of **redundancy and robust network design**  

---

## 💡 Business Impact
This project demonstrates how companies can:

- Identify vulnerable points in their supply chain  
- Evaluate the impact of disruptions before they occur  
- Improve resilience through better network design  
- Make **data-driven decisions** to reduce operational risk  

👉 The approach can be applied to real-world logistics systems for **supply chain optimization and risk management**.

---

## 🧠 Key Insight
Even small disruptions in critical nodes can cause **disproportionate impact** on overall supply chain performance, highlighting the importance of redundancy and strategic planning.

---

## 🛠 Tech Stack
- **Python** (pandas, numpy)  
- **NetworkX** (network modeling)  
- **SimPy** (simulation)  
- **Matplotlib** (visualization)  
- **Optimization Algorithms** (Max Flow)  

---

## 🧩 System Architecture
- Network Modeling → NetworkX  
- Optimization → Max Flow (Edmonds–Karp)  
- Simulation → SimPy  
- Analysis → Python (pandas, matplotlib)  

---

## 📷 Visualizations
*(Add your images here)*  
- Supply chain network topology  
- Disruption impact analysis  
- Performance comparison charts  

---

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/resilient-supply-chain-network.git
cd resilient-supply-chain-network
pip install -r requirements.txt
