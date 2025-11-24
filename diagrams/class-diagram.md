


```markdown
```mermaid
classDiagram

    class Student {
        - String regNo
        - String name
        - String email
        - boolean active
        + profile()
        + gpa()
    }

    class Course {
        - CourseCode code
        - String title
        - int credits
        - String instructor
        - Semester semester
        - String department
    }

    class Enrollment {
        - Student student
        - Course course
        - Semester semester
        - double marks
    }

    class StudentService
    class CourseService
    class EnrollmentService
    class ImportExportService
    class BackupService
    class AppConfig

    StudentService --> Student
    CourseService --> Course
    EnrollmentService --> Enrollment
    AppConfig --> Student
    AppConfig --> Course
