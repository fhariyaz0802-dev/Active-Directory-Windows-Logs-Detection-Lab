# Active Directory + Windows Logs Detection Lab

## Overview
This project demonstrates Windows security monitoring using Event Viewer and Sysmon.

## Objectives
- Monitor Windows Security Logs
- Analyze successful logon events
- Analyze privileged logon events
- Monitor process creation activity
- Collect Sysmon telemetry

## Environment
- Windows 11 ARM VM (UTM)
- Sysmon
- Event Viewer

## Screenshots

### 1. Windows VM Setup
![Windows Setup](windows%20setup.png)


### 2. Sysmon Operational Log
![Operational Log](System%20Operational%20Log.png)

### 3. Process Creation Event (Event ID 1)
![Process Creation](Process%20creation.png)

### 4. Command Activity
![Command Activity](Command%20Activity.png)

### 5. Privileged Logon (Event ID 4672)
![Privileged Logon](Privileged%20Logon.png)

### 6. Successful Logon (Event ID 4624)
![Successful Logon](Successful%20Logon.png)

## Key Findings
- Sysmon successfully generated process creation logs.
- Event ID 4624 captured successful user logons.
- Event ID 4672 captured privileged logon activity.
- Command execution activity was visible through Sysmon logging.

## Skills Demonstrated
- Windows Security Monitoring
- Event Viewer Analysis
- Sysmon Configuration
- Log Analysis
- SOC Analyst Fundamentals
