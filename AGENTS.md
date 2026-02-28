# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure high-quality, maintainable, and reliable AI coding agent development within the AGENTS repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   **Code Reuse:** Avoid duplicating code snippets or logic across multiple files. Create reusable functions, classes, and modules to promote code cohesion.
*   **Standardized Components:** Define and document reusable components with clear interfaces and usage patterns.
*   **Pattern Matching:** Use pattern matching extensively to handle variations in input data and create flexible code.

## 2. KISS (Keep It Simple, Stupid)

*   **Simplicity:** Strive for code that is easily understood, maintainable, and debuggable.
*   **Minimalism:** Avoid unnecessary complexity. Simplify logic where possible without sacrificing functionality.
*   **Clear Intent:** Each line of code should have a clear and understandable purpose.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one primary responsibility.
*   **Open/Closed Principle:**  Systems should be extensible without modifying their existing code. Utilize abstraction to extend functionality.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:**  Clients should not be forced to depend on methods they do not use.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Features:**  Do not implement features or functionalities that are not currently required or likely to be needed in the future.
*   **Focus on Core Requirements:** Prioritize the implementation of core functionality.

## 5. Development Process & Testing

*   **Minimum Effort:**  Each file should implement the minimum necessary functionality to meet its specified purpose.
*   **Unit Testing:** All code must undergo rigorous unit testing.
*   **Comprehensive Test Coverage:**  Aim for at least 80% test coverage. Test all critical paths and edge cases.
*   **Test-Driven Development:**  Write tests *before* writing the code.  Automated testing should be performed on every change.
*   **Code Review:** All code must be reviewed by another AI agent before integration.
*   **Refactoring:**  Regularly refactor existing code to improve its quality and maintainability.

## 6. File Structure & Size

*   **Maximum File Length:** Each file must be a maximum of 180 lines of code.
*   **Modular Design:** Organize files into logical modules or packages.
*   **Consistent Naming Conventions:** Adopt a consistent naming convention throughout the codebase (e.g., camelCase, snake_case).
*   **Comments:** Use comments sparingly and only to explain complex logic or non-obvious design decisions. Prioritize clear code over comments.

## 7. Data Handling

*   **Mock Data:**  All data inputs and outputs must be simulated using mocks.  No real data should be used.
*   **Data Abstraction:**  Data interfaces should be defined clearly to facilitate testing and potential future changes.
*   **Data Validation:** Implement data validation to ensure data integrity and prevent errors.

## 8.  Integration & Dependencies

*   **Dependency Management:**  Use a dependency management system to track and manage external libraries and dependencies.
*   **Version Control:**  Employ a version control system (e.g., Git) to track code changes and facilitate collaboration.

## 9.  Documentation

*   **API Documentation:**  Generate API documentation (using tools like Sphinx or similar) to document the API contracts for each module.
*   **Code Comments:**  Provide clear and concise code comments to explain complex logic.

## 10.  Maintainability

*   **Readability:**  Code should be easy to read and understand.
*   **Error Handling:** Implement robust error handling and logging to facilitate debugging and troubleshooting.

These guidelines are intended as a living document and will be reviewed and updated periodically.  Any deviation from these guidelines will be subject to review and potential revision.