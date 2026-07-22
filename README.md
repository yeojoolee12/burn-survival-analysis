# Evaluation of Bathing Solutions on Time-to-Infection in Burn Patients

This repository contains the survival analysis evaluating the effectiveness of a novel bathing solution compared to standard care in preventing infections among burn patients.

## 📌 Project Overview
* **Objective:** To compare time-to-infection between control/standard bathing solutions and a new bathing solution using Kaplan-Meier estimation.
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
* `burn_analysis.Rmd` : R Markdown source code containing analysis and visualization.
* `burn.csv` : Dataset used for analysis.
* `index.html` : Rendered HTML report.
