A console-based Library Management System built in core Java, developed as
the "Build Your Own Project" submission for the Java Programming course.

**Author:** Yatharth Joshi
**Registration No:** 24BCY10045
# Campus Course Records Manager (CCRM)

## Project Overview & How to Run

Campus Course Records Manager is a console-based Java SE application to manage students, courses, enrollment, grades, and transcripts for an educational institute. The project demonstrates core Java fundamentals such as OOP, exception handling, IO, streams, lambdas, and more.

**JDK Version:** 17 or higher is recommended.

**Running the project:**
1. Install JDK and set environment variables.
2. Import the project into Eclipse IDE.
3. Run the main class: `edu.ccrm.cli.MainMenu`.
4. Use the CLI menus to manage students, courses, enrollments, grades, importing/exporting, and backup.

## Evolution of Java (Short Timeline)

- 1995: Java 1.0 – Initial public release.
- 2004: Java SE 5 – Added generics, enums, annotations.
- 2014: Java SE 8 – Introduced lambdas, streams API.
- 2017: Java SE 9 – Modular system (Project Jigsaw).
- 2021–2024: Recent LTS versions enhancing performance, records, and sealed classes.

## Java Editions Comparison

| Edition       | Use Case                           | Features                                   | Examples                                |
|---------------|----------------------------------|--------------------------------------------|----------------------------------------|
| Java ME       | Mobile and embedded devices      | Compact runtime, device-specific libraries | Mobile apps, IoT, embedded devices     |
| Java SE       | Standard desktop/server apps     | Core APIs, JDBC, Swing, NIO, Concurrency  | Desktop apps, CLI tools, libraries      |
| Java EE (Jakarta EE) | Enterprise, distributed systems | Web services, Servlets, EJB, JMS          | Web apps, large-scale business systems  |

## JDK, JRE, JVM Explained

- **JDK (Java Development Kit):** Full development kit including compiler (`javac`), runtime, and tools for building Java apps.
- **JRE (Java Runtime Environment):** Runtime environment that includes JVM and core libraries required to run Java programs but no compiler.
- **JVM (Java Virtual Machine):** The engine that executes Java bytecode, providing platform independence.

## Windows Installation Steps

1. Download JDK installer from Oracle or OpenJDK.
2. Run installer, follow setup wizard.
3. Set environment variables: `JAVA_HOME` and update `PATH`.
4. Verify installation with command `java -version`.
5. Screenshots of these steps are in `/Screenshots/install_verify.png`.

## Eclipse Setup Steps

1. Download and install Eclipse IDE for Java Developers.
2. Create a new Java Project: File > New > Java Project.
3. Import source folders and libraries.
4. Set `edu.ccrm.cli.MainMenu` as the run configuration.
5. Run the project using Run > Run As > Java Application.
6. Screenshots available in `/Screenshots/eclipse_setup.png`.

## Mapping Table (Syllabus Topic → Location)

| Syllabus Topic                    | File/Class                   | Method/Description                         |
|----------------------------------|------------------------------|-------------------------------------------|
| Encapsulation                    | `domain/Student.java`         | Private fields with getters/setters       |
| Inheritance                     | `domain/Person.java`          | Abstract class extended by Student/Instructor |
| Polymorphism                    | `service/TranscriptService.java` | Overridden `toString()` methods           |
| Singleton Pattern               | `config/AppConfig.java`       | Singleton instance used for config        |
| Builder Pattern                 | `domain/Course.Builder.java`  | Builder for course object construction    |
| Exception Handling             | `service/EnrollmentService.java` | Custom exceptions for max credits etc.   |
| Lambdas and Streams            | `service/StudentService.java` | Filtering students using Stream API       |
| File IO (NIO.2 & Streams)       | `io/ImportExportService.java` | CSV import/export using NIO               |
| Date/Time API Usage             | `domain/Student.java`         | Enrollment dates using Java Time API      |

## Enabling Assertions

Assertions can be enabled to check program invariants during runtime.

Run the program using:


The `-ea` flag (or `-enableassertions`) enables assertions. Assertions are used in code to verify conditions like non-null IDs or valid credit ranges.

---

*Screenshots referenced above are included in the `/Screenshots` folder.*

*This project is an original work complying with academic integrity guidelines.*

