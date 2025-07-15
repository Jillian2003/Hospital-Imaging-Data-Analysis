# Hospital Enterprise Imaging Operations Dashboard
---
## Dataset

**Source:** Enterprise Imaging Operations - Incident and Service Request Data (2022-2024)  

---

## Objective

Analyze trends regionally and at the hospital level to gain insights into IT service management performance for imaging systems.

---

## Key Features of the Dataset

- **Date Reported:** When the incident or request was created.
- **Category:** Incident (unplanned disruption) vs. Service Request (standard service request).
- **System Affected:** PACS (Picture Archiving and Communication Systems), RIS (Radiology Information Systems), VNA (Vendor Neutral Archives), DICOM (Digital Imaging and Communications in Medicine), Radiology Workstations, etc.
- **Hospital Location & Region**
- **Resolution Time:** Total time taken to resolve the issue.

---

## Project Steps

1. **Data Acquisition:** Obtain the dataset from Enterprise Imaging Operations.
2. **Data Cleaning and Preparation:** Use Python (Pandas) to clean and standardize the data.
3. **Data Analysis:** Identify trends in IT incidents and service requests.
4. **Data Visualization:** Use Tableau to develop reports and dashboards.
5. **Reporting:** Compile insights and recommendations.

---

## Data Cleaning and Preparation

- Handle missing values and inconsistencies.
- Remove duplicate records.
- Standardize date and time formats.
- Normalize categorical variables.
- **Priority:** Remove confidential information (employee/patient names).

<img width="1021" height="872" alt="Screenshot 2025-06-30 101255" src="https://github.com/user-attachments/assets/747047a1-39bc-4cae-a5c1-12b8721c0f84" /> 
<img width="1283" height="824" alt="Screenshot 2025-06-30 101331" src="https://github.com/user-attachments/assets/db7a1054-8f19-4a3f-99dc-a5d97da326d4" />

---

## Data Analysis Breakdown

- **Regional Incident Trends:** Identify the most frequent imaging system issues by region and hospital.
- **Service Performance:** Analyze average resolution times across different locations.
- **Hospital Comparisons:** Identify hospitals and regions with the highest incident volume.
- **Recurring Issues:** Determine if certain failures are repeated.

---

## Key Insights

### Total Tickets & Ticket Distribution

- **Total Tickets:** 75,991  
    - Service Requests: 47,073  
    - Incidents: 28,918  
- Service requests outnumber incidents, indicating routine maintenance/support is more frequent, though critical failures still occur.

### Year with the Most Tickets

- **2022:** 27,547 tickets (highest volume)
    - Possible causes: new system launches, equipment malfunctions, protocol changes, staffing impacts.

### Month with the Most Tickets

- **March:** 2,773 tickets (peak)
    - Potential causes: seasonal demand spikes or widespread failures.

---

## Service Request Analysis Breakdown

### Top Regions for Service Requests

- Orange: 4,470 tickets
- East Orange: 3,986 tickets
- Mid-Amelia: 3,899 tickets
- Dragonwood: 3,362 tickets
- North Orange: 3,198 tickets

*Possible causes: high patient volumes, system concentration, or inadequate proactive maintenance.*

### Hospitals with the Most Service Requests

- Shawnee Regional Hospital: 2,727 tickets
- Orange Hospital: 2,601 tickets
- Wondergroove Women's Hospital: 1,908 tickets
- VAGA Victoria Medical Park: 1,892 tickets
- Timberland Medical: 1,702 tickets

*Indicates either high usage/complexity or need for staff training in technical issue management.*

### Priority-Based Service Request Analysis

| Priority       | Closed Tickets | Cancelled Tickets | Rejected Tickets |
|----------------|---------------|-------------------|------------------|
| Low            | 45,194        | 430               | 14               |
| Medium         | 835           | 12                | -                |
| High           | 578           | 9                 | -                |
| Critical       | -             | 1                 | -                |

*Most tickets are low priority, showing routine issues are common, but higher priority tickets underscore the need for strong IT systems.*

---

## Incident Analysis Breakdown

### Top Regions for Incidents

- Orange: 8,018 tickets
- East Orange: 3,042 tickets
- Overlong: 2,613 tickets
- Algrove: 1,936 tickets
- Gardner Woods: 1,521 tickets

*Orange region stands out for systemic issues or heavy system usage.*

### Hospitals with the Most Incident Requests

- Orange Hospital  
- Celebration Hospital  
- Solutions Center Hospital  
- East Orange Hospital  
- Algrove General Hospital  

*Orange Hospital has especially high incident rates (notably for PACS), suggesting frequent failures or monitoring gaps.*

### Priority-Based Incident Analysis

| Priority       | Closed Tickets | Cancelled Tickets |
|----------------|---------------|-------------------|
| Low            | 12,530        | 1,210             |
| Medium         | 13,960        | 549               |
| High           | 646           | 22                |
| Critical       | 1             | -                 |

---

## Recommendations

### 1. Focus on High-Ticket Regions and Hospitals

- Orange Region and Orange Hospital should be prioritized for more IT support, training, and proactive maintenance.
- Consider increased staffing and automated monitoring tools.

### 2. Review and Improve IT Support Response Times

- Regions like AIT Enterprise Imaging Apopka and FHPG Brandon with slow resolution times need targeted reviews and possible upgrades.

### 3. Implement Preventive Maintenance

- High incident volumes (especially in Orange) require preventive strategies: regular maintenance, health checks, predictive analytics.

### 4. Enhance Training for Staff

- High-volume hospitals (e.g., AH Orlando, AH Altamonte) may benefit from additional technical training to reduce ticket volumes.

### 5. Improve Regional Focus and Data-Driven Decision Making

- Drill down into data for high-incident regions to identify root causes and enable targeted, efficient resource allocation.

---

## Dashboard

https://public.tableau.com/app/profile/jillian.ireland/viz/HospitalEnterpriseImagingOperationsDashboard/Overview

<img width="1920" height="1112" alt="Screenshot 2025-06-30 142426" src="https://github.com/user-attachments/assets/6573adc6-9ece-45b3-be59-ef3637108a4d" />

<img width="1920" height="1109" alt="Screenshot 2025-06-30 142437" src="https://github.com/user-attachments/assets/8f0efd2a-de23-44f8-b6da-02fe31b9bd1f" />

<img width="1920" height="1106" alt="Screenshot 2025-06-30 142447" src="https://github.com/user-attachments/assets/099ef5b2-53b7-41ef-8f82-80808a59c23c" />

