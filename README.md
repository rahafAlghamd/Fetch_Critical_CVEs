# Fetch Critical CVEs

## Description

The **Fetch Critical CVEs** tool is designed to automate the retrieval and filtering of critical CVE (Common Vulnerabilities and Exposures) information from trusted sources such as the NVD (National Vulnerability Database) and Saudi CERT. The tool allows users to:

- Specify date ranges to fetch CVEs published within a certain timeframe.
- Extract essential details such as CVE ID, summary, publication date, and severity.
- Output the results to an external file in a structured format.

With a user-friendly interface, this tool simplifies CVE management, enhances vulnerability tracking, and supports cybersecurity professionals in staying informed about critical threats efficiently.

---

## Supported Sources

- **Saudi CERT**  
- **NVD (National Vulnerability Database)**  

---

## Features

### Efficient CVE Retrieval
- Automatically fetches CVEs based on severity (critical).
- Filters results using user-defined criteria, such as publication date ranges.

### Customizable Date Filtering
- Users can specify start and end dates to retrieve CVEs published within a specific timeframe.

### Detailed Information Extraction
- Extracts details for each CVE, including:
  - CVE ID
  - Titile
  - Descrition 
  - Publication date
  - Best Practices and Recommendations if applicable 

### External File Output
- Outputs results to an external file in a structured format for easy reading, storage, and sharing.

### User-Friendly Design
- Simple interface with clear input prompts for users of varying technical expertise.

---

## Requirements

- Python 3.x
## Installation

Install the required dependencies:

```bash
python.exe -m pip install bs4
pip install beautifulsoup4

```
---
## Demo

<video controls>
  <source src="[path/to/video.mp4](https://github.com/rahafAlghamd/Fetch_Critical_CVEs/blob/main/Fetch_critical_CVEs.mp4)" type="video/mp4">
  Your browser does not support the video tag.
</video>


