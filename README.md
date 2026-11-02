### Hi, I'm Austin

**Founder of [dreamd](https://github.com/botzrDev/dreamd).** I'm building long-term memory for AI agents that you can trace, review and roll back.

When an agent acts on something wrong, you should be able to find the memory behind it, see what else it fed, and take it out. dreamd makes that the default. Every memory is a line in a file in your repo, every lesson cites the events it came from, and each dream cycle commits to git, so you review what your agents learned like code.

Try it: `npx -y dreamd-mcp setup`

Works with Claude Code, Cursor, Cline and other MCP harnesses. One local Rust binary, Apache-2.0 core, currently v1.2.0. I build it with my cofounder Joshua Beeney.

Where it's going: a full runtime memory for agents and, later, robots, so they can actually learn over time. Robot support doesn't ship yet; the [roadmap](https://github.com/botzrDev/dreamd/blob/main/ROADMAP.md) says what's next.

### Background

I spent a decade running production infrastructure (Linux and Windows Server, virtualization, identity, networking, incident response) before moving to systems software full time. Before that I directed squadron IT operations in the US Air Force. I also do security research on agent tooling, which is why dreamd says plainly what it does and doesn't protect against.

### Also building

- **[aegis](https://github.com/botzrDev/aegis)**: a reproducible runtime for testing what agent tool isolation actually guarantees. Rust on wasmtime. `MIT`
- **[mcp-guard](https://github.com/botzrDev/mcp-guard)**: a security gateway for MCP servers, with authentication and per-tool authorization. `AGPL-3.0` core

### Writing

- **[Provenance Is Not Independence](https://doi.org/10.5281/zenodo.21431717)**: why agents that share a source get miscounted as independent corroboration, and a deterministic check for it.
- **[The Individuation Architecture](https://doi.org/10.5281/zenodo.21441573)**: agent identity as a developmental problem rather than a configuration one.

### Reach me

Star [dreamd](https://github.com/botzrDev/dreamd) to follow releases, or open an issue with your `blame` output when a memory goes wrong.

[dreamd.dev](https://dreamd.dev) · [X @dreamd_dev](https://x.com/dreamd_dev) · [LinkedIn](https://www.linkedin.com/in/dreamddev/) · austin@botzr.com
