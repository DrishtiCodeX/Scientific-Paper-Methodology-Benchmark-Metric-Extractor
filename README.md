# Scientific Paper Methodology & Benchmark Metric Extractor

A hardware-software integrated academic project designed to support the extraction and analysis of research methodology and benchmark metrics from scientific research papers.

## 📌 Project Overview

The **Scientific Paper Methodology & Benchmark Metric Extractor** aims to simplify the process of analyzing scientific research papers by identifying important information related to research methodology and benchmark metrics.

The project combines a Python-based backend, API layer, database support, and hardware components to develop a research paper analysis system.

It focuses on making research information easier to identify, organize, and review.

## 🎯 Problem Statement

Scientific research papers contain important information about methodologies, experiments, and performance evaluation metrics.

However, manually reviewing research papers to identify this information can be time-consuming and require considerable effort.

This project aims to simplify the extraction and organization of research methodology and benchmark metrics, helping users review important research information more efficiently.

## 🎯 Project Objectives

- Develop a system for analyzing scientific research papers.
- Identify and extract research methodology information.
- Extract benchmark metrics and performance-related information.
- Organize extracted information for easier review.
- Develop a backend using Python and FastAPI.
- Integrate hardware components into the project setup.
- Explore AI-assisted extraction where supported by the implementation.

## ✨ Key Features

- Scientific research paper analysis.
- Research methodology extraction.
- Benchmark metric extraction.
- Backend API development.
- Database support for storing or managing information.
- Hardware integration using ESP32 and OLED display.
- AI-assisted candidate extraction, if Gemini API integration is implemented.

## 🛠️ Technology Stack

### Software Requirements

| Software / Service | Purpose |
|---|---|
| Python | Backend programming language |
| FastAPI | HTTP API layer |
| VS Code | Code editing and debugging |
| Git | Version control |
| GitHub | Repository hosting and collaboration |
| MySQL or PostgreSQL | Database layer |
| Gemini API | AI-assisted candidate extraction, if integrated |
| API Testing Tool | Endpoint verification |

**Database:** Specify the database used in the final implementation: MySQL or PostgreSQL.

**AI Integration:** Gemini API is included only if it is integrated into the working project.

## 🔧 Hardware Requirements

| Component | Purpose |
|---|---|
| ESP32 | Hardware controller |
| OLED Display | Displaying information |
| Jumper Wires | Connecting hardware components |
| Mini Breadboard | Hardware prototyping |
| USB Cable | Power and connectivity |



## 🏗️ System Architecture

The project consists of hardware and software components that form the overall system.

### Software Architecture

The software layer is designed around the following components:

1. **Python Backend:** Handles application logic and processing.
2. **FastAPI:** Provides the HTTP API layer.
3. **Database:** Supports data storage and management.
4. **AI API:** May assist with candidate extraction when integrated.
5. **API Testing:** Supports endpoint verification.

### Hardware Architecture

The hardware setup consists of:

- ESP32
- OLED Display
- Mini Breadboard
- Jumper Wires
- USB Cable

These components form the project's hardware setup.

## 🔄 Project Workflow

The research paper extraction workflow is designed around the following stages:

1. **Input:** Provide a scientific research paper.
2. **Processing:** Analyze the paper using the implemented software.
3. **Methodology Extraction:** Identify relevant research methodology information.
4. **Benchmark Metric Extraction:** Identify relevant benchmark metrics and performance-related information.
5. **Output:** Review the extracted information.

The exact processing and extraction methods depend on the project's implementation.

## 💻 Installation and Setup

### Prerequisites

- Python
- Visual Studio Code
- Git
- Required Python libraries
- Configured database, if used
- Hardware components listed in the hardware inventory

### Setup

1. Clone the repository:

   ```bash
   git clone <your-github-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <your-project-folder>
   ```

3. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment.

   **Windows:**

   ```bash
   venv\Scripts\activate
   ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Configure the database and environment variables according to the project implementation.

7. Run the application using the configured FastAPI entry point.

   The exact command depends on the application's main Python file.


## 📂 Project Documentation

The repository may include the following documentation:

- Research Paper
- Project Synopsis
- Project Presentation
- Application Screenshots
- Hardware Inventory
- Installation Instructions

## 🔮 Future Scope

- Improve research methodology extraction accuracy.
- Support additional scientific paper formats.
- Improve benchmark metric identification.
- Enhance the presentation of extracted information.
- Expand AI-assisted extraction capabilities.
- Improve hardware and software integration.
- Develop additional research paper analysis features.

## 👩‍💻 Project Information

| Details | Information |
|---|---|
| Project Name | Scientific Paper Methodology & Benchmark Metric Extractor |
| Project Type | Academic Project |
| Domain | Research Paper Analysis and Information Extraction |
| Backend Language | Python |
| API Framework | FastAPI |
| Hardware Controller | ESP32 |
| Display | OLED Display |
| Hardware Cost | ₹940 |

## 📚 References

References and research papers used during project development will be documented here.

## 📄 License

A license will be added according to the project's sharing and usage requirements.

---

**Developed as an academic project.**
