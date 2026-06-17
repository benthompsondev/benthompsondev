# Portfolio Map

This is the starting point for my public GitHub.

If someone only has a few minutes, this page should make it clear what to open first, what each repo is meant to show, and where the useful docs, scripts, screenshots, and run checks live.

My strongest skills right now is practical IT automation: taking disorganized operational work, adding validation and guardrails, and turning it into something repeatable. I also want this page to show the other side of the portfolio my personal projects I am building and my roots: a local-first app project, older Python teaching material, and the path I am building toward with DevOps, cloud, and cleaner software habits.

## Quick Path

| If you want to see... | Open this first | Why |
| --- | --- | --- |
| My best automation work | [Enterprise PowerShell Systems](https://github.com/benthompsondev/enterprise-powershell-systems) | The flagship repo: sanitized PowerShell systems, fake data, run checks, reviewer docs, and GitHub Actions |
| The fastest script-by-script map | [PowerShell Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md) | Direct links to each demo script and the problem it solves |
| My practical open-source project | [Ledger Local Finance](https://github.com/benthompsondev/ledger-local-finance) | Local-first Python app with Streamlit, SQLite, screenshots, demo data, and validation |
| My early Python / teaching background | [COMP10001 Python Teaching Exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) | Beginner Python exercises from my PASS Leader / teaching support work |
| The public profile landing page | [benthompsondev](https://github.com/benthompsondev) | Short version of who I am, what I build, and what to open first |

## Public Repo Index

| Repo | Type | Best links | What it shows |
| --- | --- | --- | --- |
| [enterprise-powershell-systems](https://github.com/benthompsondev/enterprise-powershell-systems) | Flagship automation portfolio | [Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md), [Reviewer Guide](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md), [Actions](https://github.com/benthompsondev/enterprise-powershell-systems/actions) | PowerShell automation for account workflows, security follow-up, endpoint migrations, O365 migration support, reporting, validation, and code review |
| [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) | Open-source personal app | [Getting Started](https://github.com/benthompsondev/ledger-local-finance/blob/main/docs/GETTING_STARTED.md), [Screenshots](https://github.com/benthompsondev/ledger-local-finance/tree/main/docs/screenshots), [Security Notes](https://github.com/benthompsondev/ledger-local-finance/blob/main/SECURITY.md), [Actions](https://github.com/benthompsondev/ledger-local-finance/actions) | Python app structure, local-first data handling, Streamlit UI, SQLite, demo data, and a product idea I can keep improving |
| [comp10001-python-teaching-exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) | Learning / teaching archive | [README](https://github.com/benthompsondev/comp10001-python-teaching-exercises/blob/main/README.md) | Earlier Python fundamentals, teaching support, and breaking code down for newer learners |
| [benthompsondev](https://github.com/benthompsondev/benthompsondev) | Profile repo | [Profile README](https://github.com/benthompsondev), [This Map](https://github.com/benthompsondev/benthompsondev/blob/main/docs/portfolio-map.md) | The front door for the portfolio |

## Work-Inspired Automation

The PowerShell repo is probably the best place to start. It’s where I’m turning the systems, scripts, fixes, and automations I’ve built from real enterprise IT work into public-safe projects with fake data, clear run steps, and no private details.

These are not raw workplace scripts. They are cleaned public demos based on real types of IT work: messy CSVs, account planning, security follow-up, endpoint replacement, messaging migration, project reporting, and code review. Private details are removed and replaced with fake users, fake domains, local files, and simulated actions.

What I want this repo to show:

- I can take a disorganized operational problem and turn it into a repeatable workflow.
- I care about validation before action.
- I write outputs and systems that another admin or project team can review.
- I think about logs, handoff files, state tracking, and rollback paths.
- I can sanitize work-inspired automation without flattening it too much.
- I can use GitHub Actions and demo checks so the repo is not just a pile of scripts.

### PowerShell Systems

| System | Link | What it handles | What to notice |
| --- | --- | --- | --- |
| Learner Onboarding Automation | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/learner-onboarding-automation) | Intake CSV validation, directory action planning, group/access planning, mailbox planning, handoff files, notification drafts, logs, and sample output | The full workflow shape: input, validation, planning, output, and review |
| Password Remediation Workflow | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/password-remediation-workflow) | Security export conversion, staged reminders, mock directory checks, cycle state, final reset planning, archive output, and audit logs | Stateful automation instead of a one-time script |
| Workforce Platform Identity Migration | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-identity-systems/workforce-platform-identity-migration) | Source data validation, account create/re-enable planning, project OU review, mailbox/license planning, and reporting | Project tracking and identity cleanup around a large platform migration |
| Browser Bookmark Migration Utility | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/browser-bookmark-migration) | Chrome bookmark backup, Edge favorite merge, multi-profile handling, reporting, and manual recovery | A small endpoint script built around avoiding user pain during a browser standardization move |
| Workstation Migration State Toolkit | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/workstation-migration-state-toolkit) | Old-device state capture, new-device restore planning, app/printer/local group inventory, master tracking, and directory prep | Automation that helped make a large device replacement project easier to run and track |
| O365 Migration Support Toolkit | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-messaging-systems/o365-migration-readiness-toolkit) | User migration waves, shared mailbox readiness, license group review, public folder planning, mailbox repair, and summary reports | Multiple scripts solving different problems in a staged on-prem to O365 migration |
| Enterprise Support And Code Review Utilities | [folder](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-support-systems/enterprise-support-and-code-review-utilities) | Smaller support utilities plus sanitized reviewer notes and templates | Code review, troubleshooting, and helping other teams make scripts safer to run |

### Best Entry Points In The PowerShell Repo

| Page | Link | Why it exists |
| --- | --- | --- |
| Script Index | [docs/script-index.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md) | Clickable map of every script |
| Reviewer Guide | [docs/reviewer-guide.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md) | Best route through the repo if someone is reviewing it quickly |
| Public Release Checklist | [docs/public-release-checklist.md](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/public-release-checklist.md) | Privacy and quality checklist before I add more work-inspired material |
| GitHub Actions | [Actions](https://github.com/benthompsondev/enterprise-powershell-systems/actions) | Proof that the demo checks and PowerShell quality checks run after changes |

## Open Source And Personal Projects

This section is for projects that are not just sanitized work automation. These are personal or open-source projects that someone could download, run, learn from, or build on.

### Ledger Local Finance

[Ledger Local Finance](https://github.com/benthompsondev/ledger-local-finance) is a local-first personal finance app.

I am building it because I like tools that keep private data local and still feel useful. It is also a different kind of portfolio proof than the PowerShell repo: app structure, UI, imports, persistence, screenshots, setup docs, and validation.

| Area | Link | What it shows |
| --- | --- | --- |
| Main repo | [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) | Project overview and run commands |
| Getting started | [docs/GETTING_STARTED.md](https://github.com/benthompsondev/ledger-local-finance/blob/main/docs/GETTING_STARTED.md) | How someone can try the app locally |
| Screenshots | [docs/screenshots](https://github.com/benthompsondev/ledger-local-finance/tree/main/docs/screenshots) | What the app looks like without needing real financial data |
| Security notes | [SECURITY.md](https://github.com/benthompsondev/ledger-local-finance/blob/main/SECURITY.md) | Privacy boundaries and what should stay local |
| Validation | [Actions](https://github.com/benthompsondev/ledger-local-finance/actions) | Checks that run against the app |

What Ledger is meant to show:

- Python app structure beyond one-off scripts
- Streamlit UI work
- SQLite-backed local data
- statement/import thinking
- screenshots and demo data
- privacy-first design habits
- setup docs that someone else can follow
- a project I can keep improving over time

## Learning And Teaching

This section is for older learning and teaching material. It is not the main portfolio lane, but it helps explain where the coding side started.

### COMP10001 Python Teaching Exercises

[COMP10001 Python Teaching Exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) contains beginner Python examples from my PASS Leader / teaching support work.

This repo matters because it shows a different skill: explaining code to people who are still getting comfortable with it. That connects directly to the kind of work I enjoy now: making technical systems easier to understand, easier to test, and easier for someone else to pick up.

What it shows:

- Python fundamentals
- simple examples for newer learners
- teaching and explanation
- early coding background before the heavier automation work

## What I Am Building Toward

The direction is pretty simple:

- keep expanding the PowerShell repo with useful sanitized systems
- keep improving Ledger as the main local-first app project
- add future projects only when they solve real problems and are practically useful to others
- keep docs, checks, screenshots, and examples strong enough that someone else can follow them
- keep GitHub focused on work I can actually explain in an interview or to another technical person

The goal is not to have the most repos. The goal is to have a clear public trail of the useful work I've done.
