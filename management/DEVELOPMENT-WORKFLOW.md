# Development Workflow

1. **Requirement Confirmation**: Use GitHub Issues to record and confirm requirements.
2. **Design and Module Splitting**: Create a `design` directory in the code repository to store design documents and module splitting plans.
3. **Review Process**: Use GitHub Pull Request (PR) functionality to review designs and code.
4. **Detailed Design**: Write detailed design documents for each module in the `design` directory.
5. **Unit Testing**: Use the Google Test framework to write unit tests for utility classes.
6. **Module Testing**: Write corresponding test cases after each module is completed.
7. **Integration Testing**: Write integration test cases after the project is completed.
8. **Commit Standards**: Use Conventional Commits standards to ensure consistency in commit messages.
9. **Code Style Checking**: Integrate tools like Clang-Tidy or CppCheck for code style checking.
10. **Build, Test, Packaging Scripts**: Add corresponding scripts in `CMakeLists.txt` or `Makefile`.

This workflow ensures a structured and efficient development process.