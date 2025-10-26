# Yash-Walhekar-Cyber-Task-3

This repository documents the completion of Task 3, which involves performing a basic vulnerability scan on a local machine.

### 1. Objective
To use a free vulnerability scanning tool (Nessus Essentials) to identify common vulnerabilities on a local PC and document the findings in a clear report.

### 2. Scan Configuration
The scan was configured using the "Basic Network Scan" template in Nessus.

* **Tool:** Tenable Nessus Essentials
* **Target:** `127.0.0.1` (localhost)
* **Scan Policy:** Basic Network Scan
* **Authentication:** The scan was unauthenticated.

*(Screenshot of the scan configuration)*
`![Scan Configuration](Screenshot 2025-10-26 234545.png)`

### 3. Scan Summary
The scan completed successfully and identified **21 total issues**. No 'Critical' or 'High' severity vulnerabilities were found.

* **Scan Start:** Sunday, 26 Oct 2025, 11:44 PM
* **Scan End:** Sunday, 26 Oct 2025, 11:51 PM
* **Elapsed Time:** 7 minutes

**Vulnerability Breakdown:**
* **Critical:** 0
* **High:** 0
* [cite_start]**Medium:** 1 [cite: 17]
* [cite_start]**Low:** 0 [cite: 18]
* **Info:** 20 *(Inferred from total)*

*(Screenshot of the scan results dashboard)*
`![Scan Summary Dashboard](Screenshot 2025-10-26 235507.png)`

### 4. Key Finding (Medium Severity)
The scan's most significant finding was one 'Medium' severity vulnerability.

* [cite_start]**Vulnerability:** SSL Certificate Cannot Be Trusted [cite: 31]
* **Severity:** **Medium**
* [cite_start]**CVSS v3.0 Score:** 6.5 [cite: 30]
* **Description:** The service is using an SSL certificate that is not trusted. This can be because it is self-signed, expired, or signed by an unknown authority. This prevents verification of the server's identity and could allow a man-in-the-middle attack.
* **Solution:** Purchase or generate a proper, trusted SSL certificate for this service.

*(Screenshot of the detailed vulnerability)*
`![Vulnerability Details](Screenshot 2025-10-26 235544.png)`

### 5. Task Deliverables
All required deliverables are contained within this repository:

1.  **Full Scan Report (PDF):** `My Basic Network Scan_fy9uqz.pdf`
2.  **Scan Result Screenshots:** All `.png` files documenting the process and findings.
3.  **README.md File:** This summary report.
