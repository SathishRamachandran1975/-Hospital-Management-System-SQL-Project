## 🏥Hospital Management System SQL Project
“Hospital Management System using SQL” is a hands-on project designed to simulate the operations of a multi-department hospital. 
It leverages SQL to model real-world workflows like patient admissions, appointments, billing, medical records, staff management, 
and more. The project showcases robust schema design, data integration, advanced query logic, reporting views, and stored procedures.

## 📌Project Objective
To design and analyze a relational database system for hospital operations using SQL. The aim is to streamline hospital workflows such 
as patient treatment, doctor scheduling, admissions, billing, and resource utilization, enabling administrators to make data-driven decisions.

## 📋Tasks Performed
 - Database Design & Schema Creation
      * Structured 10+ interrelated tables: patients, doctors, departments, rooms, appointments, medicalrecords, admissions, billing, staff, etc.
 - Sample Data Insertion
      * Populated realistic dummy data to mimic hospital activities including appointments, treatments, billing, and discharges.
 - Views for Reporting
      * Created SQL views such as vw_ActivePatients, vw_DoctorSchedule, and vw_FinancialSummary.
 - Stored Procedures
      * Implemented dynamic procedures for:
            * Patient admission (sp_AdmitPatient)
            * Scheduling appointments (sp_ScheduleAppointment)
            * Billing generation (sp_GeneratePatientBill)
            * Patient discharge (sp_DischargePatient)
  - Advanced SQL Queries
       * Queries for:
            * Patient history and billing
            * Departmental statistics
            * Room utilization
            * Doctor performance
            * Admission trends

## 📊Key Insights
  - ICU and Private rooms show highest occupancy rates.
  - Certain departments (e.g., Emergency, Cardiology) handle more admissions and billing volume.
  - Regular patients contribute significantly to hospital revenue.
  - Staff salaries vary widely across departments.
  - Seasonal spikes in admissions and billing occur in July and August.

## 📈Key Performance Indicators (KPIs)
KPI	Description
| KPI                         | Description                                                 |
|----------------------------|-------------------------------------------------------------|
| 🛏️ Room Occupancy Rate      | % of occupied vs. total rooms per room type                 |
| 👩‍⚕️ Doctor Appointment Analysis | Count of total, completed, no-shows, and canceled appointments |
| 💰 Total Billing           | Revenue generated per department/month                     |
| 📅 Admission Trends        | Monthly count of patient admissions                        |
| 📦 Average Stay Duration   | Avg. length of stay per patient                            |
| 👥 Department Staff Stats  | Total staff and salary distribution                        |
| 💳 Collection Rate         | Percentage of paid vs. billed amount                       |


## 🗃️SQL File Structure
|| <a href ="https://github.com/SathishRamachandran1975/-Hospital-Management-System-SQL-Project/blob/main/Hospital%20Management%20System%20SQL-Project.sql">SQL_FILE</a> ||
<a href ="https://github.com/SathishRamachandran1975/-Hospital-Management-System-SQL-Project/blob/main/Hospital%20Management%20System%20SQL-Project.pdf">SQL_PDF</a>  ||
<a href ="https://github.com/SathishRamachandran1975/-Hospital-Management-System-SQL-Project/blob/main/HOSPITAL%20MANAGEMENT%20SYSTEM.pptx">SQL_PPT</a> ||
- Database & Tables
    - `CREATE` scripts for all major hospital entities
- Sample Data
    - `INSERT` statements for patients, doctors, rooms, etc.
- Core Queries
    - Appointment, billing, and admission analytics
- Views
    - `vw_ActivePatients`, `vw_DoctorSchedule`, `vw_FinancialSummary`
- Stored Procedures
    - Modular logic for hospital workflows
 
## ⚙️Process Overview
  - The development of this Hospital Management System project followed a structured step-by-step process:
       1. Design Schema  
               - Created a well-normalized relational database schema including all major hospital entities such as patients, doctors,
                 departments, appointments,rooms, admissions, and billing.
       2. Insert Data  
               - Populated the tables with realistic sample data to simulate real hospital operations — including patient registrations,
                 staff details, appointments, admissions, medical records, and payment transactions.
       3. Execute Queries  
               - Wrote SQL queries to extract meaningful information — such as room occupancy, admission trends, doctor performance, patient
                 billing summaries, and more.
       4. Create Views & Procedures  
               - Built SQL views for reusable reports and stored procedures to automate key operations like patient admissions, appointment
                 scheduling, billing, and discharge processing.
       5. Analyze Insights  
               - Leveraged data from the queries and views to generate insights into hospital efficiency, revenue generation, patient activity,
                 and resource utilization — supporting strategic decision-making.
 
 ## 🧬Database Schema Diagram
 - The relational schema reflects real-world hospital operations. It is fully normalized with the following key entities:
    - patients – Basic patient details and contact info
    - departments – Hospital units like Cardiology, Emergency, etc.
    - doctors – Specialist profiles linked to departments
    - appointments – Scheduled consultations with status tracking
    - medicalrecords – Diagnoses, treatments, prescriptions
    - rooms – ICU, General, Private, Emergency, OT
    - admissions – Room assignments and discharge records
    - billing – Patient billing with payment statuses
    - staff – Non-doctor employees including nurses, receptionists
- Relationships:
    - 1:N between patients and appointments/admissions
    - 1:N between doctors and appointments/records
    - 1:N between departments and doctors/rooms/staff
    - N:1 from admissions to rooms
    - N:1 from billing to admissions and patients

## 📌Click to View:
-<a href ="https://github.com/SathishRamachandran1975/-Hospital-Management-System-SQL-Project/blob/main/Hospital%20Management%20System%20Schema%20Diagram.pdf">SCHEMEA_FILE</a>

-<a href ="https://github.com/SathishRamachandran1975/-Hospital-Management-System-SQL-Project/blob/main/Hospital%20Management%20System%20Schema%20Diagram_page-0002.jpg">SCHEMA_DIAGRAM</a>

## 🏁Final Conclusion
  - This SQL-based Hospital Management System demonstrates a complete digital workflow for a multi-department hospital. From patient admissions
    and appointments to medical records and billing, the project showcases how relational databases and advanced SQL logic can power data-driven
    healthcare administration. Through interactive views, automation via stored procedures, and deep performance queries, it builds a strong
    foundation for real-time hospital dashboards and operational reporting.



