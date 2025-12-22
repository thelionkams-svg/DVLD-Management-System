# DVLD - Driving & Vehicle License Department Management System

## About the Project
This is my first comprehensive project built using **C#** and **SQL Server**. The goal of this system is to manage and automate the entire process of issuing driving licenses. I designed the architecture using a **3-Layer approach** (UI, Business, and Data Access) to ensure the code is organized and easy to maintain.

## Features I Implemented:

### 🛠️ Core Services & Application Workflow
I developed the system to handle various types of applications, each with its own business logic:
**First-Time Licenses**: I implemented a strict workflow where the applicant must pass three tests in order: Vision, Written, and Practical. 
**License Management**: The system handles Renewals, Replacements (for lost or damaged licenses), and International Licenses. 
**Detained Licenses**: I added a feature to manage fines and release licenses once payments are cleared. 

### 🚦 Testing and Requirements Logic
I spent a lot of time coding the "Business Rules" to make sure the system is realistic:
**Age Verification**: The system automatically checks if the applicant meets the minimum age for each class (e.g., 18 for Class 1 and 3, or 21 for heavy vehicles). 
**Test Sequence**: I ensured that an applicant cannot book a Practical test without passing the Vision and Written tests first. 
**National ID Check**: To prevent data duplication, the system uses the National ID as a unique identifier for every person.

### 👥 User and Person Management
* I built a module to manage "People" information separately from "Users". 
* Users (employees) have specific permissions and can be activated or deactivated. 

## Technical Details
* **Language:** C#
* **Database:** SQL Server 
* **Architecture:** 3-Tier Architecture (Presentation, Business Logic, and Data Access Layers).

## Acknowledgments
This project was developed as part of the "Full Project in C#" course by **Eng. Mohammed Abu-Hadhoud** (Programming Advices). I built this system following professional architectural standards to ensure high-quality code and robust business logic.
