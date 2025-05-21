# GondarPHCU_EHR
# EHR System for Gondar Health Centers

A secure Electronic Health Record (EHR) system designed for eight health centers in Gondar, Ethiopia. Built by Shegaw Marie, a software engineering student at the University of Gondar, this system manages patient records, supports offline functionality, and includes Amharic/English interfaces for accessibility.

## Features
- Patient registration with local identifiers (e.g., kebele-based IDs)
- Medical history, diagnosis, and treatment tracking
- Offline support for rural health centers
- Multilingual interface (Amharic and English)
- Role-based access (doctors, nurses, admins)
- HL7 FHIR-compliant APIs for interoperability
- Secure data storage with audit logging

## Tech Stack
- **Frontend**: React, Tailwind CSS
- **Backend**: Django, Django REST Framework
- **Database**: PostgreSQL (SQLite for offline mode)
- **Authentication**: JWT
- **Security**: AES-256 encryption
- **Testing**: pytest, Jest

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ShegawMarie/Gondar-EHR.git
