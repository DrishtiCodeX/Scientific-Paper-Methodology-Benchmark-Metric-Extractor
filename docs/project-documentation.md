# Project Documentation

## Scientific Paper Methodology & Benchmark Metric Extractor

### 1. Project Overview

The Scientific Paper Methodology & Benchmark Metric Extractor is a research-assistance project designed to help users organize methodology details and benchmark metrics from scientific research papers.

Scientific papers contain information about research methods, datasets, experimental settings, evaluation metrics, and reported results. Finding and recording these details manually can be time-consuming and inconsistent.

This project aims to assist users by extracting relevant information, organizing it into a structured format, and supporting its storage and retrieval.

### 2. Problem Statement

Research methodology and benchmark metrics are often distributed across different sections, tables, and figures of scientific papers.

Manual extraction can lead to:
- Time-consuming research-paper review.
- Inconsistent recording of methodology and metrics.
- Loss of dataset and experimental context.
- Difficulty comparing results across different research papers.
- Missing source references for extracted information.

The project aims to provide a structured approach to organizing research information while allowing users to verify extracted details against the original paper.

### 3. Project Objectives

- Develop a backend system using Python and FastAPI.
- Provide REST APIs for submitting and retrieving paper-related information.
- Identify methodology details, datasets, and benchmark metrics.
- Organize extracted information into a structured format.
- Support relational database storage and retrieval.
- Maintain source context for verification.
- Handle missing or uncertain information appropriately.
- Support testing and validation of the extraction workflow.

### 4. Proposed System

The proposed system follows a modular backend architecture.

It is designed to receive paper-related input, process methodology and benchmark information, organize the extracted fields, validate the information, and store structured records in a relational database.

AI-assisted extraction may be used to identify candidate information. Extracted details should be checked against the original research paper before being treated as verified.

The system is intended to assist research-paper review and comparison, not replace manual verification.

### 5. System Workflow

The proposed workflow consists of the following stages:

1. **Input:** User submits scientific-paper content or metadata through the API.
2. **Request Validation:** Backend checks the request and supported input requirements.
3. **Candidate Extraction:** Extraction component identifies methodology details, datasets, and metric mentions.
4. **Normalization:** Extracted information is organized into a consistent structure.
5. **Verification:** Information is checked for correctness and source context.
6. **Database Storage:** Validated records are stored in the configured relational database.
7. **Retrieval:** Structured information is returned through the API for review and comparison.

### 6. Information to Be Extracted

The proposed structured record may contain:

- Paper title or identifier
- Authors and publication year
- Methodology
- Dataset
- Dataset split
- Metric name
- Metric value
- Baseline or comparison method
- Experimental conditions
- Source location
- Verification status

These fields are based on the proposed project schema and should be finalized according to the actual implementation.

### 7. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming and data processing |
| FastAPI | REST API development |
| VS Code | Development environment |
| Git | Version control |
| GitHub | Code management and collaboration |
| MySQL or PostgreSQL | Proposed relational database |
| AI tools / Gemini | Potential assistance in candidate extraction |

**Note:** The final database selection and AI integration should reflect the technologies actually used in the project.

### 8. Hardware Components

The project hardware inventory includes:

| Component | Cost |
|---|---:|
| ESP32 | ₹480 |
| OLED Display | ₹200 |
| Jumper Wires | ₹35 |
| Mini Breadboard | ₹80 |
| USB Cable | ₹145 |
| **Total** | **₹940** |

The exact functional connection between the ESP32/OLED hardware and the paper-extraction software should be documented according to the actual hardware demonstration.

### 9. System Architecture

The proposed system is organized into the following modules:

- **API Layer:** Receives requests and returns structured responses.
- **Input Validation:** Checks required fields and supported inputs.
- **Extraction Layer:** Identifies candidate methodology details, datasets, and metrics.
- **Normalization Layer:** Organizes information into consistent fields.
- **Validation Layer:** Checks extracted information and source evidence.
- **Database Layer:** Stores and retrieves paper records.
- **Response Layer:** Returns structured information for review.

### 10. Database Design

The proposed database structure may include:

#### Paper
Stores paper-related information such as title, authors, year, and source identifier.

#### Methodology Record
Stores methodology descriptions and source locations.

#### Metric Record
Stores metric names, values, datasets, and baseline information.

#### Verification Record
Stores verification status and reviewer notes.

The final database schema depends on the database selected and the implementation completed by the project team.

### 11. Testing and Validation

The project testing approach includes:

- API request validation
- Extraction behavior testing
- Normalization testing
- Database storage and retrieval testing
- Missing-information handling
- Integrated workflow testing

Extracted information should be compared with the original scientific paper to check correctness.

No extraction accuracy, precision, recall, response time, or completed test results are claimed in this documentation without actual supporting test records.

### 12. Limitations

- Scientific papers may contain different layouts and terminology.
- Metric values may be separated from their datasets or experimental conditions.
- AI-assisted extraction may produce incorrect information.
- Missing information must be handled without inventing values.
- Extracted details require verification against the original paper.
- The exact hardware integration role needs to be described based on the actual demonstration.

### 13. Future Scope

- Support additional scientific-paper formats.
- Improve PDF and table extraction.
- Enable batch processing of research papers.
- Support comparison across multiple papers.
- Improve source-location tracking.
- Add a review interface for correcting extracted information.
- Evaluate extraction performance using a labelled dataset.
- Improve hardware integration where applicable.

### 14. Conclusion

The Scientific Paper Methodology & Benchmark Metric Extractor aims to make research-paper review more organized by structuring methodology details and benchmark metrics.

The proposed Python and FastAPI backend, relational database, extraction workflow, and validation process provide a foundation for organizing and retrieving research information.

The system is intended to support research review while keeping the original scientific paper as the authoritative source.

### 15. Project Information

**Project Name:** Scientific Paper Methodology & Benchmark Metric Extractor

**Department:** Computer Science & Engineering

**Institution:** CGC University Mohali

**Academic Semester:** 3rd Semester

**Project Type:** Engineering Clinics Final Project
