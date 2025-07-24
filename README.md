# Browser-artifact-forensics
Digital forensics project that looks into browser artefacts using Nirsoft BrowsingHistoryView.
# Analysis of Browser Artifacts Using NirSoft (Combining NirSoft with CSV Analysis)

The study focuses on digital forensics for activities performed using web browsers. With NirSoft BrowsingHistoryView, the researchers gathered, analyzed, and graphically represented data to simulate an investigative setting—illustrating the process of reconstructing timelines in addition to the analysis of user actions.

## Equipment Used


- BrowsingHistoryView by NirSoft
- Data extraction through Windows
- An analysis tool for CSV files and spreadsheets.
- Photos taken for archiving purposes.

# Project Objectives

- Simulate real-world forensic analysis of browser artifacts
- Get data from web browsers' browsing histories (Chrome, Firefox, Edge).
- Determine key measures that include:
- Recognized domains
- Timestamps
- Reading patterns
- Reconstruct Chronological Order of User Actions.

# Demonstrated Competencies

- Digital forensics fundamentals
- Timeline reconstruction
- Gathering and saving evidence
- CSV-based log analysis
- Report documentation

# Screenshots

Screenshots related to extraction and analysis of evidence are all available.
# Forensic Evidence

The raw output, produced by the NirSoft tool in .CSV form, is available.
- Browser forensics yashwant.csv

# Application Case Example

Imagine a SOC analyst or incident responder needs to verify user activity related to a phishing investigation. This project simulates such an extraction and presents the raw data for timeline verification.

# MITRE ATT&CK Mapping

Each of these digital forensic operations maps to the following MITRE ATT&CK tactics:

1. T1217 -  Browser Information Discovery
- The tool utilizes NirSoft BrowsingHistoryView to fetch browsing history, recorded URLs, and their timestamps.
This mimics the way threat actors collect browser artifacts in the course of reconnaissance or data collection.

2. T1083 - File and Directory Discovery

Forensic software interactions with directory locations like AppData or user web cache directory locations require identification of locations with sensitive data.

3. T1005 - Data from Local System 

Data obtained from web browsers, visited sites, cookies, and downloads might collectively provide a type of locally kept user data. - This reflects how adversaries collect data from an endpoint post-compromise. 

#Author
: Yashwant G.S - Comptia Security+ Certified | MSc Cybersecurity
