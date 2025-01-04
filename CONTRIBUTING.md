# Contributing to DailyCard

First off, thank you for considering contributing to DailyCard! It's people like you that make DailyCard such a great tool. 👏

## Code of Conduct

By participating in this project, you are expected to uphold our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

## How Can I Contribute? 🤔

### Reporting Bugs 🐛

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* **Use a clear and descriptive title**
* **Describe the exact steps to reproduce the problem**
* **Provide specific examples to demonstrate the steps**
* **Describe the behavior you observed after following the steps**
* **Explain which behavior you expected to see instead and why**
* **Include screenshots and animated GIFs if possible**

### Suggesting Enhancements 💡

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* **Use a clear and descriptive title**
* **Provide a step-by-step description of the suggested enhancement**
* **Provide specific examples to demonstrate the steps**
* **Describe the current behavior and explain the behavior you expected to see instead**
* **Explain why this enhancement would be useful**

### Pull Requests 🚀

* Fork the repo and create your branch from `main`
* If you've added code that should be tested, add tests
* If you've changed APIs, update the documentation
* Ensure the test suite passes
* Make sure your code lints
* Issue that pull request!

## Development Setup 🛠️

1. Fork the repo
2. Clone your fork
```bash
git clone https://github.com/your-username/dailycard.git
cd dailycard
```
3. Install dependencies
```bash
npm install
```
4. Create a branch for your feature
```bash
git checkout -b feature/amazing-feature
```

### Coding Style 📝

* Use 2 spaces for indentation
* Use camelCase for variable and function names
* Use PascalCase for component names
* Add comments for complex logic
* Follow our ESLint configuration

```javascript
// Good
function calculateTotal() {
  // Logic here
}

// Bad
function calculate_total() {
  // Logic here
}
```

### Commit Messages 📝

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

Example:
```
feat: add email validation for digital cards

- Implement regex pattern for email validation
- Add error messaging for invalid emails
- Update unit tests

Closes #123
```

### Branch Naming Convention 🌲

* Feature branches: `feature/description`
* Bug fix branches: `fix/description`
* Documentation branches: `docs/description`
* Performance improvement branches: `perf/description`

Example: `feature/add-qr-code-generator`

## Testing 🧪

* Write unit tests for all new features
* Ensure all tests pass before submitting a PR
* Include both positive and negative test cases
* Follow the existing testing patterns

```bash
# Run all tests
npm run test

# Run specific test file
npm run test path/to/test-file.test.js
```

## Documentation 📚

* Update the README.md if needed
* Add JSDoc comments for all new functions and classes
* Update API documentation if you change any endpoints
* Include code examples where appropriate

## Review Process 👀

1. Submit your pull request
2. Maintainers will review your code
3. Address any comments or requested changes
4. Once approved, your code will be merged

## Getting Help 🆘

* Check our [documentation](https://docs.dailycard.net)
* Join our [Discord community](https://discord.gg/dailycard)
* Email us at developers@dailycard.net

## Recognition 🏆

Contributors are listed in our [CONTRIBUTORS.md](CONTRIBUTORS.md) file. We also highlight significant contributions on our blog and social media channels.

## Additional Notes 📌

### Issue Labels

* `bug` - Something isn't working
* `enhancement` - New feature or request
* `documentation` - Improvements or additions to documentation
* `good first issue` - Good for newcomers
* `help wanted` - Extra attention is needed

### Security Issues 🔒

If you discover a security vulnerability, please send an email to security@dailycard.net instead of opening a public issue.

---

Thank you for contributing to DailyCard! 🙏

*This guide was inspired by best practices from various open source projects and adapted for DailyCard's specific needs.*
