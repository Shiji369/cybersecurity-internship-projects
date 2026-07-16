# Android Application Security Assessment – Termux

## Overview

This project presents a Mobile Application Vulnerability Assessment and Penetration Testing (VAPT) conducted on the **Termux Android Application** during my cybersecurity internship.

The assessment focused on identifying security vulnerabilities through static and dynamic analysis, evaluating the application's security posture, and recommending remediation measures. The assessment identified security issues related to debug configuration, exported components, permission management, and application security best practices.

---

## Objectives

- Perform Android application security assessment
- Identify security vulnerabilities and misconfigurations
- Validate findings through manual testing
- Prepare a professional Mobile Application VAPT report
- Recommend remediation measures

---

## Scope

**Target:** Termux Android Application

The assessment included:

- APK Static Analysis
- AndroidManifest.xml Review
- Permission Analysis
- Component Security Testing
- Dynamic Analysis
- Runtime Behavior Analysis

---

## Methodology

This assessment followed the shared Android Application Security Testing methodology available in:

**Android-Application-VAPT/methodology.md**

---

## Tools Used

- MobSF
- JADX
- APKTool
- Android Debug Bridge (ADB)
- Genymotion
- Burp Suite

---

## Key Findings

| Severity | Findings |
|----------|---------:|
| High | 1 |
| Medium | 4 |
| Low | 3 |
| Informational | 2 |

### Major Findings

- Root Detection Not Implemented
- Application Running in Debug Mode
- Exported Content Provider Protected by Weak Permission
- Exported Command Execution Service Protected by Weak Permission
- Weak Protection Level for Command Execution Permission
- Use of SYSTEM_ALERT_WINDOW Permission
- Application Requests Permission to Install Packages
- Exported Settings Activity

---

## Skills Demonstrated

- Android Application Security Testing
- Mobile Application VAPT
- Static Analysis
- Dynamic Analysis
- Reverse Engineering
- Android Manifest Analysis
- Permission Analysis
- Security Reporting
- Risk Assessment

---

## Repository Contents

- `report.pdf` – Redacted Mobile Application VAPT Report
- `screenshots/` – Supporting screenshots collected during testing

---

## Disclaimer

This project is shared for educational and portfolio purposes only. Any confidential or sensitive information has been removed from the published report and supporting materials.
