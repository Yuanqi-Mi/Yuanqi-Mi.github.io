---
title: "Research Tool Development: REDCap RDS Tree Automata"
summary: "A Streamlit-based tool for visualizing RDS recruitment trees, generating Gile’s SS-weights, and estimating population size using SS-PSE for multi-country biobehavioral studies."
tags:
  - RDS
  - Population Size Estimation
  - HIV Epidemiology
  - Data Tool Development
date: "2025-01-01"

# Optional: Add a thumbnail
image:
  caption: "REDCap RDS Tree Automata Interface"
  focal_point: "center"
  preview_only: false
---

## Overview

**REDCap RDS Tree Automata** is a research tool I built to support multi-country HIV surveillance systems, particularly studies using **Respondent-Driven Sampling (RDS)**.

The tool enables:

- Visualization of recruitment trees (layered tidy-wave plots)
- Generation of **Gile’s Successive Sampling (SS) weights**
- Production of **SS-PSE population size estimates**
- Automated quality checks for network size, degenerate trees, and seed dependency
- Direct integration with **REDCap API**


The application is being implemented by The Global Fund to Fight AIDS, Tuberculosis and Malaria, and academic collaborators across Sub-Saharan Africa.

---

## 🔗 Application Link

👉 **LIVE APP / GitHub Repository:**  
https://github.com/Yuanqi-Mi/REDCap-RDS-Tree-Automata-SSPSE-/

---

## 📊 Tool Interface

![RDS Tree Automata](recruitment_tree.gif)

---

## Technical Highlights

- **Python / Streamlit** frontend  
- **NetworkX** for graph construction  
- **Plotly** for dynamic RDS tree visualization  
- **R integration** via subprocess for SS-PSE modeling  
- Supports **RDS**, and post-stratification workflows    
- Lightweight deployment (cloud or local)

---

## Impact

This tool has streamlined analysis workflows for:

- Population size estimation (PSE)
- Weighting procedures for biobehavioral surveys
- Field monitoring of recruitment progress
- Generation of standardized deliverables for international stakeholders


---


