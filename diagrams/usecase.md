```mermaid
usecaseDiagram
actor Admin
actor Faculty

Admin --> (Manage Students)
Admin --> (Manage Courses)
Admin --> (View Reports)
Admin --> (Backup Data)

Faculty --> (View Courses)
Faculty --> (Record Marks)
Faculty --> (View Student Performance)
