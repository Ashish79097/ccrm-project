

```markdown
```mermaid
flowchart LR
    UI[CLI - Main.java] --> SVC[Service Layer]

    SVC --> STU[StudentService]
    SVC --> CRS[CourseService]
    SVC --> ENR[EnrollmentService]
    SVC --> IO[ImportExportService]
    SVC --> BAK[BackupService]

    STU --> DOM[Domain Models]
    CRS --> DOM
    ENR --> DOM

    IO --> FILES[(CSV Files)]
    BAK --> ZIP[(Backups)]

    DOM --> CFG[AppConfig]
