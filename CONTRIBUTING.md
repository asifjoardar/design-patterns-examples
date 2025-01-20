# Contributing to Design Pattern Palette

Thank you for considering contributing to **Design Pattern Palette**! We welcome contributions to make this repository a comprehensive collection of design pattern examples. Please follow these guidelines to ensure a smooth contribution process.

## Table of Contents

- [Project Structure](#project-structure)
- [How to Contribute](#how-to-contribute)
  - [Fork the Repository](#fork-the-repository)
  - [Adding a New Example](#adding-a-new-example)
  - [Adding a New Design Pattern](#adding-a-new-design-pattern)
  - [Reporting Bugs](#reporting-bugs)
  - [Good First Issues](#good-first-issues)
- [Code Quality](#code-quality)
- [Pull Request Checklist](#pull-request-checklist)
- [Need Help?](#need-help)

---

## Project Structure

This project is modular-based, and each design pattern has its own module. Here is the structure:

```
pattern-name/
  ├── example1/
  │   ├── src/
  │   ├── pom.xml
  ├── pom.xml
pom.xml
```

### Key Points:

- **`pattern-name`**: Represents a design pattern (e.g., Singleton, Factory).
- **`example1`**: Contains the examples code and a `pom.xml` for a specific implementation of the pattern.

## How to Contribute

### Fork the Repository

1. Fork this repository by clicking the "Fork" button on the top-right corner of this page.
2. Clone your fork locally.
3. Create a new branch for your contribution:
   ```bash
   git checkout -b feature/<your-feature-name>
   ```

### Adding a New Example

1. Open a new issue using the **New Example Issue Template**.
2. Provide an explanation of your example in the issue template fields, including relevant `.puml` diagrams.
3. Wait for approval from the maintainers.
4. Add the example under the corresponding `pattern-name` directory:
   - Create a new directory (e.g., `example2`).
   - Add your implementation.
5. Ensure your code passes the Checkstyle rules.
6. Commit your changes and submit a pull request.

### Adding a New Design Pattern

1. Open a new issue using the **New Pattern Issue Template**.
2. Wait for approval from the maintainers.
3. Create a new directory for the design pattern at the root level.
5. Provide a detailed explanation of the design pattern and its examples in the issue template fields, including `.puml` diagrams if applicable.
6. Commit your changes and submit a pull request.

### Reporting Bugs

1. Open an issue using the **Bug Report Template**.
2. Provide a clear description of the issue, steps to reproduce, and any relevant details.

### Good First Issues

If you are new to the project, look for issues labeled **`good first issue`**. These are beginner-friendly and will help you get started.

## Code Quality

This project uses Checkstyle to maintain code quality. Ensure that your code adheres to the coding standards before submitting a pull request:

1. Install Checkstyle in your development environment.
2. Run Checkstyle locally:
   ```bash
   mvn checkstyle:check
   ```
3. Fix any reported issues.

## Pull Request Checklist

Before submitting your pull request:

1. Ensure your changes are based on the latest `master` branch.
2. Verify that your code adheres to the Checkstyle rules.
3. Provide a meaningful description of your changes in the pull request.
4. Link your pull request to the relevant issue.
5. Add relevant labels to your pull request (e.g., `new pattern`, `new example`).

## Need Help?

If you have any questions or need assistance, feel free to open a discussion or contact the maintainers through GitHub.

Happy coding! 🎉
