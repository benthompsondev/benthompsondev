# Portfolio Map

This is the plain map of what is worth looking at first on my GitHub.

The main story is practical automation: taking messy IT workflows, adding validation and guardrails, and turning them into something another admin could review or reuse. The repos here are public-safe versions of that work, plus a local-first app project and an older Python teaching archive.

## Start Here

| Area | Link | Why it is here |
| --- | --- | --- |
| Profile README | [benthompsondev](https://github.com/benthompsondev) | The front page for my public work |
| Main PowerShell portfolio | [enterprise-powershell-systems](https://github.com/benthompsondev/enterprise-powershell-systems) | Sanitized IT automation systems, demo data, run checks, logs, and reviewer docs |
| Local-first app project | [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) | Python / Streamlit / SQLite app with screenshots, demo data, privacy notes, and GitHub Actions |
| Python teaching archive | [comp10001-python-teaching-exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) | Earlier beginner Python examples and teaching support material |

## Enterprise PowerShell Systems

This is the flagship repo. It is built around work-inspired PowerShell systems that were sanitized for public release. The point is not to publish raw workplace scripts. The point is to keep the useful workflow shape: messy input, validation, review output, logs, fake data, and a demo check.

Helpful entry points:

| Page | Link | What it helps with |
| --- | --- | --- |
| Repo | [enterprise-powershell-systems](https://github.com/benthompsondev/enterprise-powershell-systems) | Main README, badges, run commands, and project overview |
| Script Index | [docs/script-index.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md) | Clickable map of every PowerShell demo script |
| Reviewer Guide | [docs/reviewer-guide.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md) | Best path through the repo if someone only has a few minutes |
| Public Release Checklist | [docs/public-release-checklist.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/public-release-checklist.md) | Privacy and quality checklist before adding a new sanitized script |
| GitHub Actions | [Actions](https://github.com/benthompsondev/enterprise-powershell-systems/actions) | Automated demo and quality checks |

Key systems:

| System | Link | What it shows |
| --- | --- | --- |
| Learner Onboarding Automation | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/learner-onboarding-automation) | Account/access planning from intake CSVs, mailbox planning, handoff output, logging, and demo checks |
| Password Remediation Workflow | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/password-remediation-workflow) | A staged weak-password follow-up process with state tracking and safe final action planning |
| Workstation Migration State Toolkit | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/workstation-migration-state-toolkit) | Device replacement workflow for capturing old-device state, restoring what can be restored, and tracking progress |
| O365 Migration Support Toolkit | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-messaging-systems/o365-migration-readiness-toolkit) | User, shared mailbox, public folder, licensing, and mailbox repair planning for a staged mail migration |
| Workforce Platform Identity Migration | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-identity-systems/workforce-platform-identity-migration) | Account creation, re-enable, OU review, mailbox/license planning, and project tracking reports |
| Browser Bookmark Migration Utility | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/browser-bookmark-migration) | Chrome-to-Edge bookmark migration with backups, merge logic, reporting, and manual recovery |
| Support And Code Review Utilities | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-support-systems/enterprise-support-and-code-review-utilities) | Smaller support scripts and sanitized reviewer notes showing code review, testing, and safer runbook thinking |

## Ledger Local Finance

Ledger is the app side of the portfolio. It is a local-first finance app built around Python, Streamlit, SQLite, Plotly, demo data, and simple checks someone can run on their own machine.

The important thing here is the product shape: local data, import flow, reports, screenshots, setup docs, and validation. It is still a work in progress, but it is a real app direction rather than a tiny script demo.

Helpful entry points:

| Page | Link | What it helps with |
| --- | --- | --- |
| Repo | [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) | Main README, project overview, and local run commands |
| Getting Started | [docs/GETTING_STARTED.md](https://github.com/benthompsondev/ledger-local-finance/blob/main/docs/GETTING_STARTED.md) | Setup path for someone trying it locally |
| Screenshots | [docs/screenshots](https://github.com/benthompsondev/ledger-local-finance/tree/main/docs/screenshots) | Visual walkthrough of the app |
| Security Notes | [SECURITY.md](https://github.com/benthompsondev/ledger-local-finance/blob/main/SECURITY.md) | Privacy boundaries and safe handling notes |
| GitHub Actions | [Actions](https://github.com/benthompsondev/ledger-local-finance/actions) | Validation runs for the app |

What this shows:

- Python app structure beyond one-off scripts
- Local-first data handling
- Streamlit UI work
- SQLite-backed workflows
- Demo data and screenshots
- Validation checks and GitHub Actions
- A practical open-source project I can keep improving over time

## COMP10001 Python Teaching Exercises

This repo is simpler and older, but it still belongs in the map.

[comp10001-python-teaching-exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) shows beginner Python examples from my earlier coding and teaching support work. It is not meant to compete with the PowerShell repo or Ledger. It shows where I started, how I explained programming basics, and why I care about making technical work easier for someone else to follow.

## What I Am Not Featuring

I removed the thin learning-only repos from the main public story because they made the profile harder to understand. I would rather show fewer projects that actually say something useful:

- real automation systems
- a local-first app
- teaching material with a clear purpose
- future projects that solve a practical problem

That is the bar I want this GitHub to keep moving toward.
