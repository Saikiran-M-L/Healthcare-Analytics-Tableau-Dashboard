# Healthcare Analytics Dashboard System

A comprehensive Tableau-based analytics solution for healthcare operations, featuring dual dashboards for executive oversight and deep operational analysis of patient encounters, costs, payer performance, and clinical efficiency.

## 📊 Project Overview

This project transforms healthcare data into actionable insights through interactive visualizations and parameter-driven analytics. Built on a star schema data model with Tableau relationships, it supports multi-dimensional analysis across patients, encounters, procedures, and payers.

### Key Features
- **Dual-Dashboard Architecture**: Executive overview + operational deep dive
- **Dynamic Parameters**: Date range, encounter class, age group, metrics selector
- **Advanced Analytics**: Readmission trends, efficiency matrices, geographic analysis
- **Multi-Persona Design**: Serves executives, clinical managers, and financial analysts

## 🗂️ Dataset

**Source:** Synthetic healthcare data (Massachusetts, 2011-2022)

**Tables:**
- `patients.csv` - 1,171 unique patients with demographics
- `encounters.csv` - Patient visits with costs and classifications
- `procedures.csv` - Medical procedures performed
- `payers.csv` - Insurance organization details
- `organizations.csv` - Healthcare facility information
- `data_dictionary.csv` - Field definitions

**Coverage:**
- **Time Span**: 2011-2022 (11 years of encounter history)
- **Geographic Scope**: Massachusetts (Suffolk, Norfolk, Middlesex, Plymouth counties)
- **Patient Demographics**: Multi-ethnic population across all age groups
- **Encounter Types**: Ambulatory, Emergency, Inpatient, Outpatient, Urgent Care, Wellness

## 📈 Dashboards

### Dashboard 1: Executive Overview
High-level operational and financial snapshot featuring KPIs (total revenue, claim volume, payer coverage ratio, patient out-of-pocket), trend analysis across multiple metrics, payer performance comparisons, and geographic patient density mapping. Designed for strategic decision-making with parameter-driven filtering by date range and encounter type.

### Dashboard 2: Clinical & Financial Deep Dive
Detailed operational analysis including efficiency matrices showing procedure volume versus cost with patient burden indicators, payer-encounter heatmaps with dynamic metric switching, cost distribution analysis, patient financial burden trends over time, and drill-down encounter detail tables. Built for clinical managers and financial analysts requiring granular insights into cost drivers and utilization patterns.

---

