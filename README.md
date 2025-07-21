# Browser-artifact-forensics
Digital Forensics project analyzing browser artifacts using Nirsoft BrowsingHistoryView
# Browser Artifact Forensics using NirSoft (NirSoft + CSV Analysis)

This project focuses on digital forensics of web browser activity. Using **NirSoft BrowsingHistoryView**, I extracted, analyzed, and visualized browser artifacts to simulate a real-world investigation scenario — showcasing timeline reconstruction and user behavior analysis.

# Tools Used

-  NirSoft **BrowsingHistoryView**
-  Windows (data extraction)
-  CSV Viewer / Spreadsheet for analysis
-  Screenshots for documentation

# Project Objectives

- Simulate real-world forensic analysis of browser artifacts
- Extract evidence from browser history (Chrome, Firefox, Edge)
- Identify key indicators like:
  - Visited domains
  - Timestamps
  - Browsing patterns
- Reconstruct timeline of user behavior

# Skills Demonstrated

- Digital forensics fundamentals
- Timeline reconstruction
- Evidence extraction & preservation
- CSV-based log analysis
- Report documentation

# Screenshots

All screenshots of evidence extraction and analysis are available
# Forensic Evidence

Raw output exported as `.CSV` from NirSoft tool is available .
- **Browser forensics yashwant.csv**

# Use Case Scenario

Imagine a SOC analyst or incident responder needs to verify user activity related to a phishing investigation. This project simulates such an extraction and presents the raw data for timeline verification.

# MITRE ATT&CK Mapping

This digital forensics project aligns with the following MITRE ATT&CK techniques:

1. T1217 - Browser Information Discovery
   - The project uses NirSoft BrowsingHistoryView to extract browser history, visited URLs, and timestamps.
   - This mimics how threat actors enumerate browser artifacts during reconnaissance or data collection.

2. T1083 - File and Directory Discovery
   - If the forensic tool accesses paths like AppData or user browser cache locations, it involves discovering sensitive file locations.

3. T1005 - Data from Local System
   - Extracted browser data such as visited sites, cookies, and download history can represent locally stored user data.
   - This reflects how adversaries collect data from an endpoint post-compromise.
                                        |

# Author

- **Name**: Yashwant G.S.
- **Security+ Certified | MSc Cybersecurity**

