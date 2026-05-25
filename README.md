# Real-Time Disaster Management Training Monitoring Dashboard

A Power BI-based analytics dashboard developed for Smart India Hackathon (SIH) 2025 to monitor, analyze, and visualize disaster management training activities conducted across India by NDMA and associated institutions.

---

## 📌 Problem Statement

- **Problem Statement ID:** 25258  
- **Title:** Real-Time Monitoring System for Disaster Management Trainings  
- **Organization:** National Disaster Management Authority (NDMA)  
- **Ministry:** Ministry of Home Affairs (MHA), Government of India  

---

## 📖 Project Overview

The Capacity Building and Training (CBT) Division of NDMA conducts disaster management training programs across India through:

- SDMAs
- NGOs
- Administrative Training Institutes (ATIs)
- Government departments
- Civil society organizations

Currently, there is no centralized platform to:
- monitor training activities
- track geographic coverage
- assess effectiveness
- identify training gaps
- generate analytical insights

This project provides a centralized Power BI dashboard solution for monitoring and analyzing disaster management training activities across India.

---

## 🎯 Objectives

- Monitor disaster management trainings in real time
- Analyze state-wise and district-wise training coverage
- Evaluate institution performance
- Track participant statistics
- Analyze disaster theme distribution
- Identify low-coverage regions
- Generate actionable insights using interactive dashboards

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard Development & Visualization |
| Excel | Dataset Storage |
| Power Query | Data Cleaning & Transformation |
| DAX | Data Analysis & Calculations |

---

## 📂 Dataset Information

The project uses a simulated dataset containing:
- 2000+ training records
- Multiple Indian states and districts
- Disaster management themes
- Institution information
- Participant statistics
- Feedback analysis
- GIS coordinates

### Main Tables

#### Training_Data
Contains:
- Training ID
- State
- District
- Disaster Theme
- Participants Count
- Date
- Venue Type
- Institution ID

#### Institution_Data
Contains:
- Institution Name
- Institution Type
- Operating State

#### Feedback_Data
Contains:
- Feedback Score
- Satisfaction Level
- Comments

---

## 📊 Dashboard Features

### 1. Executive Overview Dashboard
- Total Trainings
- Total Participants
- States Covered
- Districts Covered
- Average Feedback Score
- Monthly Training Trends

### 2. Geographic Analysis Dashboard
- GIS-based filled maps
- State-wise training coverage
- Participant distribution analysis
- Geographic insights

### 3. Disaster Theme Analytics
- Theme distribution analysis
- Most conducted disaster training themes
- Theme-wise participant trends

### 4. Institution Performance Dashboard
- Institution comparison
- Participant contribution analysis
- Feedback performance monitoring
- Training effectiveness evaluation

### 5. Alerts & Insights Dashboard
- Low coverage state identification
- Inactive region analysis
- Feedback warning indicators
- Performance monitoring insights

---

## 📈 Power BI Features Used

- KPI Cards
- Bar & Column Charts
- Line Charts
- Treemap
- Pie & Donut Charts
- GIS Maps
- Scatter Plot
- Matrix/Table Visuals
- Slicers & Filters
- Conditional Formatting
- DAX Measures

---

## 📌 Sample DAX Measures

### Total Trainings

```DAX
Total Trainings = COUNT(Training_Data[Training_ID])
```

### Total Participants

```DAX
Total Participants = SUM(Training_Data[Participants_Count])
```

### Average Feedback

```DAX
Average Feedback = AVERAGE(Feedback_Data[Feedback_Score])
```

### States Covered

```DAX
States Covered = DISTINCTCOUNT(Training_Data[State])
```

---

## 🌍 GIS Integration

The dashboard includes:
- Geographic training analysis
- State-wise training visualization
- Participant density mapping
- Regional preparedness insights

---

## 📷 Dashboard Screenshots

_Add your dashboard screenshots here._

Suggested screenshots:
- Executive Overview
- Geographic Analysis
- Theme Analytics
- Institution Performance
- Alerts Dashboard

---

## 🚀 Project Outcomes

- Improved visibility of disaster management training activities
- Enhanced monitoring of regional training coverage
- Better decision-making through analytics
- Identification of training gaps and inactive regions
- Real-time interactive reporting system

---

## 📚 Learning Outcomes

Through this project, the following skills were developed:
- Power BI Dashboard Development
- Data Modeling
- DAX Calculations
- Data Visualization
- GIS Analytics
- Business Intelligence
- Analytical Thinking
- Dashboard Storytelling

---

## 👨‍💻 Developed For

Smart India Hackathon (SIH) 2025

Problem Statement ID: 25258

---

## 📄 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this project with proper attribution.

See the `LICENSE` file for more details.
