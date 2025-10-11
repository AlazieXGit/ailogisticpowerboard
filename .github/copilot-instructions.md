# Copilot Instructions for AI Logistic Power Board

## Project Overview
This is the AI Logistic Power Board project, which appears to be focused on AI-powered logistics solutions. The repository supports multiple technology stacks including Python, Node.js, and AI/ML components.

## Coding Standards

### General Guidelines
- Write clean, readable, and maintainable code
- Follow established patterns and conventions found in the existing codebase
- Add meaningful comments for complex logic or algorithms
- Use descriptive variable and function names
- Keep functions focused on a single responsibility

### Python Standards (if applicable)
- Follow PEP 8 style guidelines
- Use type hints where appropriate
- Write docstrings for functions, classes, and modules
- Use virtual environments for dependency management

### JavaScript/Node.js Standards (if applicable)
- Follow standard JavaScript/ES6+ conventions
- Use consistent indentation (2 or 4 spaces)
- Prefer const and let over var
- Use async/await for asynchronous operations

## Project Structure
- `.gitignore` - Comprehensive ignore patterns for OS files, IDEs, Python, Node.js, AI/ML artifacts, and sensitive data
- Repository root contains project configuration files

## Development Workflow

### Setting Up the Development Environment
1. Clone the repository
2. Install dependencies based on the technology stack used
   - For Python projects: `pip install -r requirements.txt` (if requirements.txt exists)
   - For Node.js projects: `npm install` or `yarn install` (if package.json exists)
3. Configure environment variables if needed (use .env files, never commit secrets)

### Version Control
- Create feature branches for new work
- Write clear, descriptive commit messages
- Keep commits focused and atomic
- Review changes before committing

## AI/ML Specific Guidelines
- Store trained models in the `models/` directory (already gitignored)
- Keep checkpoints in the `checkpoints/` directory (already gitignored)
- Document model architecture and hyperparameters
- Include training and evaluation scripts
- Version control model configurations and training scripts, but not the large binary model files

## Security Best Practices
- Never commit sensitive data (API keys, passwords, credentials)
- Use environment variables for configuration
- Keep `.env` files in .gitignore
- Store secrets securely using appropriate secret management tools
- Review the .gitignore to ensure sensitive files are excluded

## Testing
- Write tests for new features and bug fixes
- Ensure tests pass before submitting pull requests
- Follow the existing test structure and conventions in the repository

## Documentation
- Update documentation when making significant changes
- Document API endpoints, function signatures, and complex algorithms
- Keep README.md up to date with setup instructions and usage examples

## Dependencies
- Keep dependencies up to date but test thoroughly after updates
- Document any new dependencies added to the project
- Use lock files (package-lock.json, yarn.lock, Pipfile.lock) to ensure reproducible builds

## Pull Requests
- Provide clear descriptions of changes
- Reference related issues
- Ensure code passes all tests and linting checks
- Request reviews from appropriate team members

## Notes for Copilot
- This is an AI logistics project, so context about logistics operations, optimization, and AI/ML concepts may be relevant
- The project supports multiple technology stacks, so check file extensions and context before generating code
- Pay attention to the comprehensive .gitignore file to understand which files and directories should not be tracked
