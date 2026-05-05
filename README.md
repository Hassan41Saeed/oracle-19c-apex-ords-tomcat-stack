# Oracle 19c + APEX + ORDS + Tomcat: Enterprise Stack

## Project Overview
This repository provides a Standard Operating Procedure (SOP) for building a production-ready Oracle APEX environment on **Oracle Linux 8**. It moves beyond basic installations by focusing on **Silent/Automated deployments** and a strictly organized **OFA-compliant directory structure**.

## Technical Components
- **Database:** Oracle Database 19c (Standalone)[cite: 2]
- **Platform:** Oracle APEX (installed in SYSAUX)[cite: 2]
- **Mid-Tier:** Oracle REST Data Services (ORDS)[cite: 2]
- **Web Server:** Apache Tomcat 9 (listening on Port 8085)[cite: 2]

## Automation & Efficiency
I have included custom scripts to handle the most tedious parts of the installation:
- **Silent ORDS Setup:** A bash script to handle the configuration and WAR generation without a GUI[cite: 2].
- **Service Management:** A systemd unit file to ensure Tomcat starts automatically on boot[cite: 2].
- **Path Optimization:** A standardized directory layout (`/opt/app/oracle/`) for maximum maintainability[cite: 2].

## Documentation
The complete, step-by-step Standard Operating Procedure is available here:
[**Download Oracle APEX Installation SOP**](./docs/Oracle_19c_APEX_ORDS_Tomcat_SOP.pdf)

## Architecture
<img width="1408" height="768" alt="Apex_infra" src="https://github.com/user-attachments/assets/4c4d6bf5-1e82-42e6-bd6f-1d13a173b1fd" />


