

```markdown
```mermaid
sequenceDiagram
    participant User
    participant Main
    participant StudentService
    participant CourseService
    participant EnrollmentService

    User->>Main: Select Enrollment Option
    Main->>User: Request RegNo
    User->>Main: Enter RegNo
    Main->>StudentService: find(regNo)
    StudentService-->>Main: Student

    Main->>User: Ask Course Code
    User->>Main: Input Code
    Main->>CourseService: find(courseCode)
    CourseService-->>Main: Course

    Main->>User: Ask Semester & Marks
    User->>Main: Input

    Main->>EnrollmentService: recordMarks()
    EnrollmentService-->>Main: Success/Error

    Main-->>User: Display result
