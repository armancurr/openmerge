# Openmerge

CLI tool that looks at your code changes and automatically generates commit messages and PR descriptions. Openmerge analyzes your git diff and creates meaningful, conventional commits so you never have to think about commit messages again.

## Features

1. **Smart Commit Message Generation**  
Analyzes your code changes and creates descriptive, conventional commit messages automatically.

2. **Automated PR Descriptions**  
Generates comprehensive pull request descriptions based on your commits and code changes.

3. **Conventional Commit Standard**  
Follows industry-standard commit message formats (feat, fix, docs, etc.) for consistent project history.

4. **Git Integration**  
Works seamlessly with your existing git workflow - just run the command and commit.

## Contributing

Want to help make Openmerge better? Here's how:

1. Fork this repository
2. Create a new branch for your feature
3. Make your changes and test them
4. Submit a pull request with a clear description

We welcome bug fixes, new features, and documentation improvements.

## Installation & Setup

```bash
# Clone the repository
git clone https://github.com/armancurr/openmerge.git

# Navigate to project directory
cd openmerge

# Install dependencies
bun install

# Build the CLI tool
bun run build

# Install globally
bun install -g openmerge

# Use in any git repository
cd your-project
openmerge commit
openmerge pr-description
```
