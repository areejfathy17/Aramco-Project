📊 Dynamic Evaluation & Performance Tracking System
📌 Project Overview

Developed for Ramco, this project is a Dynamic Performance Evaluation System designed to track, measure, and visualize departmental performance across multiple branches.

The system enables structured monitoring of Requirements and frequency-based Tasks (Monthly, Weekly, Quarterly), compares Annual Targets vs. Actual Performance, calculates completion rates automatically, and delivers a centralized interactive Executive Dashboard powered by a unified Data Model.

⚠️ Note: The dashboard screenshots included in this repository contain sample data for demonstration purposes only and do not represent actual company data.

🎯 Business Objective

The objective was to build a centralized and automated evaluation system that:

Allows each department to enter data independently (separate user input)

Consolidates all departments into a unified reporting structure

Eliminates manual calculations

Provides real-time KPIs and performance insights for management

🏗️ System Architecture

The system consists of four main layers:

1️⃣ Data Entry Layer

Separate input sheets for each department

Tasks linked to Requirements

Frequency-based tracking (Monthly / Weekly / Quarterly)

Data Validation lists for controlled and structured input

Dynamic annual and monthly targets

2️⃣ Annual Target Structure

Annual target points per Requirement

Monthly performance tracking

Dynamic lookup logic

Built-in error handling to prevent calculation issues

3️⃣ Data Processing – Power Query

Merging departmental tables

Grouping and aggregating performance points

Creating calculated columns

Handling null and division errors

Data type normalization and cleaning

Structuring data for reporting

4️⃣ Centralized Data Model

Connecting all departments and branches

Enabling cross-department reporting

Supporting dynamic Pivot Tables

Powering the unified Dashboard interface

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

Completed vs. Pending points analysis

Frequency-based task performance tracking

Department-level performance overview

🔹 Dynamic Filters (Slicers)

Department

Requirement

Task Frequency

The dashboard updates dynamically based on user selections.

⚙️ Tools & Technologies Used

Microsoft Excel

Power Query

Data Model (Relationships)

Pivot Tables

Calculated Fields / Measures

Data Validation

Dashboard UI & Performance Structuring
