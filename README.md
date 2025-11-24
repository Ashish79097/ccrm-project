# Campus Course & Records Manager (CCRM)

A Java-based command-line system for managing students, courses, enrollments, grades, reports, and backups for an educational institution. Designed using clean OOP principles, layered architecture, and exception handling.

---

## 📌 Project Overview

CCRM is a menu-driven CLI application that allows administrators to:

* Manage student profiles
* Manage course catalog
* Enroll students into courses
* Record marks and compute GPA
* Import/Export data
* Maintain backups
* Generate academic reports

This project demonstrates practical implementation of Java OOP concepts, service-layer architecture, and file-based storage.

---

## 📌 Features

### **1. Student Management**

* Add student
* Update student
* Deactivate student
* List students
* View student profile
* Generate transcript

### **2. Course Management**

* Add course (Builder Pattern)
* Update course
* Deactivate course
* List courses
* Filter courses (Instructor / Department / Semester)

### **3. Enrollment & Grades**

* Enroll student in course
* Unenroll student
* Record marks
* Validate duplicate enrollments
* Enforce max credit limit

### **4. Import / Export**

* Import students from CSV
* Import courses from CSV
* Export all data

### **5. Backup System**

* Creates backup folder
* Saves exported files
* Shows backup file size

### **6. Reports**

* Top 5 students by GPA
* GPA distribution: High / Mid / Low

---

## 📌 Technologies Used

* Java 17+
* OOP Concepts
* Custom Exceptions
* Java Collections
* Streams API
* File I/O (CSV import/export)
* Builder Pattern
* Enums
* Layered architecture

---

## 📁 Project Structure

```
project/
│── src/
│   └── edu/ccrm/
│        ├── cli/
│        ├── service/
│        ├── domain/
│        ├── io/
│        ├── config/
│        ├── util/
│        └── exceptions/
│
│── diagrams/
│── statement.md
│── README.md
│── project-report.pdf
│── exports/
│── backups/
```

---

## ▶ How to Compile and Run (VS Code Terminal)

### **1. Go to project folder**

```powershell
cd "PATH_TO_PROJECT"
```

### **2. Compile all Java files**

```powershell
$files = Get-ChildItem -Recurse -Filter *.java | ForEach-Object { $_.FullName }
javac -d out $files
```

### **3. Run main program**

```powershell
cd out
java edu.ccrm.cli.Main
```

---

## 📌 Non-Functional Requirements

* **Performance:** In-memory processing ensures fast operations
* **Usability:** Clean, menu-driven interface
* **Maintainability:** Modular, layered service architecture
* **Reliability:** Custom exception handling
* **Scalability:** Easy to extend to databases

---

## 🧪 Testing Approach

* Manual testing of all menu operations
* Boundary testing:

  * Duplicate enroll attempt
  * Over-credit enrollment
  * Invalid course code or student ID
* Testing import/export flows
* Testing backup function

---

## 🎯 Future Enhancements

* Replace in-memory storage with database
* GUI or web-based UI
* Role-based access system
* More detailed analytics and reporting

---

## 📸 Screenshots


