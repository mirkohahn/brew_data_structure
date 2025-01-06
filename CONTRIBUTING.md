# Contributing to the Repository

We welcome contributions to improve and expand this project! Whether you're fixing bugs, suggesting enhancements, or adding new features, your input is valuable. Please follow these guidelines to ensure a smooth contribution process.

---

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful and considerate of others.

---

## How to Contribute

### 1. Reporting Issues
- Search existing issues to avoid duplicates.
- Open a new issue if your problem or suggestion isn’t already covered.
- Provide a detailed description and steps to reproduce (if applicable).

### 2. Suggesting Features
- Create a new issue tagged with `enhancement`.
- Clearly describe the feature, its purpose, and potential use cases.

### 3. Submitting Changes

#### a. Fork the Repository
- Click the "Fork" button on the repository page.
- Clone your fork locally:
  ```bash
  git clone https://github.com/mirkohahn/brew_data_structure.git
  cd repo-name
  ```

#### b. Create a Branch
- Use a descriptive branch name:
  ```bash
  git checkout -b feature/your-feature-name
  ```

#### c. Make Your Changes
- Follow the repository's coding standards (e.g., file naming, formatting).
- Document changes in relevant files (e.g., `README.md`, examples, or documentation).

#### d. Commit Your Changes
- Write clear and concise commit messages:
  ```bash
  git add .
  git commit -m "Add feature: detailed description"
  ```

#### e. Push Your Changes
- Push your branch to your forked repository:
  ```bash
  git push origin feature/your-feature-name
  ```

#### f. Open a Pull Request
- Go to the original repository on GitHub.
- Click "Compare & pull request."
- Provide a detailed description of your changes.

---

## Development Workflow

1. **Set Up Your Environment**:
   - Install dependencies:
     ```bash
     npm install
     ```
   - Run tests:
     ```bash
     npm test
     ```

2. **Run Linters and Formatters**:
   - Ensure your code adheres to the coding style:
     ```bash
     npm run lint
     npm run format
     ```

3. **Write Tests**:
   - Add or update test cases for your changes in the `tests/` directory.
   - Ensure all tests pass before submitting your pull request.

---

## Review Process
- All pull requests are reviewed by maintainers.
- Changes may be requested to align with project standards.
- Be responsive to feedback to ensure a timely merge.

---

## Additional Notes
- Ensure your changes are consistent with the project’s purpose and roadmap.
- Respect existing coding conventions and architecture.
- Contributions without proper documentation or tests may not be accepted.

Thank you for contributing! 🚀
🍺 Now go and have a beer!