# task-v1

**Open-source developer tools and server infrastructure maintained by [@Taskov1ch](https://github.com/Taskov1ch).**

This organization is the home for my larger projects, shared components, and tools that benefit from living independently from my personal repositories.

The current focus is on **Python tooling, automation, reproducible environments, CI/CD, and game-server infrastructure**.

---

## Luminesk

Luminesk is a Docker-first toolchain for creating and operating reproducible Minecraft Java and Bedrock server instances.

Instead of treating a server installation as a collection of manual steps, Luminesk describes it as a reviewable recipe with explicit inputs, sources, runtime configuration, persistent data, and readiness rules.

### [luminesk-cli](https://github.com/task-v1/luminesk-cli)

The main Python CLI.

It handles installation, updates, configuration, lifecycle management, validation, recovery, and automation of server instances.

Key areas include:

* declarative server recipes;
* reproducible artifact and container identities;
* Docker-based runtime management;
* interactive and non-interactive workflows;
* dry-run planning;
* transactional updates;
* rollback and recovery;
* cross-platform installation;
* automated testing and static analysis.

**Stack:** Python · Docker · HTTP · pytest · mypy · Ruff · GitHub Actions

[Repository](https://github.com/task-v1/luminesk-cli) · [Documentation](https://luminesk.taskov1ch.xyz)

### [luminesk-database](https://github.com/task-v1/luminesk-database)

The official Git-backed catalog of recipes consumed by Luminesk CLI.

The repository provides validation rules, public schemas, compatibility checks, deterministic index generation, and CI-driven publication of catalog snapshots.

**Stack:** Python · TOML · GitHub Actions · CI/CD · Schema Validation

[Repository](https://github.com/task-v1/luminesk-database)

---

## Other projects

### [AstraAuction](https://github.com/task-v1/AstraAuction)

A player-to-player marketplace plugin for the Lumi server ecosystem.

It provides asynchronous persistence, SQLite/MySQL support, item-state preservation, search and sorting, configurable transaction fees, localization, and storage for offline seller payments and expired listings.

**Stack:** Java · SQLite · MySQL · Gradle

---

## Engineering focus

Projects in this organization generally explore or use:

`Python` · `Docker` · `Linux` · `Automation` · `CI/CD` · `GitHub Actions` · `Testing` · `Validation` · `Developer Tooling`

The goal is to build tools with predictable behavior, explicit configuration, reproducible workflows, and enough documentation to be usable outside the development environment.

---

## Archived projects

Older experiments and previous-generation projects are kept archived when they are no longer actively maintained.

Archived repositories are preserved for historical reference and should not be assumed to represent the current architecture or development practices of active projects.

---

## Maintainer

Maintained by **[Taskov1ch](https://github.com/Taskov1ch)**.

[Personal website](https://taskov1ch.xyz) · [GitHub profile](https://github.com/Taskov1ch)
