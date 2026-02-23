# OpenSource Framework

> Maintained forks of abandoned npm packages

[![License](https://img.shields.io/github/license/opensourceframework/opensourceframework.svg)](./LICENSE)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

## About

OpenSource Framework is a monorepo dedicated to maintaining forks of abandoned npm packages. We ensure these valuable tools continue to receive security updates, bug fixes, and compatibility improvements.

## Available Packages

| Package | Original | Status | Description |
|---------|----------|--------|-------------|
| [@opensourceframework/next-csrf](./packages/next-csrf) | [next-csrf](https://www.npmjs.com/package/next-csrf) | ![Maintenance](https://img.shields.io/maintenance/yes/2026.svg) | CSRF protection for Next.js |
| [@opensourceframework/next-images](./packages/next-images) | [next-images](https://www.npmjs.com/package/next-images) | ![Maintenance](https://img.shields.io/maintenance/yes/2026.svg) | Image optimization for Next.js |
| [@opensourceframework/critters](./packages/critters) | [critters](https://www.npmjs.com/package/critters) | ![Maintenance](https://img.shields.io/maintenance/yes/2026.svg) | CSS inlining for SSR |

## Why OpenSource Framework?

Many npm packages become abandoned over time, leaving projects vulnerable to:
- **Security vulnerabilities** - No security patches for discovered vulnerabilities
- **Compatibility issues** - No updates for new Node.js or framework versions
- **Bug persistence** - Known bugs remain unfixed
- **TypeScript gaps** - Missing or outdated type definitions

OpenSource Framework solves these problems by:
- **Active maintenance** - Regular updates and security patches
- **Community-driven** - Open to contributions and feedback
- **Transparency** - Clear provenance and changelogs for all packages
- **Quality standards** - Enforced code standards, testing, and CI/CD

## Quick Start

### Installation

```bash
# Using npm
npm install @opensourceframework/[package-name]

# Using yarn
yarn add @opensourceframework/[package-name]

# Using pnpm
pnpm add @opensourceframework/[package-name]
```

### Migration from Original Packages

Simply update your imports:

```diff
- import { something } from 'original-package';
+ import { something } from '@opensourceframework/original-package';
```

## Contributing

We welcome contributions! Please see our [Contributing Guide](./CONTRIBUTING.md) for details.

### Ways to Contribute

- **Report bugs** - Open an issue with detailed reproduction steps
- **Suggest features** - Share your ideas in discussions or issues
- **Submit PRs** - Fix bugs, add features, or improve documentation
- **Review code** - Help maintain code quality
- **Spread the word** - Star the repo and share with others

## Development

### Prerequisites

- Node.js 20+
- pnpm 9+

### Setup

```bash
# Clone the repository
git clone https://github.com/opensourceframework/opensourceframework.git
cd opensourceframework

# Install dependencies
pnpm install

# Build all packages
pnpm build

# Run tests
pnpm test

# Lint code
pnpm lint
```

### Project Structure

```
opensourceframework/
â packages/           # Forked packages
â  â next-csrf/      # CSRF protection for Next.js
â  â next-images/    # Image optimization for Next.js
â  â critters/       # CSS inlining for SSR
â tools/              # Shared tooling configurations
â .github/            # GitHub templates and workflows
â plans/             # Architecture and planning documents
```

## Sponsoring

Help sustain this project by becoming a sponsor:

- [GitHub Sponsors](https://github.com/sponsors/opensourceframework)
- [Open Collective](https://opencollective.com/opensourceframework)

Sponsors get:
- Recognition in README and releases
- Priority issue triage
- Input on package priorities

## Security

We take security seriously. Please see our [Security Policy](./SECURITY.md) for details on reporting vulnerabilities.

## License

This repository is licensed under the [MIT License](./LICENSE). Individual packages may retain their original licenses if different.

## Acknowledgments

- Original package authors for their valuable contributions
- All contributors who help maintain these packages
- Our sponsors for financial support

---

Made with ð by the OpenSource Framework community\n\n---\n\nMaintained by @opensourceframework in the [monorepo](https://github.com/riceharvest/opensourceframework).