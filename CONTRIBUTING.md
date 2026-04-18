# Contributing to A2A-SIN-Teams

Thank you for your interest in contributing!

## Getting Started

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/my-feature`
3. Make your changes
4. Run tests: `npm test`
5. Commit with conventional commits: `git commit -m "feat: add my feature"`
6. Push and open a PR

## Communication

- Always leave screenshots for visual changes
- Always leave a detailed PR description
- Always review your code first
- Always communicate in GitHub (issues or PRs)

## Code Style

- Use TypeScript
- Follow existing patterns
- Write tests for new features
- JSDoc on all exported functions

## Boundary Rules

Before adding a feature or top-level claim, answer:

1. Is this about Teams messaging integration, or is it broader team-management truth?
2. Does another OpenSIN repo already own the canonical source of truth?

### Put it in `A2A-SIN-Teams` if:
- it improves Teams messaging integration
- it improves this repo's A2A agent behavior

### Do NOT put it in `A2A-SIN-Teams` if:
- it claims org-wide team registry ownership
- it duplicates product, ops, or docs canon

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
