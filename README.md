# Healthcare Patient Dashboard

## 📊 Project Overview

**Healthcare Patient Dashboard** is an interactive data visualization project created using **Tableau Public**. The dashboard analyzes healthcare patient data and presents important information through multiple visualizations.

The project helps users understand patient distribution based on admission type, gender, blood type, medical condition, and billing amount.

## 🎯 Objectives

- Analyze healthcare patient data visually.
- Understand different patient admission types.
- Compare patient distribution by gender.
- Analyze blood type distribution.
- Identify patient counts across medical conditions.
- Understand the distribution of billing amounts.
- Present multiple visualizations in a single interactive dashboard.

## 🛠️ Tools and Technologies

- **Tableau Public**
- **Microsoft Excel / CSV Dataset**
- **Data Visualization**
- **Dashboard Design**

## 📁 Dataset

The dataset contains healthcare-related patient information such as:

- Admission Type
- Age
- Blood Type
- Date of Admission
- Discharge Date
- Doctor
- Gender
- Hospital
- Insurance Provider
- Medical Condition
- Medication
- Name
- Room Number
- Test Results
- Billing Amount

## 📈 Dashboard Visualizations

### 1. Admission Type — Bar Chart

**Purpose:** Shows the number of patients for each admission type.

**Fields Used:**
- Columns → `Admission Type`
- Rows → `Age` → `Count`

**Categories:**
- Elective
- Emergency
- Urgent

### 2. Blood Type — Treemap

**Purpose:** Shows the distribution of patients across different blood types.

**Fields Used:**
- Color → `Blood Type`
- Size → `Age` → `Count`
- Label → `Blood Type`

**Blood Types:**
- A-
- A+
- AB-
- AB+
- B-
- B+
- O-
- O+

### 3. Gender — Pie Chart

**Purpose:** Shows the proportion of male and female patients.

**Fields Used:**
- Color → `Gender`
- Angle → `Age` → `Count`
- Label → `Gender`

### 4. Medical Condition — Horizontal Bar Chart

**Purpose:** Compares the number of patients across different medical conditions.

**Fields Used:**
- Rows → `Medical Condition`
- Columns → `Age` → `Count`

This visualization helps compare different medical conditions among patients.

### 5. Billing Amount — Histogram

**Purpose:** Shows the distribution of patient billing amounts.

**Fields Used:**
- Columns → `Billing Amount (bin)`
- Rows → `Billing Amount` → `Count`

A billing amount bin is created in Tableau to group continuous billing values into ranges.

## 🖥️ Dashboard

The individual worksheets are combined into one dashboard titled:

**Healthcare Patient Dashboard**

### Dashboard Components

- 📊 Admission Type — Bar Chart
- 🟦 Blood Type — Treemap
- 🥧 Gender — Pie Chart
- 📊 Medical Condition — Horizontal Bar Chart
- 📈 Billing Amount — Histogram

## 🔄 Project Workflow

```text
Healthcare Dataset
        ↓
Connect Dataset in Tableau
        ↓
Create Individual Worksheets
        ↓
Create Different Visualizations
        ↓
Add Worksheets to Dashboard
        ↓
Arrange Dashboard
        ↓
Healthcare Patient Dashboard
