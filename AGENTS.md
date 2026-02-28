```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines outline the principles and rules for the development of AI coding agents within this repository.  Adherence to these principles is crucial for maintaining code quality, readability, and maintainability.

## 1. DRY (Don't Repeat Yourself)

*   All code must be reusable. Avoid duplication of functionality across multiple files.
*   When a feature is implemented, it should be encapsulated in a dedicated module or function.
*   Consider using abstract classes or interfaces to define common behaviors.
*   Standardize naming conventions across modules and components.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize clarity and readability over cleverness.
*   Ensure each function and module has a single, well-defined purpose.
*   Use meaningful variable and function names.
*   Avoid unnecessary complexity.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  The code should be open for extension but closed for modification.  New features should be added without altering existing code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be required to depend on methods or properties that it does not use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Avoid implementing features solely for hypothetical future needs.
*   Implement only what is currently required for the current task.
*   Refactor to remove unnecessary code before adding new functionality.

## 5. Testing & Coverage

*   All development must be productive.  Do not use mocks.
*   Unit tests are *mandatory* for all code. Aim for 80% test coverage.
*   Tests should cover all critical code paths and edge cases.
*   Test frameworks should be selected and used consistently.
*   Tests should be designed to verify the intended behavior of the agent, not just detect errors.

## 6. Code Length Constraints

*   Maximum code length: 180 lines.
*   Code should be organized logically and clearly.

## 7. File Structure

*   Each file should contain a single, well-defined purpose.
*   File names should be descriptive and follow a consistent naming convention.
*   Use comments to explain complex logic or non-obvious code.
*   Consistent formatting (indentation, line breaks) is required.

## 8.  Specific Requirements (Illustrative – Adapt as Needed)

*   **Agent Core Logic:** All agent core logic must be encapsulated within a `AgentCore` module.  This module must have a clear purpose.
*   **Data Management:**  Use a consistent data structure for agent state (e.g., a dedicated `AgentState` class) to avoid duplication.
*   **Communication Protocol:** Define a clear communication protocol (e.g., a message queue) for agent interaction.
*   **Logging:** Implement a basic logging mechanism to record important events.
*   **Configuration:** Utilize a configuration file format to manage agent parameters.

## 9.  Development Practices

*   Code should be reviewed by at least one other developer before deployment.
*   Use a version control system (e.g., Git) for all code.
*   Document code clearly and concisely.
*   Follow established coding standards.
*   Address any identified issues promptly.

## 10.  Reporting

*   Weekly status reports documenting progress, roadblocks, and completed tasks.
*   Code quality metrics (test coverage) will be tracked.

These guidelines are intended as a starting point and may be subject to revision as needed.  Continuous improvement and adherence to these principles are essential for the long-term success of this repository.
```