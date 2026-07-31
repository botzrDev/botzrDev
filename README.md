
### Hi, I'm Austin 👋

  **Lead Infrastructure Engineer.** Distributed systems, Rust, and the layer AI agents
  actually run on.

  I spent a decade operating production infrastructure — Linux and Windows Server,
  virtualization, identity, networking, incident response — before moving to systems
  software full time. My foundation is the US Air Force, where I directed squadron IT
  operations and held a Secret clearance. That's where I learned security isn't a layer
  you add later.

  Everything below is open source, local-first, and measured rather than asserted.

  ### 🔭 What I'm building

  **[botzr-aegis](https://github.com/botzrDev/aegis)** — a capability-based execution
  runtime for AI agent tools. Eight crates on crates.io — `cargo install botzr-aegis-cli`.
  Every tool call passes a policy → capability → sandbox → audit pipeline before it runs.
  Isolation is wasmtime + the WebAssembly Component Model (WASI Preview 2): default-deny
  networking, cap-std filesystem preopens, per-call memory limits, epoch-based
  interruption. Policy evaluation benchmarks at **32 ns**, the policy-and-capability
  hot path at **2.7 µs**. `MIT`

  **[dreamd](https://github.com/botzrDev/dreamd)** — a portable memory layer for AI coding
  agents. One `.agent/` folder shared across Claude Code, Cursor, Cline, and anything else
  that speaks MCP. Plain JSONL you can grep, diff, and hand-edit. BM25 retrieval over a
  single-writer Tantivy index — no embedding model, no GPU, no telemetry. v0.1 public
  **August 9**. `Apache-2.0`

  **[mcp-guard](https://github.com/botzrDev/mcp-guard)** — a security gateway for Model
  Context Protocol servers. stdio, HTTP, and SSE transports, with API key authentication,
  JWT validation, OAuth 2.1, and per-tool authorization. `AGPL-3.0`

  **[uveddi](https://github.com/botzrDev/uveddi)** — multi-language architectural analysis
  across Rust, Python, JavaScript, and TypeScript. Tree-sitter based, with SARIF security
  export and WebAssembly plugin support.

  **ECHOS** *(unreleased — no public repo yet)* — security research into how agent
  tooling actually fails, disclosed privately before publication. Findings, not
  think-pieces.

  ### 📄 Writing

  - **[Provenance Is Not Independence](https://doi.org/10.5281/zenodo.21431717)** —
    reconstructing provenance doesn't establish source independence, so agents sharing an
    epistemic ancestor get miscounted as independent corroboration. Proposes a deterministic
    lineage-set check using Kish effective sample size over W3C PROV-DM, with no model calls
    in the hot path.
  - **[The Individuation Architecture](https://doi.org/10.5281/zenodo.21441573)** — agent
    identity as a developmental problem rather than a configuration one, compared against 12
    adjacent approaches.

  ### 📫 Reach me

  I build in public because infrastructure gets better when people can check it. Review the
  code, open an issue, or argue with me about a benchmark.

  **Currently open to senior and lead infrastructure roles — fully remote.**

  [LinkedIn](https://www.linkedin.com/in/dreamddev/) · austin@botzr.com

