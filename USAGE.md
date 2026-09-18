# Usage Guide for Campus Course Records Manager (CCRM)

## Running the Application

1. Ensure JDK 17+ is installed and environment variables are set.
2. Compile the source code:
3. Run the main class:
4. Use the menu-driven CLI to perform operations.

## Sample CLI Commands

- **Manage Students**
- Add: Provide student details such as ID, name, email.
- List: Display all registered students.
- **Manage Courses**
- Add: Define course code, title, credits, instructor.
- Search: By instructor, department, or semester.
- **Enrollment**
- Enroll/Unenroll students in courses respecting max credit rules.
- Record grades and compute GPA.
- **Import/Export Data**
- Import student/course data from CSV files.
- Export current data to CSV format.
- **Backup**
- Execute backup of exported files to timestamped folders.

## Test Data Files

- `test-data/students.csv`: Sample students data.
- `test-data/courses.csv`: Sample courses data.
- `test-data/enrollments.csv`: Sample enrollments and grades.

Ensure data files are formatted as CSV with headers matching attributes:
For example, `students.csv`:


## Notes

- Enable assertions for runtime checks (see README).
- Use the CLI menu options as guided by prompts.
- Refer to the main README.md for detailed project overview and setup instructions.



