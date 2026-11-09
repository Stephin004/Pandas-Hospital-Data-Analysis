# Hospital Data Analysis Using Python Pandas

## Project Overview

This project focuses on analyzing hospital appointment data using Python and Pandas. It combines patient, doctor, and appointment datasets to explore hospital operations, patient demographics, doctor performance, consultation revenue, and appointment trends.

The project demonstrates practical data analysis techniques, data manipulation, data aggregation, statistical analysis, and visualization.

## Objectives

- Understand and explore hospital datasets.
- Perform data inspection and identify missing or duplicate values.
- Merge patient, doctor, and appointment datasets.
- Analyze patient demographics and age distribution.
- Examine appointment status and monthly trends.
- Analyze doctor workloads and performance.
- Calculate consultation revenue by doctor and specialization.
- Explore relationships between patient age, doctor experience, and consultation fees.
- Identify useful insights through data visualization.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Jupyter Notebook / Google Colab | Interactive development |

## Dataset Description

This project uses three CSV datasets.

### 1. patients.csv

Contains patient-related information.

- Patient_ID
- Patient_Name
- Age
- Gender
- City

### 2. doctors.csv

Contains doctor-related information.

- Doctor_ID
- Doctor_Name
- Specialization
- Experience

### 3. appointments.csv

Contains hospital appointment information.

- Appointment_ID
- Patient_ID
- Doctor_ID
- Appointment_Date
- Consultation_Fee
- Status

## Project Structure

```text
Pandas-Hospital-Data-Analysis/
│
├── README.md
├── Pandas_Assignment.ipynb
├── patients.csv
├── doctors.csv
├── appointments.csv
└── requirements.txt
```

## Analysis Performed

### Part A – Data Understanding
- Dataset loading and exploration
- Shape, data types, and information
- Missing value identification
- Duplicate record checking
- Date conversion

### Part B – Data Integration
- Merging appointments with patient information
- Merging doctor information
- Creating a combined hospital dataset

### Part C – Hospital Overview
- Total appointment count
- Appointment status distribution
- Completed consultation revenue
- Average, highest, and lowest consultation fees
- Patient gender and city distribution

### Part D – Patient Analysis
- Patient age distribution
- Minimum, maximum, average, and median age
- Age categorization
- Patient distribution across cities
- Identification of repeat patients

### Part E – Doctor Analysis
- Appointments handled by each doctor
- Doctor workload comparison
- Completed revenue by doctor
- Doctor experience analysis

### Part F – Specialization Analysis
- Appointment distribution by specialization
- Revenue by specialization
- Average consultation fees
- Completed appointments by specialization

### Part G – Monthly Analysis
- Monthly appointment trends
- Monthly completed revenue
- Identification of highest revenue month
- Monthly cancelled appointments

### Part H – Appointment Status Analysis
- Appointment status counts and percentages
- Monthly appointment status comparison
- Cancelled appointments by doctor
- Cancelled appointments by specialization

### Part I – Relationship Analysis
- Patient age vs consultation fee
- Doctor experience vs appointment count
- Doctor experience vs consultation revenue
- Correlation analysis

### Part J – Data Visualization
- Patients by city
- Patient age distribution
- Appointments handled by doctor
- Completed revenue by specialization
- Monthly appointment trends
- Appointment status distribution
- Consultation fee distribution
- Outlier detection using box plots

### Part K – Final Analysis
- Hospital activity summary
- Patient demographic insights
- Doctor workload and revenue analysis
- Appointment trends
- Consultation fee analysis
- Business insights and observations

## Visualizations

The project uses Matplotlib to create:

- Bar charts
- Histograms
- Scatter plots
- Line charts
- Pie charts
- Box plots

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Stephin004/Pandas-Hospital-Data-Analysis.git
```

### 2. Navigate to the project folder

```bash
cd Pandas-Hospital-Data-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open `Pandas_Assignment.ipynb` using Google Colab or Jupyter Notebook.

Make sure all three CSV files are available in the working directory before executing the notebook.

## Key Learning Outcomes

- Practical experience with Pandas DataFrames.
- Data cleaning and preprocessing.
