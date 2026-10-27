# 👋 Welcome!

I'm Liam, a Software Engineer based in Canada, I'm currently working as a Lead Developer at [EducationPlannerBC](https://www.educationplannerbc.ca/),
During the day I work primarily in Go and TypeScript, but I've been wrestling with Rust lately and loving it.

## Featured Projects

### [Forage](https://github.com/LiamCoop/Forage)

A live job feed built from the career pages of companies you choose, so you see a posting within the hour it goes up. The crawler tracks ~1,800 postings across 30 companies by diffing normalized listing snapshots, detecting new, closed and reopened roles. It detects the ATS (Greenhouse, Lever, Ashby) and uses its public API, falling back to generic HTML scraping and then headless Playwright, so 29 of 30 companies never need a browser. On top of the feed: a semantic title filter built on Voyage embeddings, Claude-powered requirement extraction and fit scoring using forced tool calls that reject unknown IDs so it can't invent facts, and an authenticated MCP server that exposes the feed to agents.

**Tech Stack:** Python, FastAPI, SQLAlchemy, PostgreSQL, Playwright, TypeScript, React, TanStack Start, Clerk, Voyage AI, Claude, MCP, Railway

### [MD-Editor](https://github.com/LiamCoop/md-editor)

A real-time collaborative markdown editor for teams with automatic merge handling, live presence, threaded review comments, and offline-first sync.

**Tech Stack:** TypeScript, Next.js, Automerge

### [Rules Engine](https://github.com/LiamCoop/rules)

A high-throughput rules engine that evaluates complex user-defined schemas using Common Expression Language. Achieves ~7k requests per second per instance through in-memory caching and precomputed evaluation environments.

**Tech Stack:** Go, PostgreSQL

### [Observability Agent](https://github.com/LiamCoop/observability-agent)

An alert investigation agent that accepts Grafana alert webhooks, queues long-running investigations, and runs a LangGraph workflow to gather metrics, logs, traces, dashboards, and alert context before generating evidence-backed likely-cause summaries.

**Tech Stack:** TypeScript, Node.js, LangGraph, OpenAI, Grafana, Redis, BullMQ

## GitHub Stats

![](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=LiamCoop&theme=gruvbox)

## 📫 How to Reach Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/liamcoop/)
