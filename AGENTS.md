# AGENTS.md: AmiTCP_NG

## Read first

This repository targets the Apollo V4 platform. Before doing anything else,
read `ApolloKnowledgeBase/AGENTS.md` and follow it. It explains the platform,
the assumptions you must not make, and which knowledge base files to read for
your task. Paths in that file are relative to `ApolloKnowledgeBase/`.

If `ApolloKnowledgeBase/` is empty, the submodule has not been initialized.
Ask the user to run `git submodule update --init` instead of proceeding
without it.

## This repository

- **What it is:** a modernised open TCP/IP stack for 68k AmigaOS: a fork of AmiTCP/IP 3.0b2 extended into a drop-in replacement for Roadshow's bsdsocket.library. See README.md, PLAN.md and docs/.
- **Kind:** library
- **Target core:** not set yet
- **Target model:** not set yet
- **Target OS:** AmigaOS (versions not set yet)
- **Execution mode:** os-friendly
- **Languages:** C

Fields marked `not set yet`: ask the developer before relying on them, and fill them in.

## Relevant knowledge base areas

- `ApolloKnowledgeBase/os/`
- `ApolloKnowledgeBase/toolchain/`

## Build and test

See `docs/BUILDING.md` (and `README.md`, `PLAN.md`, `PORTING.md` for the design). Build and fix all errors and warnings before presenting code.

## Knowledge base feedback

When you find something missing or wrong in ApolloKnowledgeBase while working
here, tell the user and offer to draft a change following
`ApolloKnowledgeBase/CONTRIBUTING.md`.

Offer a lesson when the user says the project, a release or a milestone is
done, and right away when an assumption turns out wrong. Follow
`ApolloKnowledgeBase/AGENTS.md` section 8: draft it from the lesson template,
show it to the user, and only submit it (as a pull request from the
`ApolloKnowledgeBase/` submodule) with their approval.
