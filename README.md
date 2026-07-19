<div align="center">

# Jinx

### I build AI systems that can hold state, survive failure, and finish the job.

`agent runtimes` · `workflow engineering` · `developer tools` · `applied research`

</div>

I started with web interfaces and build tooling. These days I work closer to the boundaries between agents, runtimes, data, and people—mostly in TypeScript, with Rust and Python where the system calls for them.

I care about making AI work operational: explicit state, recoverable execution, human checkpoints, useful observability, and evidence that the real path works.

## Recent public work

| Project | What I am exploring |
| --- | --- |
| [Agent Skills](https://github.com/Jinx-1120/skills) | Portable, evidence-first workflows for coding agents—designed around clear outcomes, adaptive depth, and truthful completion. |
| [MDX Renderer](https://github.com/Jinx-1120/mdx-renderer) | A browser-based MDX playground with isolated preview, custom components, local persistence, and a deliberately small runtime. |
| [agent-cli](https://github.com/Jinx-1120/creater-cli) | An experiment in multi-agent software workflows with durable state, DAG scheduling, human checkpoints, and breakpoint recovery. |

## How I work

```text
inspect reality → model state & failure → ship a focused slice → verify the boundary → document the contract
```

- Real runtime evidence beats plausible-looking output.
- State, failure, recovery, and cancellation are product work—not cleanup.
- Tests, docs, config, and examples should ship with the behavior they describe.
- Repetition is usually a signal to build a tool, adapter, or reusable workflow.
- I prefer small, descriptive commits and progressive hardening over one opaque rewrite.

## Current toolbox

- **Languages:** TypeScript · Rust · Python · SQL
- **Frontend:** React · Next.js · Vite · Tailwind CSS · shadcn/ui · Storybook · React-Native · Flutter
- **Backend & data:** Bun · Node.js · Hono · Drizzle ORM · PostgreSQL · ClickHouse · Redis · BullMQ · Polars
- **AI & interfaces:** AI SDK · MCP · oRPC · TanStack Query · Zod · hermes-agent
- **Engineering:** Turborepo · Biome · Vitest · Bun Test · Rstest · Docker · Kubernetes · Helm · OpenTelemetry · GitHub Actions

---

If you are working on durable agents, developer infrastructure, or better human–agent workflows, I am interested in the hard parts: ownership, recovery, and proving that the system actually works.
