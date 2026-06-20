# Autopsy-Digital-Forensics-Lab

Digital forensics lab using Autopsy 4.22 to examine disk images, recover evidence, perform keyword searches, and generate forensic reports. Southwestern College coursework.

## Overview
This repository documents hands-on digital forensics investigations using Autopsy 4.22.1. 
Each project involves examining disk images, analyzing file artifacts, performing keyword 
searches, and generating formal forensic reports.

## Tools Used
- Autopsy 4.22.1
- Windows OS
- Excel (for report output)

## Projects

### C1Prj01 – USB Drive Investigation
**Examiner:** Jayson Araga  
**Data Source:** Disk Image (E01 format)

**Summary:**  
Examined a USB drive image belonging to a person of interest. Two key files were recovered:

- **Sylvias Assets.xls** – A spreadsheet documenting financial holdings totaling $2,796,000.00 
  (Stocks, Bonds, Real Estate, Annuities, Savings Account, Life Insurance)
- **suicide1.txt** – A plain text note expressing emotional distress, signed by Sylvia

**Key Findings:**  
The combination of the financial spreadsheet and the personal note provided relevant 
evidence to understand the context of the investigation.

---

### C1Prj02 – Keyword Search & Report Generation
**Examiner:** Jayson Araga  
**Data Source:** Disk Image (C1Prj02-1.001)

**Summary:**  
Conducted a keyword search using the term "Confidential" across the disk image. 
Multiple files were identified containing confidential and trade secret markings, including 
reports, financials, notes, a plan, a summary, data, an overview, a strategy document, 
and an archive. Evidence of file deletion was also discovered.

**Steps Performed:**
1. Created new case in Autopsy
2. Added disk image as data source
3. Configured and ran all ingest modules (80 files processed)
4. Performed keyword search for "Confidential"
5. Tagged relevant files as "Recovered Office Documents"
6. Generated Excel report of all tagged results

**Key Findings:**  
Nine files were tagged and exported, all timestamped February 10, 2017. 
Evidence of deleted data was also noted during analysis.

---

## Skills Demonstrated
- Disk image ingestion and analysis
- File type identification and extraction
- Keyword searching
- Evidence tagging and documentation
- Forensic report generation (Excel format)
- Chain of custody awareness
