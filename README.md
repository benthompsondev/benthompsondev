# Ben Thompson

I work in healthcare information systems and systems support. The part of the job I enjoy most is taking disorganized operational work and turning it into something safer, repeatable, and easier for another person to trust.

Most of my strongest work is PowerShell automation around Microsoft 365, Active Directory / Entra ID, Exchange, SCCM, Intune, endpoint support, onboarding, migrations, reporting, and code review. I am building this GitHub as a public-safe version of that story: real workflow patterns, fake data, readable docs, validation checks, and projects that are useful enough to explain plainly.

I am aiming toward automation-heavy DevOps, cloud automation, platform/support automation, and practical software engineering work. Titles matter less to me than useful systems, good habits, accurate testing and work that solves real problems.

## Start Here

| If you only open one thing | Link | Why it matters |
| --- | --- | --- |
| Full portfolio map | [docs/portfolio-map.md](docs/portfolio-map.md) | The best index for everything public on this GitHub |
| Flagship automation repo | [enterprise-powershell-systems](https://github.com/benthompsondev/enterprise-powershell-systems) | Sanitized PowerShell systems based on real IT automation work |
| Script-by-script map | [PowerShell Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md) | Direct links to each script and what problem it solves |
| Local-first open-source finance app | [ledger-local-finance](https://github.com/benthompsondev/ledger-local-finance) | Python / Streamlit / SQLite app with screenshots, demo data, and validation |
| Python teaching archive | [comp10001-python-teaching-exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises) | Earlier Python teaching support and beginner examples |

## The Short Version

I like building practical tools for the parts of IT work that are too messy to ignore and too repetitive to keep doing by hand:

- Disorganized CSVs that need validation before anyone trusts them
- repeated account, mailbox, access, and endpoint tasks
- migration projects where the same checks happen again and again
- reports and logs that project teams can actually use
- scripts that need guardrails before they should be run by someone else
- documentation that makes a process repeatable instead of guarded knowledge

The pattern I keep coming back to is simple:

```text
input -> validate -> plan -> review -> act or simulate -> log -> verify
```

That is the thread through most of my public work.

## What I Have Built And Worked On

These are public-safe summaries of the kind of work behind the repos. Private workplace details, raw exports, internal names, and real data are intentionally not published.

| Area | What I worked on | Public artifact |
| --- | --- | --- |
| Account and access automation | Built PowerShell workflows for structured onboarding input, account planning, access planning, mailbox planning, handoff files, and logs | [Learner Onboarding Automation](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/learner-onboarding-automation) |
| Security follow-up automation | Turned weak-password follow-up into a staged process with reminder planning, state tracking, directory re-checks, and audit output | [Password Remediation Workflow](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-healthcare-systems/password-remediation-workflow) |
| Endpoint migration | Wrote automation around a Windows 11 hardware refresh project so old-device state could be captured, restored, tracked, and reviewed across many replacements | [Workstation Migration State Toolkit](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/workstation-migration-state-toolkit) |
| Browser standardization | Built a Chrome-to-Edge bookmark migration flow with backups, merge behavior, reporting, and a recovery path so users did not lose bookmarks during a browser move | [Browser Bookmark Migration Utility](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-endpoint-systems/browser-bookmark-migration) |
| O365 / Exchange migration support | Helped support a staged move from on-prem mail systems to O365, including user waves, shared mailbox readiness, license checks, public folder planning, and mailbox repair work | [O365 Migration Support Toolkit](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-messaging-systems/o365-migration-readiness-toolkit) |
| Workforce identity migration | Built planning/reporting scripts around messy project data, existing accounts, re-enable paths, project OU tracking, mailbox/license planning, and status exports | [Workforce Platform Identity Migration](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-identity-systems/workforce-platform-identity-migration) |
| Code review and team support | Reviewed scripts from other technical teams, tightened risky pieces, added validation/run notes, and explained changes in plain language before they were used | [Support And Code Review Utilities](https://github.com/benthompsondev/enterprise-powershell-systems/tree/main/enterprise-support-systems/enterprise-support-and-code-review-utilities) |

## Featured Repositories

### [Enterprise PowerShell Systems](https://github.com/benthompsondev/enterprise-powershell-systems)

This is my main portfolio repo.

It is built from sanitized versions of real workflow solutions I built in a large healthcare enterprise environment: onboarding, password remediation, Windows 11 device replacement, Chrome-to-Edge bookmark migration, workforce identity migration, O365 migration support, smaller troubleshooting utilities, and code review examples.

What I want this repo to prove:

- I can turn a manual process into a repeatable system.
- I care about validation, logs, state, rollback paths, and reviewable output.
- I can protect private data while still preserving the useful architecture.
- I can write docs and demo checks so another person can understand and run the work.
- I can review other people’s scripts and help make them safer before they hit production.

Good places to start:

- [Script Index](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/script-index.md)
- [Reviewer Guide](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/reviewer-guide.md)
- [Public Release Checklist](https://github.com/benthompsondev/enterprise-powershell-systems/blob/main/docs/public-release-checklist.md)
- [PowerShell demo checks](https://github.com/benthompsondev/enterprise-powershell-systems/actions/workflows/powershell-demo-check.yml)

### [Ledger Local Finance](https://github.com/benthompsondev/ledger-local-finance)

Ledger Finance is my open-source, local-first finance app. It is built for people who want more control over their financial data without subscriptions, cloud lock-in, or handing everything to a third-party service.

It is also the app-structure side of my portfolio: Python, Streamlit, SQLite, Plotly, statement imports, screenshots, demo data, local run checks, privacy notes, and GitHub Actions.

Good places to start:

- [Getting Started](https://github.com/benthompsondev/ledger-local-finance/blob/main/docs/GETTING_STARTED.md)
- [Screenshots](https://github.com/benthompsondev/ledger-local-finance/tree/main/docs/screenshots)
- [Security Notes](https://github.com/benthompsondev/ledger-local-finance/blob/main/SECURITY.md)
- [Ledger validation](https://github.com/benthompsondev/ledger-local-finance/actions/workflows/ci.yml)

### [COMP10001 Python Teaching Exercises](https://github.com/benthompsondev/comp10001-python-teaching-exercises)

This is older and simpler, but it belongs here.

It comes from my Python PASS Leader / teaching support work. It shows where the coding side started: breaking down programming concepts for newer learners, writing beginner examples, and explaining code in a way people can follow.

## Skills And Tools

| Area | Tools and experience |
| --- | --- |
| Automation | PowerShell, Python, CSV workflows, validation, reporting, logging, repeatable scripts |
| Microsoft / identity | Microsoft 365, Exchange Online, Teams, SharePoint, OneDrive, Entra ID / Azure AD, Active Directory |
| Endpoint / systems | SCCM, Intune, Windows deployment, Windows Server, Group Policy, endpoint troubleshooting |
| Operations support | migrations, onboarding, mailbox work, access reviews, documentation, vendor/team coordination |
| Growing into | GitHub Actions, Docker, Linux, Azure/cloud, testing, packaging, cleaner software architecture |
| Project habits | fake demo data, privacy reviews, readable READMEs, local checks, small reversible changes |

## Background

My current work is in a large healthcare IT / information systems environment, mostly around Microsoft 365, hybrid identity, endpoint deployment, automation, documentation, and enterprise troubleshooting.

Before that, I worked across desktop support, networking, security software deployment, imaging, print services, licensing, and end-user support. I also worked as a Python PASS Leader at Mohawk College, where I created beginner programming material and helped students get comfortable with code.

Education and certification:

- Computer Systems Technician - Network Systems, Mohawk College
- Network Engineering and Security Analyst, Mohawk College
- Bachelor of Sports Business Management, Honours, Brock University
- CompTIA A+

I keep a Linux/networking homelab to learn by building real systems, breaking them safely, and improving the setup each time.

## What I Am Building Toward

I want this GitHub to become a clean public trail of the kind of work I want more of:

- practical IT and systems automation
- cloud and DevOps-adjacent workflows
- useful PowerShell and Python projects
- local-first apps and tools
- CI checks, testing, docs, and privacy-safe examples
- projects that are easy for a teammate, recruiter, or anyone interested in tech to understand

The goal is not to collect the most repos. The goal is to show useful work that is organized, tested, and real enough to explain clearly.
