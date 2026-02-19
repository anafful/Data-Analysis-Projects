# Bike Sales Analysis – Excel Pivot & Functions

## Overview

This project analyses a bike sales dataset using Excel, focusing on Pivot Tables, logical functions, and basic data preparation techniques to explore sales patterns and customer segments.

---

## Objectives

- Analyse sales across markets and demographics  
- Identify high-performing segments  
- Categorise sales volumes using formulas  
- Build summary views with Pivot Tables  

---

## Pivot Table Analysis

A Pivot Table was created to summarise sales by country, market, age group, and gender.

### Key Findings

- **Germany customers:** Primarily Adults aged 36–64  
- **Countries present across all markets:** Australia and UK  
- **Most profitable segment:** US customers (Adults 35–64)  
- **Youth demographic:** Lower overall spending patterns observed  

![Revenue by Age Group]Images/revenue-comparison.png)

---

## Product Categorisation – SWITCH Function

Sales volumes were grouped into performance categories using the SWITCH function.

**Formula Applied**

```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
