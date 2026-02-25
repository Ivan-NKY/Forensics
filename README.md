# Digital Forensic Investigation 
## Project Overview
This repo consists of 2 projects under the same category  
* Suspicious USB Case Study
* Examiner Report on In-Class forensic investigations (below)
## USB Investigation Showcase
 This project simulates a digital forensic investigation involving a malicious USB device discovered in a corporate environment. The objective was to perform image acquisition, forensic analysis, and data recovery using open-source tools. The investigation was conducted in multiple stages:

* Image Acquisition – Creating a bit-by-bit forensic image of the USB to preserve original evidence.
* Data Analysis – Extracting and analyzing deleted files, metadata, and hidden information.
* Report Documentation – Consolidating forensic evidence, timestamps, and investigative findings.
* This project demonstrates a structured approach to identifying, extracting, and analyzing digital evidence using industry-standard forensic tools.

### Key Areas Covered
Disk Imaging & Data Integrity Checks (FTK Imager, TestDisk)  
Deleted File & Metadata Extraction (Autopsy)  
File Carving & Data Recovery (Autopsy, FTKimager)  
Steganography Analysis (StegHide)  
Report Generation & Timeline Reconstruction  
## Tools Used for this investigation
### 🛠 Forensic Imaging & Data Acquisition

TestDisk
FTK Imager
### 🔎 Analysis & Investigation

Autopsy  
FTKimager  
### 🕵️ Steganography & Hidden Data Extraction

StegHide  


# Examiner Report
This report involves a followup from an in-class forensic excercise.  
The RTF report is located in the appendices section, the format of this report is derived from [hereee](https://www.geeksforgeeks.org/computer-forensic-report-format/)

### Case study
Simon recently reported an unauthorized bank transfer of SGD $2000 in his OCBC bank
account history and reported it to the police. The recipient of the transaction was traced to
the tenant of his apartment, Alicia.  
When interrogating Alicia, she consistently denied any wrongdoings and claimed that Simon
has transferred the money on his own accord. She mentioned that Simon had been sexually
harassing her in the apartment, and the money was transferred as hush money to keep her
quiet. She gave a possibility that Simon might be trying to frame her to get his money back
and avoid any criminal indications if she reported the sexual harassment to the police.
According to the bank’s online banking logs, the transaction was made from Simon’s
apartment’s public IP address. Hence, both Simon and Alicia’s personal computers in the
apartment have since been seized for investigation.  
The preliminary interviews and investigation have gathered the following information:  
### Simon Spegman 
* 42 years old
* Singaporean Male
* Single
* Chief Executive Officer of Reynholm Industries
* Working hour: Mon - Fri, 12pm to 6pm
* Known software used:
* * Windows 7
* * Outlook
* * Google Chrome
* * Online aliases:
* * Email: “simonspegman”
* OCBC bank account number: 7566721
### Alicia Tan Hui Jing
* 18 years old
* Malaysian Female
* Single
* Student of Ngee Ann Polytechnic
* Tenant of Simon Spegman’s apartment
* Avid gamer
* Known software used:
* * Windows 10
* * Mail (application)
* * Firefox
* * Skype client
* Online aliases:
* * Email, Skype: “aliciatanhuijing”
* * Maplestory, metasploitframework: “aliciathj”
Both Mr Thomas Chee and you work as forensics investigators in a private forensics firm, True Identity Pte Ltd. The hard disk of Simon and Alicia’s personal computers were acquiredby Mr Thomas Chee and Simon’s image file (Simon.Ex01) has also been examined by him. You have been tasked to examine Alicia’s image file (Alicia.Ex01) to solve the case.   

