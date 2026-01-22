# Contributing to EnsuraScript

Thanks for your interest in contributing to EnsuraScript!

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/GustyCube/EnsuraScript.git`
3. Create a branch: `git checkout -b my-feature`
4. Make your changes
5. Run tests: `go test ./...`
6. Commit and push
7. Open a Pull Request

## Development Setup

```bash
# Build
go build -o ensura ./cmd/ensura

# Run tests
go test ./...

# Run docs locally
cd docs && npm install && npm run docs:dev
```

## What to Contribute

- Bug fixes
- New handlers/adapters
- Documentation improvements
- Example scripts
- Editor integrations

## Code Style

- Follow standard Go conventions
- Run `go fmt` before committing
- Add tests for new functionality

## Reporting Issues

Open an issue with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- EnsuraScript version (`ensura version`)

## Questions?

Open a discussion or issue if you're unsure about anything.
