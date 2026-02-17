
# Bike Sales Analysis – Excel Pivot & Functions
## Overview

This exercise focused on exploring a bike sales dataset using Pivot Tables, logical functions, and basic data preparation techniques in Excel.

Objectives

Analyse sales across markets and demographics

Identify profitable segments

Categorise sales volumes using formulas

Build summary views using Pivot Tables

## 1️⃣ Pivot Table Analysis

A Pivot Table was created to summarise sales by country, market, age group, and gender.

Key Findings

Germany customers: Adults aged 36–64

Countries present in all markets: Australia and UK

Most profitable segment: US customers (Adults 35–64)

Youth demographic: Lower spending behaviour observed

## 2️⃣ Product Categorisation – SWITCH Function

Sales volumes were categorised into performance bands using the SWITCH function.

Formula applied:

=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")


Logic Used

High → Sales > 600

Medium → Sales between 300–600

Low → Sales < 300

## 3️⃣ Data Preparation

Basic cleaning steps were performed:

✔ Removed spacing inconsistencies in Sales Volume
✔ Confirmed numerical data types
✔ Ensured Pivot compatibility

## 4️⃣ Visualisations

Charts were created to visualise sales distribution and patterns.
