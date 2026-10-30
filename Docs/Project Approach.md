# Project Approach - Customer Footfall Tracker
Author: Apollinaria Konstantinell

Project: Customer Footfall Tracker

Dataset: [Customer Footfall Tracker.xlsm](https://github.com/user-attachments/files/34156835/Customer.Footfall.Tracker.xlsm)

# 1. Objective
The initial objective of the project was to create visual proof of attendance and customer behaviour to broader senior management team of the venue, that could aid in cutting down time to do admit-predictions and team scheduling.
Focus then shifted to collecting the information in order to strengthen pattern prediction over time.

# 2. Dataset Overview
Source: Vista software (files not available)

Time Period: Q1 (January - March), 2026

Key Variables: 

* Screens with 30+ admits
* Operational hours: 11:00 - 23:00
* Days of the week: Friday - Thursday

# 3. Project Workflow 

### Step 1. Environment Setup (Worksheet: Footfall Data and Heatmap V1)
A table was set up. 
* Vertical axis: 11:00 until 00:00
* Horizontal axis: Friday - Thursday

### Step 2. Collection of data
Starting with January 1st 2026, using Vista scheduler I went through every screening for each day, adding a tally mark to the table for a screen above 30 admits in attendance. Ending on April 1st 2026.

### Step 3. Data Transformation (Worksheet: "Footfall Data and Heatmap V1")
Converted the tallies into numbers to enable Excel to read the data. 

### Step 4. Generated Heatmap 
For quicker result, a copilot heatmap was generated inorder to fit the timeline to enable discussion with the rest of senior management team.

### Step 5. Created Heatmap (Worksheet: "Footfall Heatmap V2")
*Recreated the table format from Step 1.
*Filled in the transformed data into the table.
*Applied Conditional Formatting.

Key Observation:
*Sunday peaks start at 13:00,  one hour earlier than Saturdays, and the last major peak at 17:00. 
*Monday and Thursday 19:00 and 20:00 showtimes have the same level of high-admit screenings as Friday prime time showings.


### Step 7. Dynamic Data Collection Matrix (Worksheets: Customer Footfall Heatmap, Active Footfall Matrix)
*Recreated the intial table.
*Applied conditional formatting.
*On a seprate sheet recreated the table, and populated it with check boxes.
*Connected the two worksheets with VBA script.
*Added a SUBMIT button.

# 4. Tools Used

| :Tool: | :Purpose: |
|---|---|
| :Excel: | :Collection and transformation of data: |
| :Copilot: | :Generation of heatmap: |
| :Conditional Formatting: | :Creation of final (static) heatmap: |
| :Internet: | :Aid and research to how to create and connect the active matrix to the heatmap: |
| :VBE: | :Connecting "Active Footfall Matrix" to "Customer Footfall Heatmap": |

# 5. Key Takeaways from the Approach
1. Data Collection - collecting and consolidating data from primary source (Vista cimena manager software).
2. Visualisation - created an easy to read format to effectively communicate with internal stakeholders.
3. Dynamic Matrix - built a data collection matrix to enable as-you-go data collection process.

# 6. Files Related to the Project
Full interactive Project: Workbook/Customer Footfall Tracker.xlsm
PDF:  xxx
Visualisation screenshots: xxx

##### This document outlines the structured analytical approach followed throughout the project.

