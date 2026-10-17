<div align="center">

# Eshan Roy · `eshanized`

**Systems engineering · Developer infrastructure · Open source**

I build software close to the machine: Linux tooling, developer workflows, infrastructure, and autonomous engineering systems.

[GitHub](https://github.com/eshanized) · [LinkedIn](https://www.linkedin.com/in/eshanized/) · [Tonmoy Infrastructure](https://tonmoyinfrastructure.org)

</div>

---

## Flagship work

### [M31A](https://github.com/eshanized/M31A) · autonomous software engineering

A Rust-native terminal coding agent built around runtime-owned policy decisions, recoverable workflows, and evidence-based verification.

`Rust` `Ratatui` `SQLite` · [Documentation](https://github.com/eshanized/M31A/tree/master/docs) · [Releases](https://github.com/eshanized/M31A/releases)

### [Snigdha OS](https://gitlab.com/Snigdha-OS) · Linux systems

An Arch-based Linux ecosystem focused on desktop experience, system tooling, and the performance/elegance balance.

`Linux` `Arch` `i3` · [GitLab projects](https://gitlab.com/Snigdha-OS)

### [OpenMail](https://github.com/eshanized/OpenMail) · privacy-first webmail

Self-hosted organizational webmail that connects to existing IMAP/SMTP infrastructure. It deliberately avoids third-party AI analysis of message content.

`PHP` `Laravel` `Livewire` · [Setup guide](https://github.com/eshanized/OpenMail/blob/master/SETUP.md) · [Security policy](https://github.com/eshanized/OpenMail/blob/master/SECURITY.md)

## Other projects

- [Octate](https://github.com/eshanized/Octate) — code-review tooling combining local static analysis with optional model-backed review. `TypeScript` `Node.js`
- [SLMGen](https://github.com/eshanized/SLMGen) — tools for dataset analysis and small-language-model fine-tuning workflows. `Python` `FastAPI` `TypeScript`
- [Runstead](https://github.com/eshanized/Runstead) — a hosting-business platform concept with an interactive browser-first simulation; infrastructure actions and payments are simulated. `Next.js` `TypeScript`

Project capabilities and release status vary. Follow the repository README, issue tracker, release notes, and CI workflow for current implementation status.

## Verify the work

I prefer implementation evidence over vanity metrics. These links go directly to each project's automation and release history; they do not imply that every workflow is currently passing.

| Project | CI / checks | Releases |
|---|---|---|
| [M31A](https://github.com/eshanized/M31A) | [Release gates](https://github.com/eshanized/M31A/actions/workflows/release-gates.yml) · [Build workflows](https://github.com/eshanized/M31A/actions) | [Releases](https://github.com/eshanized/M31A/releases) |
| [OpenMail](https://github.com/eshanized/OpenMail) | [CI workflow](https://github.com/eshanized/OpenMail/actions/workflows/ci.yml) | [Releases](https://github.com/eshanized/OpenMail/releases) |
| [Octate](https://github.com/eshanized/Octate) | [CI workflow](https://github.com/eshanized/Octate/actions/workflows/ci.yml) | [Releases](https://github.com/eshanized/Octate/releases) |
| [SLMGen](https://github.com/eshanized/SLMGen) | [CI workflow](https://github.com/eshanized/SLMGen/actions/workflows/ci.yml) | [Releases](https://github.com/eshanized/SLMGen/releases) |
| [Runstead](https://github.com/eshanized/Runstead) | [CI workflow](https://github.com/eshanized/Runstead/actions/workflows/ci.yml) | [Releases](https://github.com/eshanized/Runstead/releases) |

## Engineering principles

- **Architecture before implementation.** Keep domain boundaries understandable and explicit.
- **Measure before optimizing.** Prefer reproducible evidence over performance claims.
- **Fail visibly.** Return actionable errors instead of hiding broken or unsupported paths.
- **Treat inputs as untrusted.** Validate external data, model output, repository content, and user-supplied configuration.
- **Make recovery part of the design.** Cancellation, checkpoints, rollback, and diagnostics are not afterthoughts.
- **Test behavior, not just code paths.** Use unit tests for local invariants, integration tests for boundaries, and end-to-end tests for critical user journeys.

## Technical interests

**Systems:** Rust, Go, Linux, shell tooling  
**Application engineering:** TypeScript, React, Next.js, Flutter, PHP  
**Infrastructure:** Git, CI/CD, deployment automation, databases  
**Applied research:** small language models, dataset pipelines, evaluation workflows

## Open source

I value focused issues, reproducible bug reports, reviewable pull requests, and documentation that reflects what the code actually does.

- [Browse my repositories](https://github.com/eshanized?tab=repositories)
- [Report a bug or request a feature](https://github.com/eshanized/M31A/issues) · use the relevant project's issue tracker for project-specific reports
- [Explore Tonmoy Infrastructure](https://tonmoyinfrastructure.org)

---

<sub>Maintained by Eshan Roy. Prefer verifiable behavior and current project documentation over unverified feature or performance claims.</sub>
