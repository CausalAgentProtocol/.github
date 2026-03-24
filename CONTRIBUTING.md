# Contributing to Causal Agent Protocol

Thank you for your interest in contributing to the **Causal Agent Protocol (CAP)**!

This document provides high-level guidelines for contributing to any repository in the `CausalAgentProtocol` organization. We have a lightweight, maintainer-driven model for Phase 1.

For maintainer contact, developer-group coordination, or contribution questions that do not fit a repository issue, email `cap@abel.ai`.

## Where to Contribute

The CAP organization is divided into specialized repositories. Please direct your contributions to the appropriate repository:

- **Protocol Specification**: To propose changes to the CAP normative specification, concepts, or website, open issues and PRs in the [`cap` repository](https://github.com/CausalAgentProtocol/cap).
- **Python SDK**: To propose changes, bug fixes, or enhancements to the Python contracts, server framework, or client helpers, use the [`python-sdk` repository](https://github.com/CausalAgentProtocol/python-sdk).
- **Official Example Server**: To contribute to the CAP organization's minimal example server, use the [`cap-example` repository](https://github.com/CausalAgentProtocol/cap-example).

## Proposing Protocol Changes

To propose a change to the CAP protocol itself:
1. Open an issue in the `cap` repository to discuss the proposed change.
2. Draft your proposal with rationale, detailing how it impacts existing graphs and agents.
3. Wait for maintainer review and consensus before opening a Pull Request with spec changes.

**Caution: Backward Compatibility**
Changes to the protocol must be made with extreme caution. Breaking changes are generally rejected unless they are part of a major version bump. Please detail backward-compatibility strategies in your proposals.

## Expectation for PRs

For all code and SDK changes:
- **Tests**: Every new feature or bug fix must include appropriate tests demonstrating the feature or the fix.
- **Documentation**: If you change a public API or protocol surface, you must update the corresponding README or docstrings.
- **CI**: All continuous integration checks (linting, type checking, tests) must pass before a PR can be merged.

## Commit and Branch Conventions

We follow a structured convention for branches and commits.

### Branch Naming
Format: `<type>/<short-description>`

Examples: `feat/add-new-verb`, `fix/sdk-timeout`, `docs/update-readme`

Allowed types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`

### Commit Messages
Format: `<type>: <short summary>`

Examples:
- `feat: add Python SDK support for new verb`
- `fix: correctly parse empty graph response`
- `docs: clarify bridging semantics`

Keep summaries concise, use lowercase, and be action-oriented.
