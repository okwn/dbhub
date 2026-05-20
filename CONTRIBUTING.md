# Contributing to DBHub

We welcome contributions! Here's how to get started.

## Development Setup

```bash
# Clone the repository
git clone https://github.com/bytebase/dbhub.git
cd dbhub

# Install dependencies
pnpm install

# Run in development mode
pnpm dev

# Build for production
pnpm build
```

## Project Structure

```
src/
├── connectors/     # Database-specific implementations
├── tools/          # MCP tool handlers
├── utils/          # Shared utilities
└── index.ts        # Entry point
```

## Testing

```bash
# Run all tests
pnpm test

# Run tests in watch mode
pnpm test:watch

# Run integration tests (requires Docker)
pnpm test:integration
```

## Pull Request Process

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/my-feature`
3. Make your changes and add tests
4. Ensure all tests pass: `pnpm test`
5. Commit your changes with clear commit messages
6. Push to your fork and open a PR against `main`

## Code Style

- Use TypeScript for new code
- Follow existing patterns in the codebase
- Add tests for new functionality

## Reporting Issues

Report bugs and feature requests via [GitHub Issues](https://github.com/bytebase/dbhub/issues).