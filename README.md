# Task 3 - Vulnerability Assessment Using Nessus

## Objective

The objective of this task was to perform a vulnerability assessment on a local system using Nessus Essentials and identify potential security issues.

## Tools Used

* Nessus Essentials
* Windows 11
* GitHub

## About Nessus

Nessus is a vulnerability assessment tool developed by Tenable. It is used by security professionals to identify vulnerabilities, misconfigurations, exposed services, and potential security risks within systems and networks.

## Scan Configuration

* Scan Type: Basic Network Scan
* Target: 127.0.0.1 (Localhost)
* Scanner: Local Scanner
* CVSS Version: CVSS v3.0

## Procedure

1. Installed and configured Nessus Essentials.
2. Updated Nessus plugins and vulnerability database.
3. Created a Basic Network Scan.
4. Configured localhost (127.0.0.1) as the scan target.
5. Executed the scan and waited for completion.
6. Reviewed and analyzed the scan results.
7. Documented findings and recommendations.

## Results

The scan completed successfully and identified several informational findings related to:

* SMB Services
* SSL Configuration
* TLS Configuration
* HTTP Services
* Service Detection
* OS Identification
* Port Enumeration

No Critical, High, Medium, or Low severity vulnerabilities were detected.

## Learning Outcomes

* Understanding vulnerability assessment processes.
* Working with Nessus Essentials.
* Identifying network services and configurations.
* Interpreting vulnerability scan reports.
* Learning security assessment methodologies.

## Repository Structure

├── README.md

├── Report.md

└── screenshots/

```
├── scan_setup.png

├── scan_summary.png

├── vulnerabilities.png
```

## Conclusion

This task provided practical experience with vulnerability assessment and security analysis using an industry-standard cybersecurity tool.
