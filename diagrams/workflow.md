

```markdown
```mermaid
flowchart TD
    A[Start Application] --> B[Show Main Menu]
    B --> C[Manage Students]
    B --> D[Manage Courses]
    B --> E[Enrollment & Grades]
    B --> F[Import/Export]
    B --> G[Backup]
    B --> H[Reports]
    B --> Z[Exit]

    C --> C1[Add/Update/List/Deactivate Student] --> B
    D --> D1[Add/Update/List/Filter/Deactivate Course] --> B
    E --> E1[Enroll/Unenroll/Record Marks] --> B
    F --> F1[Import CSV / Export All] --> B
    G --> G1[Create Backup & Show Size] --> B
    H --> H1[Top Students & GPA Distribution] --> B
