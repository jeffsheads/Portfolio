# Network Automation & Documentation System

This project is a collection of Python-based automation tools designed to eliminate manual network documentation and validation processes.

## Overview

This system automates the collection and documentation of network infrastructure data, replacing manual processes with a structured, repeatable workflow.

## Core Pipeline

### 1. Data Collection
**Repo:** IDF-Book-Data-Pull  
- Connects to network devices  
- Collects infrastructure data  
- Correlates device information with DNS  

### 2. Documentation Generation
**Repo:** IDF-Book-Generator  
- Processes collected data  
- Generates standardized PDF documentation per IDF  
- Produces consistent, repeatable outputs  

## Independent Tool

### 3. Validation & Reporting
**Repo:** KIVA-Check  
- Performs validation checks across systems  
- Verifies project status and system readiness  
- Generates structured reports (e.g., Excel) for operational tracking  

## Workflow

1. Collect network data from devices  
2. Process and generate documentation  

Validation and reporting tools operate independently for operational visibility.

## Key Features

- End-to-end automation of network documentation  
- Reduction of manual data collection and reporting  
- Improved consistency and accuracy of infrastructure records  
- Scalable and repeatable workflow design  

## Technologies Used

- Python  
- Bash  
- Network Device Interfaces (CLI/API)  
- Data Processing & Transformation  

## Purpose

This system was developed to automate network documentation (IDF books) and improve operational visibility in a large-scale enterprise environment.

It demonstrates practical application of automation to real-world infrastructure challenges.
