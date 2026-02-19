Dynamic Evaluation & Performance Tracking System
📌 Project Overview

This project is a Dynamic Performance Evaluation System built to track, measure, and visualize departmental performance across multiple branches.

The system was designed to:

Monitor Requirements across departments

Track Tasks based on frequency (Monthly, Weekly, Quarterly)

Compare Annual Targets vs. Actual Performance

Calculate completion rates automatically

Provide a fully interactive Executive Dashboard

⚠️ Note: The dashboard screenshots included in this repository contain sample data for demonstration purposes only and do not represent real company data.

🎯 Business Objective

The goal was to create a centralized, automated system that:

Allows each department to enter data independently (separate user input)

Consolidates all departments into a unified reporting model

Eliminates manual calculations

Provides management with real-time KPIs and performance insights

🏗️ System Architecture

The project consists of 4 main layers:

1️⃣ Data Entry Layer

Separate input sheets for each department

Tasks linked to Requirements

Frequency-based tracking (Monthly / Weekly / Quarterly)

Data Validation lists for controlled input

Dynamic annual & monthly targets

2️⃣ Annual Target Structure

Annual target points per Requirement

Monthly tracking

Dynamic lookup logic

Error handling to prevent calculation failures

3️⃣ Data Processing – Power Query

Data transformation was handled using Power Query, including:

Merging departmental tables

Grouping and aggregating points

Creating calculated columns

Handling null and division errors

Data type normalization

Cleaning and structuring for reporting

4️⃣ Data Model

A centralized Data Model was created to:

Connect all departments and branches

Enable cross-department reporting

Build dynamic Pivot Tables

Power the unified Dashboard

This allowed the dashboard to track all departments from a single reporting interface.

📊 Dashboard Features
🔹 KPI Summary Bar

% Requirements Completion

Total Annual Points

Total Completed Points

Total Pending Points

Total Completed Tasks

Total Pending Tasks

🔹 Interactive Visualizations

Requirement completion comparison

Completed vs Pending points

Frequency-based task analysis

Department-level performance tracking

The dashboard updates dynamically based on selections.

⚙️ Tools & Technologies Used

Microsoft Excel

Power Query

Data Model (Relationships)

Pivot Tables

Calculated Fields / Measures

Data Validation

Dashboard Design & UI Structuring

🚀 Key Achievements

Fully automated annual & monthly performance tracking

Multi-user department input system

Centralized reporting model

Error-free calculation structure

Executive-ready interactive dashboard
