# Quark (hch) — minimal AI coding agent

This repository is initialized as a local workspace for Quark v1, the minimal C11 AI coding agent described by the upstream project at <https://github.com/Icecream-v0/Quark>.

The project goal is a single static `hch` binary with terminal, GUI, and swarm workflows.

## Current status

This workspace currently contains the project landing page and metadata scaffold so future development can proceed on the current branch.

## Planned surfaces

- `hch` — interactive terminal agent.
- `hch gui` — browser GUI served locally.
- `hch "task"` — one-shot headless agent run.
- `hch swarm -n 3 "task"` — parallel agent attempts with best result applied.

## Build

The full implementation is expected to be C11 and buildable with `make` once source files are added.
