# Project Statement

## 1. Problem Statement
Educational institutions often face challenges in managing student information, courses, enrollments, grades, and backups when using manual or unstructured systems. This leads to data inconsistency, delays in record processing, duplicate enrollments, difficulty in generating reports, and overall inefficiency. A centralized and streamlined Java-based system is required to handle academic records effectively.

## 2. Scope of the Project
The project provides a command-line application capable of managing:

- Student records (add, update, list, deactivate, profile view)
- Course catalog (add, update, list, filter, deactivate)
- Enrollment and grading for students
- Import and export of CSV data
- Backup creation and size tracking
- Performance reports (top students, GPA distribution)

The system uses an in-memory storage architecture with layered components like Config, Domain, Services, Exceptions, and Utilities. It does not include GUI, networking, or external database integration.

## 3. Target Users
The primary users of this system include:

- Academic Administrators – to manage student and course data.
- Faculty Members – to assign grades and review enrollment data.
- Administrative Staff – to generate reports and maintain backups.
- Institutions seeking a lightweight, local, menu-driven records management solution.

## 4. High-Level Features
- Student Management: Add, update, list, deactivate, view profile, generate transcripts.
- Course Management: Add, update, list, filter (instructor/department/semester), deactivate.
- Enrollment & Grades: Enroll/unenroll students, record marks, validation for duplicates and credit limits.
- Import/Export: Import student and course data from CSV; export all data.
- Backup System: Create backups of exported files and check their size.
- Reports: Top students report, GPA category distribution (High/Mid/Low).
