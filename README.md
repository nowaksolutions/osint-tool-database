# OSINT Tool Database

A structured, continuously evolving knowledge base of Open-Source Intelligence (OSINT) tools used in cybersecurity investigations, threat intelligence, and digital reconnaissance.

This repository is hosted on :contentReference[oaicite:0]{index=0} and is designed as both a personal learning system and a professional portfolio artifact.

Each tool lives in its own file and is organized by investigative category to mirror real SOC and threat-intelligence workflows.

---

## Purpose

The goal of this project is to move beyond simple tool collection and instead build:

• Deep understanding of OSINT capabilities  
• Clear investigative workflows  
• Practical analyst documentation  
• A foundation for future automation  
• A reference system for SOC operations  

Every tool is documented using a standardized template to ensure consistency, clarity, and operational relevance.

---

## Repository Structure
category/
│
├── breach-data/
├── correlation/
├── domain/
├── geolocation/
├── people-osint/
├── social-media/
└── username-enumeration/
│
templates/
└── tool-template.md

README.md

Each category folder contains individual Markdown files, with **one tool per file**.

Example: category/username-enumeration/whatsmyname.md
---

## Categories

Tools are organized by investigation phase:

Username Enumeration  
People OSINT  
Domain & Infrastructure  
Social Media Analysis  
Breach Data  
Geolocation  
Correlation & Link Analysis  

This reflects how analysts actually pivot during real investigations.

---

## Documentation Standard

Each tool file includes:

Category  
Purpose  
Input  
Output  
Strengths  
Limitations  
Account Requirements  
Typical Use Case  
Example  
Personal Notes  
Tags  

This ensures every entry provides both technical detail and real-world context.

---

## Tags

Tools are additionally tagged for fast searching and future automation:

#free  
#paid  
#passive  
#active  
#api  
#recon  
#people-osint  
#domains  
#automation  

---

## Roadmap

Planned future enhancements:

• Expansion to 100+ documented tools  
• SOC-style investigation workflows  
• Python-based indexing and search  
• SQLite local database integration  
• CLI launcher for tool lookup  
• Automated recon pipelines  

---

## Author

Christopher Nowak  
United States Marine Corps Veteran  
Cybersecurity Student  
SOC / Threat Intelligence Focus  

Driven by logic. Guided by purpose.

---

## Disclaimer

All tools documented in this repository are intended for educational and defensive security purposes only.

Always ensure proper authorization and legal compliance before conducting any investigations.
