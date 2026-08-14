<div align="center">
  
# 🏥 Hospital Management Data Analysis Project 🩺

![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-FF6F00?style=for-the-badge&logo=google-analytics&logoColor=white)

*A comprehensive end-to-end data analysis project focusing on hospital operations, database design, SQL querying, and Power BI visualization.*

</div>

---

## 📖 Overview

The **Hospital Management Data Analysis Project** is designed to simulate a real-world healthcare data environment. It provides a structured approach to understanding how a hospital system manages its core entities—such as patients, doctors, appointments, treatments, and billing. 

By taking raw mock datasets, this project builds a robust **Relational Database**, extracts meaningful business intelligence through **SQL Case Studies**, and presents the findings through an interactive **Power BI Dashboard**.

## 🎯 Objectives
- **Database Architecture**: Design a logical flow of information using ERDs and Data Flow Diagrams.
- **Data Management**: Handle, clean, and structure raw CSV data into a MySQL relational database.
- **Business Intelligence**: Solve real-world healthcare questions using advanced SQL queries.
- **Data Visualization**: Provide high-level stakeholders with intuitive, colorful, and interactive dashboards to track hospital performance.

---

## 🗂️ Dataset Details

The project utilizes five core datasets (in CSV format) representing different facets of hospital operations:

| Dataset | Description | Key Attributes |
| :--- | :--- | :--- |
| 🧑‍⚕️ **`patient.csv`** | Demographics and insurance details of patients. | `patient_id`, `name`, `DOB`, `insurance_provider` |
| 👨‍⚕️ **`doctors.csv`** | Information on medical professionals. | `doctor_id`, `specialization`, `experience` |
| 📅 **`appointment.csv`** | Records of when patients meet doctors. | `appointment_id`, `patient_id`, `date`, `status` |
| 💊 **`treatments.csv`** | Specific medical procedures administered. | `treatment_id`, `appointment_id`, `treatment_name` |
| 💳 **`billing.csv`** | Financial data related to patient care. | `billing_id`, `patient_id`, `amount`, `payment_status` |

---

## 🏗️ Architecture & System Design

To ensure a robust underlying structure, the project includes complete system design blueprints:
- 🗺️ **Entity-Relationship Diagram (`ER-DIAGRAM.jpg`)**: Shows the relationships and cardinalities between Patients, Doctors, Appointments, Treatments, and Billing tables.
- 👥 **Use Case Diagram (`USE CASE DIAGRAM .jpg`)**: Maps out how different actors (Admin, Doctor, Patient) interact with the hospital system.
- 🔄 **Data Flow Diagrams (`DFD LEVEL 0.jpg` & `DFD LEVEL 1.jpg`)**: Illustrates how data moves through the system processes from input to output.

---

## 💻 SQL Case Studies & Analysis

A core component of this project is the `SQL QUERY AND OUTPUT` file. It features complex SQL queries written to solve business case studies, such as:
1. **High-Value Patients**: Identifying patients spending above the average billing amount on specific specializations (e.g., Dermatology).
2. **Doctor Performance**: Analyzing appointment frequencies and successful treatments per doctor.
3. **Revenue Tracking**: Aggregating financial data to understand peak revenue periods and insurance utilization.

*(Visual proofs of the outputs are available in the `MySql Output Snapshot/` directory).*

---

## 📊 Data Visualization (Power BI)

Raw data is transformed into actionable insights using **Microsoft Power BI**. 
The repository includes:
- 📈 **`Visulization.pbix`**: The fully interactive Power BI dashboard file.
- 🖼️ **`Visualization Dashboard Picture.jpg`**: A quick-glance screenshot of the final dashboard.

**Key Dashboard Metrics:**
- Total Revenue & Billing trends over time.
- Patient demographic breakdown (Age/Gender).
- Most common treatments and popular doctor specializations.

---

## 🚀 Future Scope

This project sets a strong foundation for hospital data management, but it can be expanded in several exciting ways:
- [ ] **Predictive Analytics**: Implementing Machine Learning models to predict patient no-show rates or disease outbreaks based on historical data.
- [ ] **Real-Time Data Pipeline**: Upgrading from static CSVs to a cloud-based automated pipeline using AWS/Azure and Apache Airflow.
- [ ] **Inventory Management**: Adding modules to track hospital equipment, bed availability, and pharmacy stock.
- [ ] **Advanced Security**: Implementing Data Masking for sensitive patient PII (Personally Identifiable Information) in compliance with HIPAA guidelines.
- [ ] **Web Application**: Building a front-end dashboard (React/Next.js) connected directly to the MySQL database.

---

## 🛠️ How to Use

1. **Setup Database**: Create a database named `Hospital_Management_Data` in MySQL.
2. **Import Data**: Import the provided `.csv` files into their respective tables.
3. **Run Queries**: Open `SQL QUERY AND OUTPUT` and execute the queries to see the analysis.
4. **View Dashboard**: Open `Visulization.pbix` in Power BI Desktop to explore the charts.

---
<div align="center">
  <b>Built with ❤️ for Data Analytics & Healthcare Technology</b>
</div>
