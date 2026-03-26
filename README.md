# Network Automation Portfolio

This portfolio highlights automation solutions designed to eliminate manual processes and improve visibility across network and operational environments.

## Projects

---

### Network Documentation Automation Pipeline

A two-part system designed to automate the collection and documentation of network infrastructure data.
> Eliminates manual network documentation by automating data collection and standardized output generation.

**Repositories:**
- [IDF-Book-Data-Pull](https://github.com/jeffsheads/IDF-Book-Data-Pull)
- [IDF-Book-Generator](https://github.com/jeffsheads/IDF-Book-Generator)

#### Components

**Data Collection**
- IDF-Book-Data-Pull  
- Interfaces with network devices to collect infrastructure data    
- Correlates device information with DNS  

**Documentation Generation**
- IDF-Book-Generator  
- Transforms collected data into structured, usable formats  
- Generates standardized PDF documentation per IDF  

#### Purpose
This pipeline replaces manual network documentation processes with a structured, repeatable workflow, improving consistency and reducing manual effort.

```mermaid
graph TD
A[Data Pull] --> B[Processing]
B --> C[PDF Generation]

---

### Workstation Validation & Reporting Tool

**Repo:** [KIVA-Check](https://github.com/jeffsheads/KIVA-Check)

A standalone automation tool designed to validate workstation status and generate reports for operational coordination.
> Provides real-time visibility into system readiness, reducing manual tracking and simplifying coordination effort.

#### What It Does
- Performs validation checks across multiple systems  
- Verifies project status and system readiness  
- Generates structured reports (e.g., Excel) for operational decision-making 

#### Purpose
Provides visibility into system readiness and supports coordination between IT, operations, and maintenance teams.

---

## Technologies Used

- Python  
- Bash  
- Network Device CLI / API Interaction  
- Data Processing & Reporting  

---

## Summary

These projects demonstrate practical application of automation to:
- Replace manual processes  
- Improve operational visibility  
- Standardize infrastructure documentation
