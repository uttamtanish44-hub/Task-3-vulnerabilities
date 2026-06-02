# Vulnerability Assessment Report Using Nessus

## 1. Introduction

Vulnerability assessment is the process of identifying, analyzing, and evaluating security weaknesses within a system or network. In this task, Nessus Essentials was used to assess the security posture of a local machine.

## 2. Objective

To perform a vulnerability scan on a local system using Nessus Essentials and analyze the findings.

## 3. Tool Used

### Nessus Essentials

Nessus Essentials is a free vulnerability assessment tool developed by Tenable. It helps identify security weaknesses, exposed services, outdated software, and configuration issues.

## 4. Scan Details

| Parameter     | Value                   |
| ------------- | ----------------------- |
| Scan Type     | Basic Network Scan      |
| Target        | 127.0.0.1               |
| Scanner       | Local Scanner           |
| Status        | Completed               |
| Scan Duration | Approximately 7 Minutes |

## 5. Methodology

### Step 1: Installation

Nessus Essentials was downloaded and installed on a Windows system.

### Step 2: Configuration

A Basic Network Scan template was selected and configured with localhost (127.0.0.1) as the target.

### Step 3: Scanning

The scan was launched using Nessus Essentials.

### Step 4: Analysis

The results were reviewed to identify vulnerabilities and security-related information.

## 6. Findings

The scan reported multiple informational findings including:

* SMB (Multiple Issues)
* SSL (Multiple Issues)
* TLS (Multiple Issues)
* HTTP (Multiple Issues)
* Service Detection
* OS Identification
* Port Enumeration
* Device Identification

### Severity Summary

| Severity      | Count |
| ------------- | ----- |
| Critical      | 0     |
| High          | 0     |
| Medium        | 0     |
| Low           | 0     |
| Informational | 23    |

## 7. Recommendations

* Keep operating system updates enabled.
* Disable unnecessary services and ports.
* Use secure protocol versions whenever possible.
* Regularly perform vulnerability assessments.
* Monitor system logs and security events.

## 8. Conclusion

The vulnerability assessment was successfully completed using Nessus Essentials. The scan identified several informational findings but no critical security vulnerabilities. This exercise provided hands-on experience in vulnerability scanning, security analysis, and the use of industry-standard cybersecurity tools.
