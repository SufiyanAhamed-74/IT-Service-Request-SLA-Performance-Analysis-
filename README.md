# IT Service Request & SLA Performance Analysis

## 📌 Project Overview

This project analyzes IT service requests to evaluate service performance, request fulfillment, SLA compliance, resolution time, and operational bottlenecks.

An interactive Power BI dashboard was developed to provide visibility into service request volume, backlog, priorities, SLA performance, request categories, and assigned team performance.

The project demonstrates practical understanding of IT Service Management (ITSM) concepts such as Service Request Management, SLA Management, request fulfillment, KPI monitoring, and continuous service improvement.

---

## 🎯 Objectives

- Monitor overall IT service request volume and trends
- Analyze request categories and priorities
- Track open, closed, and in-progress requests
- Measure SLA compliance and SLA breaches
- Analyze resolution time and service performance
- Compare performance across assigned teams
- Identify recurring request patterns
- Identify operational bottlenecks and areas for improvement

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **CSV Dataset**

---

## 📊 Dataset

The dataset contains **3,000 IT service request records**.

### Key Fields

| Field | Description |
|---|---|
| Ticket_ID | Unique service request identifier |
| Request_Date | Date when the request was created |
| Request_Category | Category of the service request |
| Priority | Priority level of the request |
| Department | Requesting department |
| Assigned_Team | Team responsible for handling the request |
| Channel | Request submission channel |
| Status | Current request status |
| SLA_Target_Hours | Target resolution time |
| Resolution_Date | Date when the request was resolved |
| Resolution_Time_Hours | Time taken to resolve the request |
| SLA_Status | Whether the SLA was met or breached |
| Customer_Satisfaction | Customer satisfaction score |

---

## 🔄 Data Preparation

Data preparation was performed using **Power Query**.

### Steps performed:

- Reviewed dataset structure and data types
- Converted date and numeric fields to appropriate formats
- Checked missing and inconsistent values
- Prepared fields required for SLA and performance analysis
- Created a clean dataset for Power BI modeling

---

## 📈 Dashboard KPIs

The dashboard focuses on key IT service management metrics:

- Total Service Requests
- Open Requests
- Closed Requests
- In-Progress Requests
- SLA Compliance %
- SLA Breach Count
- Average Resolution Time
- Average Customer Satisfaction

---

## 📊 Dashboard Analysis

### 1. Service Request Overview

Provides an overall view of service request performance.

Key analysis includes:

- Request volume
- Request status
- Monthly request trends
- Request priority
- Request categories
- Department-wise request distribution

### 2. SLA & Performance Analysis

Focuses on service-level performance.

Key analysis includes:

- SLA compliance
- SLA breaches
- SLA performance by priority
- Resolution time by assigned team
- Resolution time by request category
- Requests exceeding SLA targets

### 3. Process Improvement Analysis

Used to identify potential operational improvement areas.

Analysis includes:

- High-volume request categories
- Recurring request patterns
- Teams handling high request volumes
- Categories with longer resolution times
- SLA breach contributors
- Request backlog and aging

---

## 🧮 DAX Measures

Example measures created for the dashboard include:

```DAX
Total Requests =
COUNTROWS('IT Service Requests')
