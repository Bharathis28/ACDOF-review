# ACDOF-review  
**Adaptive Cloud–DevOps Orchestration Framework (ACDOF)**  
_Simulation Notebooks & Supporting Code for the Review Paper_

This repository contains all the simulation code, notebooks, and workflow experiments used in the review paper:

**“A Literature Review on Cloud–DevOps Synergy for Scalable and Reliable ML Lifecycle Management (ACDOF)”**

The project explores how predictive orchestration, energy-aware scheduling, cross-cloud coordination, and unified governance can improve the performance, sustainability, and reliability of ML workloads.

##  Overview

Modern ML pipelines face challenges such as:
- Reactive & inefficient autoscaling  
- Fragmented multi-cloud interoperability  
- High energy usage & carbon emissions  
- Missing governance, lineage, version control  
- Poor runtime observability & unpredictable latency  

To address these limitations, **ACDOF** integrates four major components:
1. **Predictive Orchestration Engine**  
2. **Energy-Aware Scheduling Module**  
3. **Cross-Cloud Orchestration Layer**  
4. **Unified Governance Layer**

This repository includes **simulation notebooks** that evaluate each of these components individually and collectively.

## Key Features

- **Predictive Scaling Simulation** (ARIMA/Prophet/LSTM-based logic)  
- **Energy-Aware Scheduling** using carbon-intensity & cloud-cost models  
- **Cross-Cloud Orchestration** (AWS/GCP/Azure simulated latency, cost & failures)  
- **Unified Governance & Traceability Tracking**  
- **Full end-to-end simulation comparing baseline vs ACDOF**  
- **Graphs for latency, CO₂ emissions, audit time, wait-time reduction, region selection**  
- **Modular notebooks for each ACDOF component**

## Simulation Outputs 
1. Predictive Orchestration
ACDOF reduces job wait-time by ~59%
Graph comparing predictive vs non-predictive workloads

2. Energy-Aware Scheduling
CO₂ emissions reduced by ~58%
Region selection logic based on carbon + cost

3. Cross-Cloud Orchestration
Latency reduced by ~27%
Automatic failover simulation
Multi-region performance plots

4. Governance & Traceability
Traceability increases from 60% → 95%
Audit time reduced from 25 min → 5 min

## How to Extend This Project
You can expand the framework by:
Integrating real cloud APIs (AWS Pricing, ElectricityMap, WattTime)
Adding GPU-based job modeling
Extending predictive models (XGBoost, LSTM sequences)
Using real Kubernetes or Terraform for prototype orchestration
Adding monitoring dashboards (Prometheus → Grafana)
This repository is intentionally modular to support future experimentation.

👥 Authors
Bharathi S.
Samuthira Pandi
M. Vinodhini
Prasithaa M. U.
(Chennai Institute of Technology, Chennai)

