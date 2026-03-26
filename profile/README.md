# Causal Agent Protocol

<p align="center">
  <img src="./assets/light.svg" alt="Causal Agent Protocol" />
</p>

**CAP** is an open protocol that gives AI agents a structured way to perform **causal reasoning** — discovering variables, traversing cause-and-effect graphs, and answering "why" questions through a well-defined verb-based interface.

## Why CAP?

Most agent protocols focus on tool invocation or retrieval. CAP adds a **causal layer**: agents can explore causal graphs, compute interventions, and generate evidence-backed explanations — all through a transport-agnostic protocol that any runtime can implement.

## Getting Started

- Start with **[cap](https://github.com/CausalAgentProtocol/cap)** for the CAP overview, getting started guides, and normative specification
- Use the **[Python SDK](https://github.com/CausalAgentProtocol/python-sdk)** to build or integrate a CAP-compatible agent
- Explore **[cap-example](https://github.com/CausalAgentProtocol/cap-example)** for the official minimal CAP example server

## What's Next

We plan to open-source a larger `cap-example` follow-up built around a financial causal graph with roughly 500 nodes.

The goal is to give implementers a more realistic public graph for testing capability discovery, graph traversal, intervention semantics, and semantic honesty without relying on proprietary data.

## Contributing

We welcome contributions! Please read our [Contributing Guide](https://github.com/CausalAgentProtocol/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/CausalAgentProtocol/.github/blob/main/CODE_OF_CONDUCT.md) before getting started.

## License

All CAP repositories are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
