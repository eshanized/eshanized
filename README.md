<div align="center">

# Eshan Roy · `eshanized`

**Systems engineering · Developer infrastructure · Open source**

I build software close to the machine: Linux tooling, developer workflows, infrastructure, and autonomous engineering systems.

[GitHub](https://github.com/eshanized) · [LinkedIn](https://www.linkedin.com/in/eshanized/) · [Tonmoy Infrastructure](https://tonmoyinfrastructure.org)

</div>

---

## Current focus

| Project | What it does | Stack |
|---|---|---|
| [M31A](https://github.com/eshanized/M31A) | Rust-native terminal coding agent focused on policy-controlled tool execution, recoverable workflows, and evidence-based verification. | Rust · Ratatui · SQLite |
| [Snigdha OS](https://gitlab.com/Snigdha-OS) | An Arch-based Linux ecosystem focused on desktop experience and system tooling. | Linux · Arch · i3 |
| [Octate](https://github.com/eshanized/Octate) | Developer-oriented code review tooling with local static analysis and optional model-backed review. | TypeScript · Node.js |
| [OpenMail](https://github.com/eshanized/OpenMail) | Self-hosted webmail for organizations using existing IMAP/SMTP infrastructure, without third-party AI analysis of mail content. | PHP · Laravel · Livewire |
| [SLMGen](https://github.com/eshanized/SLMGen) | A toolkit that prepares dataset analysis and fine-tuning workflows for small language models. | Python · FastAPI · TypeScript |
| [Runstead](https://github.com/eshanized/Runstead) | A hosting-business platform concept with an interactive browser-first product simulation. | Next.js · TypeScript |

Project capabilities and release status vary. Follow each repository's README, issues, release notes, and CI workflow for the current implementation status.

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
