# OpenIPERA
### Engineering Enterprise Services

**OpenIPERA models the system. Orchestration and automation operate the system.**

[Website](https://openipera.io/) · [Architecture](https://openipera.io/architecture.html) · [Documentation](https://openipera.io/documentation.html) · [Source and experiments](https://github.com/openipera/openipera-architecture)

## Why OpenIPERA?

Organizations can automate individual infrastructure and application tasks while still lacking an explicit, maintainable representation of the **knowledge, dependencies, policies, and operational obligations** that make a service complete.

A request for a service—whether a simple virtual machine or a complex electronic medical record system—requires more than provisioning infrastructure or installing software. The dependencies, governance, security, monitoring, and acceptance obligations must also be satisfied and sustained.

**OpenIPERA separates knowledge of the service from the mechanisms used to realize it.**

## From intent to execution

1. **Service contracts** express the requested service and its obligations.
2. A **Service Model DAG (SM-DAG)** represents service decomposition and dependencies through Service Nodes and Atomic Nodes.
3. **Lifecycle Cards** associate the model with governed, versioned service knowledge and atomic automation bindings.
4. A **Service Model Validator** checks model integrity and consistency.
5. A **compiler** resolves the model and request context into a **Service Object Graph (SOG)**.
6. External **orchestration and execution platforms** consume that representation to carry out the necessary work.

The **SOG** is a mathematical representation of what must be accomplished and sustained to fully operationalize a service. It describes *what must be true, what must happen, and what must remain true*—not a predefined automation workflow.

## What OpenIPERA is not

OpenIPERA is **not another workflow engine, automation framework, or sophisticated way to construct static workflows**. It is intended to work with existing orchestration and automation platforms, not replace them.

## Explore

- **[OpenIPERA website](https://openipera.io/)** — the project overview and architectural narrative
- **[Reference and functional architecture](https://openipera.io/architecture.html)** — the capabilities and how they relate
- **[Documentation](https://openipera.io/documentation.html)** — technical explanations and specifications
- **[openipera-architecture](https://github.com/openipera/openipera-architecture)** — architecture source, experimental work, and implementation artifacts

## Licensing and identity

OpenIPERA software is licensed under **[Apache License 2.0](https://github.com/openipera/openipera-architecture/blob/main/LICENSE)**. Original architecture documentation and technical diagrams are licensed under **[CC BY 4.0](https://github.com/openipera/openipera-architecture/blob/main/LICENSE-DOCUMENTATION.md)**, unless otherwise noted. The OpenIPERA name and woven-eye visual identity are **[reserved project branding](https://github.com/openipera/openipera-architecture/blob/main/BRANDING.md)**.

**Workflows are derived from knowledge of the system. Knowledge of the system is not derived from workflows.**
