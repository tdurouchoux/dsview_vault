---
already_read: true
link: https://www.anthropic.com/research/redesigning-source-control
read_priority: 0
relevance: 4
source: Alpha Signal
tags:
- DevOps
type: Content
upload_date: '2026-11-15'
---

https://www.anthropic.com/research/redesigning-source-control

## Summary

Anthropic built Scion, an in-house version control system, to handle the explosive growth of AI-driven code changes (from 2,500 to 30,000+ merges/day) that outpaced traditional git-based workflows.

**Problem & Scale**
- Anthropic’s monorepo grew to 100GB history, 25GB compressed working copy, and 25M daily checkouts for CI.
- Git’s decentralized, offline-first design (shallow clones, sparse checkouts, mirrors) became unsustainable at this scale.
- Previous workarounds (hundreds of git mirrors, seeds) failed as merge rates increased.

**Scion’s Core Principles**
- Clients are always online, so Scion fetches data on-demand instead of storing full repos locally.
- Client-server asymmetry: server handles all logic (commits, merges, blame), client only caches and manages working copies.
- Comprehensive API exposes source control queries, eliminating the need for local repos in many workflows.
- Horizontally scalable: no full repo materialization, no packfiles, no maintenance overhead.
- Commits are server-side, incremental, and lock-free, with cost scaling to change size, not repo size.
- Working copies are optional and sparse/virtualized by design.

**Technical Design**
- **Data Structures**: Changesets (write-ahead log entries) store only changed files and content-addressed blobs. Derived data (blame, path history) is computed recursively and lazily.
- **Scaling**: Tiered caching (scion-daemon → scion-cache → scion-server) with >99% hit rates, 200x smaller footprint than git mirrors, and 25% CI CPU savings.
- **Protocol**: Client requests specific trees/blobs recursively, enabling efficient sparse/virtual checkouts without special support.

**Lessons & Impact**
- Built by a 7-person team in 5 months while merge volume grew 10x, showcasing rapid agent-assisted development.
- Engineers focused on high-level design and constraints, often directing Claude to avoid over-engineering or anti-patterns.
- Scion enabled new security models (fine-grained permissions) and operational excellence (Claude "superfans" monitoring components).
- Rethinking workflows: post-merge testing, agent-driven conflict resolution, and elimination of global locks.

**Broader Implications**
- Scion is not a general git replacement but a case study for agent-scale monorepos.
- Git platforms could adopt Scion-like server-side RPCs, sparse protocols, or tiered caching to scale.
- Shared learnings aim to help the ecosystem (GitHub, GitLab, OSS) adapt to AI-driven development.

## Links

- [Sapling SCM - Facebook's Monorepo Source Control System](https://sapling-scm.com/) : Official documentation and overview of Sapling, a source control system developed by Meta (formerly Facebook) that pioneered techniques used in Anthropic's Scion, such as the Bonsai data model and server-side source control architecture.
- [Piper Source Control System - Wikipedia](https://en.wikipedia.org/wiki/Piper_(source_control_system)) : Wikipedia page for Piper, Google's large-scale monorepo source control system, which is referenced as prior art for Scion's design principles and scaling challenges.
- [Claude Mythos - Anthropic's AI Model](https://www.anthropic.com/claude/mythos) : Official page for Claude Mythos, an AI model mentioned in the content as a key driver for Anthropic's development needs and Scion's rapid iteration.
- [Introducing Claude Tag - Anthropic's AI Monitoring Tool](https://www.anthropic.com/news/introducing-claude-tag) : Blog post introducing Claude Tag, an AI-powered monitoring tool used by Anthropic's engineering team to maintain operational excellence in systems like Scion.


## Topics

![[topics/Platform/Scion]]

![[topics/Tool/Antique]]

![[topics/Concept/Agent scale source control]]

![[topics/Concept/Changeset]]

![[topics/Concept/Derived data]]

![[topics/Platform/Spanner]]

![[topics/Tool/scion daemon]]

![[topics/Tool/scion cache]]