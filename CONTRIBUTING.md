# Contributing to Autonomous Infrastructure Platform

Thank you for your interest in contributing to the Autonomous Infrastructure Platform! This document provides guidelines for contributing to any repository in the `autonomous-bits` organization.

## 🤝 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🚀 How to Contribute

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When creating a bug report, include:

- **Description**: Clear description of the issue
- **Steps to Reproduce**: Detailed steps to reproduce the behavior
- **Expected Behavior**: What you expected to happen
- **Actual Behavior**: What actually happened
- **Environment**: OS, platform version, etc.
- **Additional Context**: Screenshots, logs, etc.

### Suggesting Features

Feature requests are welcome! Please provide:

- **Description**: Clear description of the feature
- **Use Case**: Why this feature would be useful
- **Proposed Solution**: How you envision the feature working
- **Alternatives**: Alternative solutions you've considered

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following our coding standards
3. **Add tests** for any new functionality
4. **Update documentation** as needed
5. **Ensure CI passes** all checks
6. **Submit a pull request** with a clear description

#### Pull Request Guidelines

- Use a clear and descriptive title
- Reference any related issues
- Include a summary of changes
- Add screenshots for UI changes
- Ensure all tests pass
- Follow the repository's coding style

## 🛠️ Development Setup

### General Requirements
- Node.js 18+ 
- npm or yarn
- Git
- Azure CLI (for Azure-related repositories)

### Repository-Specific Setup
Each repository has its own setup instructions in its README. Generally:

```bash
# Clone the repository
git clone https://github.com/autonomous-bits/[repository-name]
cd [repository-name]

# Install dependencies
npm install

# Run tests
npm test

# Start development server (if applicable)
npm run dev
```

## 📏 Coding Standards

### TypeScript/JavaScript
- Use TypeScript for all new code
- Follow ESLint configuration
- Use Prettier for formatting
- Write comprehensive JSDoc comments
- Prefer functional programming patterns

### Commit Messages
Follow conventional commits format:

```
type(scope): description

[optional body]

[optional footer]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Examples:
- `feat(cli): add stamp validation command`
- `fix(mcp): resolve connection timeout issue`
- `docs(readme): update installation instructions`

### Testing
- Write unit tests for all new functions
- Write integration tests for APIs
- Aim for >80% code coverage
- Use descriptive test names
- Follow AAA pattern (Arrange, Act, Assert)

## 🏗️ Architecture Guidelines

### Service Design
- Follow microservices principles
- Use dependency injection
- Implement proper error handling
- Add comprehensive logging
- Design for observability

### API Design
- Use RESTful principles
- Version APIs appropriately
- Include proper HTTP status codes
- Document with OpenAPI/Swagger
- Implement rate limiting

### Database Design
- Use migrations for schema changes
- Index frequently queried columns
- Implement proper foreign keys
- Consider data retention policies

## 🔒 Security Guidelines

- Never commit secrets or credentials
- Use environment variables for configuration
- Implement proper authentication/authorization
- Validate all inputs
- Use HTTPS for all communications
- Follow OWASP guidelines

## 📚 Documentation

- Update README files for significant changes
- Add inline code comments for complex logic
- Create/update API documentation
- Include examples and tutorials
- Keep documentation synchronized with code

## 🏷️ Issue and PR Labels

### Priority Labels
- `priority/critical` - Security issues, production outages
- `priority/high` - Important features, significant bugs
- `priority/medium` - Standard features and bugs
- `priority/low` - Nice to have features, minor issues

### Type Labels
- `type/bug` - Something isn't working
- `type/feature` - New feature request
- `type/enhancement` - Improvement to existing feature
- `type/documentation` - Documentation improvements

### Component Labels
- `component/api` - Backend API changes
- `component/ui` - Frontend/UI changes
- `component/infrastructure` - Infrastructure code
- `component/agent` - AI agent related

## 🔄 Release Process

1. **Feature Development**: Work in feature branches
2. **Code Review**: All changes require review
3. **Testing**: Comprehensive testing required
4. **Documentation**: Update docs as needed
5. **Release**: Follow semantic versioning

## ❓ Getting Help

- Check existing documentation
- Search existing issues
- Join our [Discussions](https://github.com/orgs/autonomous-bits/discussions)
- Reach out to maintainers

## 📞 Contact

- **Discussions**: [GitHub Discussions](https://github.com/orgs/autonomous-bits/discussions)
- **Issues**: Repository-specific issue trackers
- **Security**: [Security Policy](SECURITY.md)

Thank you for contributing to the Autonomous Infrastructure Platform! 🎉
