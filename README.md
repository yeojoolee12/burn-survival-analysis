# Evaluation of Bathing Solutions on Time-to-Infection in Burn Patients

This repository contains a survival analysis comparing a novel bathing solution with standard care in terms of time to infection among burn patients.

## 📌 Project Overview
* **Objective:** To compare time-to-infection between the standard care and novel bathing solution groups using Kaplan-Meier estimation.
* **Dataset:** `burn.csv`
* **Primary Endpoint:** Time to infection (`infecttime`) and infection occurrence (`infectevent`).

## 🛠 Tools & Packages
* **Language:** R
* **Packages:** `survival`, `survminer`, `ggplot2`

## 📊 Key Analysis
* Data cleaning and factor level definition for treatment groups.
* Kaplan-Meier survival curve estimation and log-rank test.
* Visualizing infection-free probability over time with risk tables.

## 📁 Repository Structure
* `survival_analysis_Yeojoo2.Rmd` : R Markdown source code containing analysis and visualization.
* `burn.csv` : Dataset used for analysis.
* `index.html` : Rendered HTML report.
* 
🔗 **Interactive Web Report:** https://yeojoolee12.github.io/burn-survival-analysis/
