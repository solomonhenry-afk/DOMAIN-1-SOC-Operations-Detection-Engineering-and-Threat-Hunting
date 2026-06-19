# LIGHTHOUSE TECHNOLOGY

# DOMAIN 1 — SOC OPERATIONS, DETECTION ENGINEERING & THREAT HUNTING

## Enterprise Security Operations Engineering Program

This project demonstrates the design, deployment, validation, and operationalization of an enterprise-scale Security Operations Center (SOC) environment focused on telemetry engineering, detection engineering, threat hunting, authentication monitoring, PowerShell visibility, Sysmon engineering, firewall telemetry integration, and MITRE ATT&CK-aligned security operations.

The objective was to simulate how modern enterprise security teams build visibility, engineer detections, investigate activity, validate telemetry, and proactively hunt for adversary behavior across enterprise environments.

---

# PROJECT OBJECTIVES

This project was designed to answer critical security operations questions:

* What telemetry is available across enterprise systems?
* How can security events be normalized and operationalized?
* Which attacker behaviors are visible to defenders?
* How effective are enterprise detections?
* How can ATT&CK-aligned monitoring improve security operations?
* How can threat hunting identify suspicious activity before alerts occur?

---

# TECHNOLOGY STACK

## Security Operations

* Splunk Enterprise
* Splunk Universal Forwarder
* Detection Engineering
* Threat Hunting
* Security Analytics

## Infrastructure

* Windows Server 2019
* Windows 10 Enterprise
* Active Directory
* DNS Services
* VirtualBox

## Endpoint Visibility

* Sysmon
* Windows Event Logging
* PowerShell Logging

## Network Security

* pfSense Firewall
* Syslog
* Enterprise Telemetry Pipelines

## Frameworks

* MITRE ATT&CK
* Security Operations Center (SOC)
* Detection Engineering
* Threat Hunting Methodology

---

# DOMAIN 1 TASKS

## Task 1 - Splunk Infrastructure Deployment

Designed and deployed a centralized SIEM platform capable of ingesting enterprise security telemetry from Windows endpoints and infrastructure systems.

### Key Outcomes

* Splunk Enterprise deployment
* Index validation
* Search functionality verification
* Enterprise monitoring foundation established

---

## Task 2 - Universal Forwarder Deployment

Configured endpoint telemetry forwarding from enterprise systems into the Splunk environment.

### Key Outcomes

* Forwarder deployment
* Secure telemetry transport
* Endpoint onboarding
* Data pipeline validation

---

## Task 3 - Enterprise Telemetry Pipeline Validation

Validated enterprise log ingestion and monitoring coverage.

### Key Outcomes

* Source validation
* Host validation
* Event verification
* Log normalization assessment

---

## Task 4 - Authentication & Security Log Visibility

Operationalized authentication monitoring across enterprise systems.

### Event IDs Validated

* 4624 — Successful Logons
* 4634 — Logoff Events
* 4648 — Explicit Credential Usage
* 4672 — Special Privileges Assigned

### Security Operations Coverage

* Authentication monitoring
* Credential visibility
* Privileged access monitoring
* Identity activity analysis

---

## Task 5 - PowerShell Logging Engineering

Enabled advanced PowerShell visibility to support detection engineering and threat hunting operations.

### Event IDs Validated

* 4103 — Module Logging
* 4104 — Script Block Logging

### Security Operations Coverage

* PowerShell visibility
* Administrative scripting visibility
* Reconnaissance detection
* Script execution monitoring

---

## Task 6 - Sysmon Engineering

Deployed Sysmon across enterprise endpoints to provide advanced endpoint telemetry.

### Event IDs Validated

* Event ID 1 - Process Creation
* Event ID 4 - Sysmon Service State
* Event ID 11 - File Creation
* Event ID 12 - Registry Object Create/Delete
* Event ID 13 - Registry Value Modification
* Event ID 16 - Sysmon Configuration Changes
* Event ID 22 - DNS Queries

### Security Operations Coverage

* Process monitoring
* DNS visibility
* Endpoint telemetry engineering
* Threat detection enrichment

---

## Task 7 - pfSense Telemetry Engineering

Integrated enterprise firewall telemetry into the monitoring environment.

### Key Outcomes

* Syslog forwarding
* UDP 514 validation
* Remote logging
* Firewall telemetry ingestion

### Security Operations Coverage

* Network visibility
* Firewall analytics
* Connection monitoring
* Infrastructure telemetry

---

## Task 8 - Detection Engineering

Developed ATT&CK-aligned detections using enterprise telemetry sources.

### Detection Use Cases

* Authentication monitoring
* Credential usage monitoring
* Privilege escalation monitoring
* PowerShell activity monitoring
* Process creation monitoring
* DNS monitoring
* Firewall activity monitoring

### Outcome

Operationalized enterprise detection engineering workflows supported by a custom Splunk SOC dashboard.

---

## Task 9 - MITRE ATT&CK Mapping

Mapped enterprise detections to real-world adversary techniques.

### ATT&CK Coverage

* T1078 - Valid Accounts
* T1068 - Privilege Escalation
* T1059.001 - PowerShell
* T1059 - Command Execution
* T1106 - Native API
* T1218 - Signed Binary Proxy Execution
* T1071.004 - DNS
* T1046 - Network Service Discovery
* T1021 - Remote Services
* T1087 - Account Discovery
* T1087.002 - Domain Account Discovery
* T1016 - System Network Configuration Discovery

### Outcome

Established ATT&CK-aligned detection coverage across enterprise telemetry sources.

---

## Task 10 - Threat Hunting

Executed proactive threat hunting operations using enterprise telemetry and ATT&CK-aligned methodologies.

### Threat Hunts Conducted

* Authentication Abuse Hunt
* Privilege Escalation Hunt
* PowerShell Reconnaissance Hunt
* Account Discovery Hunt
* Domain Reconnaissance Hunt
* Process Creation Hunt
* DNS Activity Hunt
* Endpoint Activity Hunt

### Outcome

Validated the ability to proactively identify attacker behaviors using enterprise telemetry rather than relying solely on alerts.

---

# ENTERPRISE SECURITY DOMAINS DEMONSTRATED

## Security Operations

* SOC Operations
* Detection Engineering
* Threat Hunting
* Security Monitoring
* Incident Investigation

## Detection Engineering

* ATT&CK Mapping
* Correlation Development
* Detection Validation
* Detection Tuning

## Endpoint Visibility

* Sysmon Engineering
* PowerShell Visibility
* Windows Security Monitoring

## Identity Security

* Authentication Monitoring
* Privileged Access Visibility
* Credential Usage Monitoring

## Network Visibility

* Firewall Telemetry
* Syslog Integration
* Enterprise Telemetry Pipelines

---

# PROJECT OUTCOME

Successfully designed and operationalized a complete enterprise security monitoring environment capable of supporting:

* Security Operations Center workflows
* Detection Engineering programs
* ATT&CK-aligned monitoring
* Threat Hunting operations
* Authentication monitoring
* Endpoint visibility
* Firewall telemetry analysis
* Incident investigation activities

This project serves as the foundation for future Lighthouse Technology domains focused on adversary validation, purple teaming, network security engineering, identity resilience, cloud security engineering, and security automation.

---

## DOMAIN 1 STATUS

COMPLETE
