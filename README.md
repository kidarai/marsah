# Marsah

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

**Autonomy by construction**

Marsah is a deterministic controller for AI coding agents. You describe a feature, and a Python controller drives model workers through a fixed pipeline: specify, build, run the quality gates, review in parallel, verify against live state, capture the evidence, commit, audit.

The graph, the retry budgets, and a hash-chained journal own every transition. The models own only the work of a single step. Every dispatch is receipted, so a run can be read back afterwards: what ran, what it cost, and what it changed.

The name is Sumerian. *mar-sa* is the shipyard, where specialized trades, strict ledgers, and sealed inspections certified a vessel before it touched open water.

## Status: upcoming

The source is not here yet. Nothing in this repository is runnable today, and there is no installation path to follow yet. Watching the repo or subscribing below is the way to know when that changes.

## Be notified when it is released

Two places, both new, both carrying the same material. Subscribe and the release reaches you.

- **The Agentic Ledger on Substack**, written work on agentic AI architecture:
  https://theagenticledger.substack.com/
- **The Agentic Ledger on YouTube**, the same work built and explained on screen:
  https://www.youtube.com/@TheAgenticLedger

You will get one email on the day this repository goes live.

You can also use GitHub's own **Watch → Releases only** on this repository.

## Companion repository

[`kidarai/marsah-corpus`](https://github.com/kidarai/marsah-corpus) holds the
quality-gate and technology-stack definitions Marsah reads when it builds.
